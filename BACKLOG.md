[Epic 1] Connecting the mobile pohone to the smart coffee machine 

User Story 1: As an employee, I want to create an account in the application so that I can connect to the smart coffee machine. 

Acceptance Criteria:
- The system verifies that the device is connected to Wi-Fi before attempting pairing.
- If Wi-Fi is not enabled, the system displays the message: “Please connect to a Wi-Fi network”.
- The system displays nearby coffee machines available for pairing.
- The system verifies that the phone and the coffee machine are successfully paired.
- The system allows entering a corporate email as the username.
- The system allows entering a password consisting of the employee ID.
- Upon clicking “Register” the system validates the entered data.
- If the data is valid, the user receives confirmation that the profile has been successfully created.
- The user is automatically redirected to the application Home screen.


User Story 2: As an application user, I want to access my profile so that I can edit and customize it. 

Acceptance Criteria:
- The system displays the currently saved user information (name and profile picture).
- The system allows editing the user’s name.
- The system allows adding or changing a profile picture from the user’s phone gallery.
- By clicking “Save” all changes are stored.
- After successful saving, the user receives confirmation of the update.


[Epic 2] Defining parameters for preparing “Favorite coffee” 

User Story 1: As a registered application user, I want to configure coffee preparation parameters so that I can personalize my coffee according to my preferences. 

Acceptance Criteria:
- The system allows selecting the coffee quantity in grams (minimum 5g, maximum 20g).
- The system allows selecting the grinding level on a scale from 1 to 15.
- The system allows selecting the water quantity in milliliters (from 50ml to 250ml).
- By clicking “Start” the system initiates coffee preparation.
- The system displays preparation steps (grinding - water heating - brewing).


User Story 2: As an application user, I want to save the defined parameters as a favorite coffee so that I can use them in the future. 

Acceptance Criteria:
- After successful preparation, the option “Save as Favorite” is displayed.
- The system allows entering a unique name under which the defined parameters will be saved.
- If the name already exists, the system displays the message: “Name already exists. Please enter a unique name”.
- By selecting “Save” the coffee configuration is added to the “Favorites” list within the user profile.


[Epic 3] Notifications about machine status 

User Story 1: As an application user, I want to receive notifications about insufficient ingredient levels so that I know when it is necessary to refill it. 

Acceptance Criteria:
- The system continuously monitors water and coffee levels in the machine.
- If the level of any ingredient falls below the minimum required for preparation, the system sends a notification.
- The notification contains information about which ingredient needs to be refilled.
- Once the machine registers a refill, the user receives confirmation that preparation can be started.
