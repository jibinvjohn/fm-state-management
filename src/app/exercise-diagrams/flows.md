# Entity relationship

- Destinations
  - id
- Homes
  - id
  - destinationId
- User
  - Name
  - Id

# Sequence diagram

UI -> AirBnB search service: Find search results for this query (where, check in, checkout, and # of guests)
AirBnB search service -> UI: Results
UI -> UI: Select home
UI -> AirBnB API: Booking
AirBnB API -> UI: Payment information
UI -> Payment processor:

# State diagram

Start with destination
When the destination is input, put in the check in date, there are validations
Then put in the checkout datem there are validations
Then add the number of guests
And then when the user presses search, it'll take us to a search results page
The search results will be loading, and eventually show up
The user can click on one of the homes and be taken to a details page
They can go back from the details page back to the search page
