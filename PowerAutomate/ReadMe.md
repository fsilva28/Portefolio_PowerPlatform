The flow is triggered by a webhook subscription for the "contact" entity. If the value of the "msdyn_isminorwithparentalconsent" field starts with 't', an approval is started and waited for, an email is sent to the assigned user, and the "msdyn_isminorwithparentalconsent" field is updated to false. Otherwise, an email is sent to the emailaddress1 field.

![Captura de ecrã 2024-04-18 194356](https://github.com/fsilva28/Portefolio_PowerPlatform/assets/159443064/20b53bb4-9bd0-48c6-ab12-7b832b76558f)

The flow starts with a button trigger. It then creates a basic approval with the title "Sair Mais Cedo II" and assigns it to an email address. The approval details are "Posso sair mais cedo ou quê?". Notifications and reassignment are enabled. A card is posted in a channel with the approval details. The flow waits for the approval to be completed. Finally, an email is sent to assigned email address with the subject "Baza!" and the message "Podes sair mais cedo. Andor!".

![Captura de ecrã 2024-04-18 195733](https://github.com/fsilva28/Portefolio_PowerPlatform/assets/159443064/b2a0be69-3cfd-402d-8284-27ebce3ed7ab)

The flow starts by subscribing to a webhook trigger for a specific entity. If the price is less than 500, an approval is started and waited for. If the outcome is "Approve", an email is sent with the message "A sua requisição foi aceite" (Your request has been approved). If the outcome is not "Approve", a rejection email is sent. If the price is equal to or greater than 500, a different approval process is started. If all approvals are "Approve", an acceptance email is sent. Otherwise, a rejection email is sent. Finally, the status of the approval is updated in the record.

![Captura de ecrã 2024-04-18 195336](https://github.com/fsilva28/Portefolio_PowerPlatform/assets/159443064/67f9a7e9-d933-4fc4-8b29-3c9fc00d4932)

The flow starts with a webhook trigger for a specific entity in Common Data Service. It then retrieves the content of a file from OneDrive for Business and converts it to a data URI. The flow then sends an approval request to a group of users and waits for their response. If the approval outcome is "Approve", it sends an email based on the value of the "Modalidade" field. If the outcome is not "Approve", it sends a rejection email. Finally, it updates the status of the record in Common Data Service.

![Captura de ecrã 2024-04-18 195449](https://github.com/fsilva28/Portefolio_PowerPlatform/assets/159443064/497b37ba-354e-466c-85e3-c039dc850d81)
