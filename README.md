# creditcardmanagement


# Implementation plan

## Milestone 1

#### Data
- a list of credit card cash back information
- a list of supported cash back categories
- different types of cash back (rotating calendar, flat cash back, specific categories cash back etc.)
- 5% cash back rotating calendar

##### data decisions
Store data as local JSON files for simplicity.
Use fetch to mock API call https://app.pluralsight.com/guides/fetch-data-from-a-json-file-in-a-react-app


#### Functionality
- A dashboard that shows for each category, which card has max cash back

##### functionality decisions
Display the dashboard in a table manner so we can support filtering and sorting in the future.
Find a react table that's easy to do row card customization on.