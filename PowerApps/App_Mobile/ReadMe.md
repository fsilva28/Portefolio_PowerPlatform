Login Page - there are two text inputs (username & password) that are sent to a button ("Iniciar Sessão") wich code checks if the username and password fields are blank. If not, it looks up the username in a data table and verifies if the entered password matches the stored one. If the credentials are correct, it navigates to the Home screen; otherwise, it sets a variable with the entered username. Finally, it resets the username and password fields.

![Captura de ecrã 2024-04-18 122504](https://github.com/fsilva28/Portefolio_PowerPlatform/assets/159443064/2df841bb-ab3e-42e5-8c10-e79e5e739048)

Home Page - The text label generates a welcome message by fetching the name associated with the email address of the currently logged-in user from the "UsersInfo" table and concatenating it with the string "Bem-vindo, ".

![Captura de ecrã 2024-04-18 122520](https://github.com/fsilva28/Portefolio_PowerPlatform/assets/159443064/00eff6b0-9aaa-493f-8ac2-5aae54321595)

Recover Password Page - The button "Recuperar Password" updates a user's password in a database, checks if the update was successful, notifies the user accordingly, and then resets input fields and clears a username variable.

![Captura de ecrã 2024-04-18 122534](https://github.com/fsilva28/Portefolio_PowerPlatform/assets/159443064/3da8c6c6-6e58-44be-9b3b-8809c8b6a920)

Checks_Local Page - This page contains three buttons, redirecting to Checks_List Page. 

![Captura de ecrã 2024-04-18 122551](https://github.com/fsilva28/Portefolio_PowerPlatform/assets/159443064/0d7fa6f9-090c-4df6-8454-faec1430ed28)

Chekcs_List Page - this page is directly related to the previous page, opening information according to the selection on Checks_Local page. It allows a navigate to Gym_Management page, and to check a toggle regarding the existence of pictures. The "Enviar registo" button updates or creates records in "ItemsRegisters" with values from variables and toggles, clears uploaded photos, and refreshes maintenance records.

![Captura de ecrã 2024-04-18 122603](https://github.com/fsilva28/Portefolio_PowerPlatform/assets/159443064/655fba7f-b4c4-42d0-9589-a3ffa1cd470c)

Gym_Management Page - This page contains a Camera component, a button that captures pictures, adding them to a collection. The last picture taken is shown giving the user the option to navigate to the Gym_Management_Gallery Page or deleting the last picture taken.

![Captura de ecrã 2024-04-18 122642](https://github.com/fsilva28/Portefolio_PowerPlatform/assets/159443064/73ca8331-b39b-4a5a-b7d6-6dfe320cda2d)

Gym_Management_Gallery Page - In this page there is a gallery with the pictures taken in the previous page, the status and a text input that allows the user to write some observations. There are two buttons: one enables the deletion of pictures; the other updates or creates records in "Manutencaos" with values from variables, current date, image data, dropdown selection, and text input. Afterward, it navigates the user to the "Checks_List" screen with a fade transition.

![Captura de ecrã 2024-04-18 122933](https://github.com/fsilva28/Portefolio_PowerPlatform/assets/159443064/abceb109-46a4-491f-8c78-cc792baa1382)

The flow chart of the app shows that after login, the users are directed to the home page (login page can also direct users to the recover password page). Once in the Home Page, users are able to navigate to the Checks_Local page through a button on the header of the page. From there, users can navigate back or procede to Gym_Management page from where they're directed to the Gym_Management_Gallery and from there to the Checks_List page. At any time, users have the possibility to navigate to the Home page via a button on the header.

![ScreenNavigation](https://github.com/fsilva28/Portefolio_PowerPlatform/assets/159443064/58fbf0a2-0d66-40b8-89db-19cd9f4501b7)
