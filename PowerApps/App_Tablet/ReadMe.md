Login Page - there are two text inputs (username & password) that are sent to a button ("Iniciar Sessão") wich code checks if the username and password fields are blank. If not, it looks up the username in a data table and verifies if the entered password matches the stored one. If the credentials are correct, it navigates to the Home screen; otherwise, it sets a variable with the entered username. Finally, it resets the username and password fields.

![Captura de ecrã 2024-04-18 165210](https://github.com/fsilva28/Portefolio_PowerPlatform/assets/159443064/dedde6ad-9818-4d7f-a780-dbce043d3207)

Home Page - The text label generates a welcome message by fetching the name associated with the email address of the currently logged-in user from the "UsersInfo" table and concatenating it with the string "Bem-vindo, ".

![Captura de ecrã 2024-04-18 165236](https://github.com/fsilva28/Portefolio_PowerPlatform/assets/159443064/e5f5298c-2e85-40f6-967d-c00990b1efbe)

Recover Password Page - The button "Recuperar Password" updates a user's password in a database, checks if the update was successful, notifies the user accordingly, and then resets input fields and clears a username variable.

![Captura de ecrã 2024-04-18 165256](https://github.com/fsilva28/Portefolio_PowerPlatform/assets/159443064/ff53769b-6114-49dd-bf72-3ec1011a5b9c)

![Captura de ecrã 2024-04-18 165308](https://github.com/fsilva28/Portefolio_PowerPlatform/assets/159443064/312a8dc8-b1a6-4d19-8a31-47081963bef5)

![Captura de ecrã 2024-04-18 165333](https://github.com/fsilva28/Portefolio_PowerPlatform/assets/159443064/19984189-b7e6-41ae-babb-cd273f270b76)

![Captura de ecrã 2024-04-18 165354](https://github.com/fsilva28/Portefolio_PowerPlatform/assets/159443064/e437aea5-6a00-4ab8-9f5d-228b598eda71)
