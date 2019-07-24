# Artist Resume

We want to create a new way for Supporting Artists to show their resume online. We want you to design the data model and demonstrate how this information will be collected and used.

Please implement the solution step by step; ideally as completely as you can.

When implementing the resume you do not have to implement the UI if you do not want to. Instead you can use unit tests or a similar framework to demonstrate how your data model works. The data model and corresponding functionality should demonstrate how the system could be connected to a frontend (i.e. handling partial updates of fields).

You do not need to implement a datastore or database model just demonstrate a typical data structure for the language you have chosen to take the test in. There might be some follow-up questions on how we might persist the data but you will not have to implement it.

## Basic information

We need artists to submit their information and only some of it should be used in the public resume.
We need to collect and the following information:

* Name
* Stage Name (optional)
* Address 
* Email
* Telephone number
* Skills (optional)
* Languages spoken (optional)
* Biography (optional)

We should show the following pieces of information: Stage Name if supplied, otherwise Name; the Town or City element of the address; Skills; Languages; Biography.

## Payroll

Artists need to be able to supply multiple home and billing addresses along with contact names for the addresses as some have agents who manage their business affairs and others temporarily move to the location where they are shooting for the duration of the production.

We also need to capture their tax code information (National Insurance number for UK artists, Social Security for US) and bank account information. 

Again there might be multiple bank accounts for personal and business payments, we need to capture both for different processes.

### Advanced information

For some skills (horse riding, singing, dancing and fencing) we need to capture whether the artist has Basic or Advanced levels of ability. We may need to allow the artist to provide a clarifying note.

The same is true of languages. We also want to have a key list of languages that people want to cast for. Artists can still supply any language they want.

### Search

Add a basic search function that allows us to find people with specific Skills or Languages.

If possible we would like to also be able to differentiate between different levels of competency.
