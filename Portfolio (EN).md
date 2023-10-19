# Rostislav Cherepanov - portfolio

Below are links to files that demonstrate my skills in the appropriate app or area.

## Maintenance of documentation

### Checklist in Google Documents

[Link to the checklist in Google Docs](https://docs.google.com/spreadsheets/d/1Hc3tJqIDyNmxQdQZLAf-jmpPrXA9A9Y1yMejwQ/?usus=p=sharing)

Here I have compiled a list of tests for the project on testing the API of the educational application Yandex Counter.

To test the four endpoints in the Yandex Counter API, I made a checklist using test design techniques - equivalence classes and boundary values.
Due to project conditions there was little time for testing, so the format of test cases did not fit. And the use of EC and BV techniques allowed an optimal number of inspections.

### YouTrack

[Link to YouTrack](https://cherrost.youtrack.cloud/)

On the board are bug reports that I found during the execution of two projects. In one it was necessary to test part of functionality of API of educational application Yandex Counter, in the other - to automate test API of educational application Yandex Scooter.

### Miro

[Link to the board in Miro](https://miro.com/app/board/uXjVP5XSdL0=/moveToWidget=3458764566784593677&cot=14)

On the board is a diagram of connections, which I based on the analysis of requirements to the application Yandex Routes.

[Requirements](https://wiki.yandex.ru/homepage/trebovanija-k-jandeks.marshruty/) to Application Yandex Routes 1.0

### Test report

[Link to Test Report](https://docs.google.com/document/d/1kRWoBRF5qjsW6nF53rvZZ-kRVEpj43sh0DrqEonNxeditzI/?usp=)

This report was created as part of the project to test the API application Yandex Counter.

## SQL & Automation API

### Postman

[Reference to the workspace in Postman](https://ww.postman.com/orbital-module-astronomer707970/workspace/cher-rost-public)

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

*The portfolio is expanded.*
