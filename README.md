# Hello Candidate

We are happy that’s you reach this point
We just need to test your programming skills, so this is a small task to make with react

# Your task is to:

1 - Handle user authentication:

- Create login form having the following fields
  - Email or phone number (user can choose the country code).
  - Password.
- Create auth service that handles
  - Logging in and out.
  - Getting current user.

2 - Handle user authorization.

- All routes should be protected (redirect to login page if not authenticated)
- Redirect to route after login.

3 - Create a form to submit a new address to the backend using RestAPI
The form must have the following fields :

- Name (String)
- Address (String)
- Apartment no. (integer)
- Floor no. (integer)
- City (Selection field – you will retrieve the data from backend API)(User can filter the list by typing city name).
- Longitude (decimal) (manually or auto filled)
- Latitude (decimal) (manually or auto filled)

Integrate the app with google maps iframe to get longitude & latitude

- Default location is current location.
- User can drag and drop to choose another location
- Above fields should be updated by dragging a new location.

4 - Create a list to display the addresses from the backend

- Use the fetched coordinates to generate a link to view the location on google maps.

5 - Users can edit the address
6 - Users can delete the address
7 - Use React-hook-form for the Form control (create a re-usable form component).
8 - Use yup for form validation
9 - Use Material-UI for Styling

# Notes :

Please use apisauce to handle API calls ( create API middleware to handle displaying data or displaying errors if exist).

Use hooks (react functional components).

# Backend Repository

https://github.com/YDS-Devs/InterviewAddressBE
