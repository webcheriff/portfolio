# Rostislav Cherepanov - portfolio

Below are links to files that demonstrate my skills in the appropriate app or area.

## Maintenance of documentation

### Checklist in Google Documents

[Link to the checklist in Google Docs](https://docs.google.com/spreadsheets/d/1Hc3tJqIDyNmGdxQrubZLAf-fjmpPrXA9Z1Y6-yMejwQ/edit?usp=sharing)

Here I have compiled a list of tests for the project on testing the API of the educational application Yandex Counter.

To test the four endpoints in the Yandex Counter API, I made a checklist using test design techniques - equivalence classes and boundary values.
Due to project conditions there was little time for testing, so the format of test cases did not fit. And the use of EC and BV techniques allowed an optimal number of inspections.

### YouTrack

[Link to YouTrack](https://cherrost.youtrack.cloud/)

The board contains reports of defects that I found while completing projects: training and test tasks for company vacancies.

### Miro

[Link to the board in Miro](https://miro.com/app/board/uXjVP5XSdL0=/?moveToWidget=3458764566784593677&cot=14)

On the board is a diagram of connections, which I based on the analysis of requirements to the application Yandex Routes.

## SQL & Automation API

### Postman

[Reference to the workspace in Postman](https://www.postman.com/rostislav-postman/workspace/cher-rost-public)

In this workspace there are two collections: in one I have automated part of the test (description in the collection) for the online pet store, and in the other I have compiled a set of necessary checks to test the educational application Yandex Scooter.

### PyCharm and SQL

[Link to project repository in PyCharm on GitHub](https://github.com/webcheriff/project_11_automate_checklist.git)

This link contains the project to automate the checklist for a specific field in the request to create a set of products in the educational application Yandex Counter.

[Link to project repository in PyCharm with SQL on GitHub](https://github.com/webcheriff/project_12_final_project.git)

Here is a project to automate the finished scenario and database queries.

#### Automation

* Customer creates order.
* Check that on the track you can get the order details.

##### Queries

* Check whether the created order is displayed in the database.

> To do this, I have deduced the list of couriers' logins with the number of their orders in the status `In delivery`.

* Ensure that the order status is recorded correctly in the database.

> For this I have deduced all the trackers of orders and their statuses.
>
> Statuses determined by the following rule:
>
> * If `finished == true`, I derived the status 2.
> * If `cancelled == true`, I derived the status -1.
> * If `inDelivery == true`, I derived the status 1.
> * For the rest of cases I deduced 0.

## HTML, CSS. Frontend, backend

### Simulators

On these simulators, I worked with cross-platform and cross-browser testing, checked layouts, frontend requests, and backend responses.
The links provide archived `.webarchive` copies.
* [Routes](https://drive.google.com/open?id=10_EjPSTjhbFNqMBkD5yBY6DoyDUsdwG5&usp=drive_fs)
* [Counter](https://drive.google.com/open?id=10umGF6JDTJ84Ug_KVcEOe1BleDGhWkOT&usp=drive_fs)
* [Stellar Burger](https://drive.google.com/open?id=10n-na5bfLlgLeitogRjxTYIV4F0WQ2DC&usp=drive_fs)

*The portfolio is expanded.*
