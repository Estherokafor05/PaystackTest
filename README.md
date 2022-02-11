# Documentation

### Running the Test
#### Cloning the Repository
1. From the main page, click on the CODE button to download the folder to your computer OR 
use *git clone https://github.com/EXAMPLE/YOUR-REPOSITORY* to clone into your computer.
2. Navigate to the folder where you downloaded the project on your computer.

#### Exporting Cloned Files to your Postman Machine
1. Launch Postman.
2. Create a new workspace for the collection.
3. Open the new workspace created on postman.
4. Click on the **IMPORT** button
5. Select the **FOLDER** tab on the pop up window. 
6. Choose **tests** folder in the downloaded project.
7. Click the **IMPORT** button to complete the file importation to your postman.

#### Running Postman Collection 
After postman collection is imported open the **regression-test-suite** collection, Click on the three dots **(...)** option and select **run collection**.

#### Running Mock Name Change
1. Select **MOCK SERVERS** on your postman.
2. click on the **NEW** button in the mock server workspace.
3. From the opo up window click on **MOCK SERVER**.
4. Click on **select an existing collection** tab.
5. Choose the collection **mock-name-change**.
6. Type a server name in the **Mock server name** text field.
7. Under Environment, check the **Save the mock server URL as an environment variable** checkbox.
8. Click **Create mock server** button to create your mock server.
9. Go to your **mock-name-change** collection.
10. Set your environment to the name of the environment created by your mock server in step 7.
11. Run the request.




