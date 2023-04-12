# Women's Networking App for Emergency Situations

# Project Description: Women's Networking App for Emergency Situations

This project aims to develop a mobile application that focuses on providing a networking platform for women, assisting them during emergency situations. The application will track the user's geolocation, enable communication between users, and provide a quick and efficient way to alert trusted contacts and security services during emergencies.

## Key Features

- Geolocation tracking in both online and offline mode
- Users can add each other as friends
- Sharing of geolocation data with other users who have the same app (with permission)
- Access to user's contacts and the ability to add trusted contacts
- Emergency button with various press and hold options for different actions
- Integration with Google Maps for displaying and tracking user's geolocation
- In-app purchases for unlocking additional features
- User profiles with personal information (first name, last name, nickname, phone number, email)

## Application Components

The application consists of the following main components:

1. Main Page: Contains a map (Google Maps), emergency button, menu button, profile button, and add contacts button.
2. Contacts Page: Features a search bar, trusted contacts header, list of contacts, separate list of added contacts, and a button to return to the main page.
3. Profile Page: Displays profile photo, user data (first name, last name, nickname, phone number, email), and a button to return to the main page.

This project is designed to be an MVP (Minimum Viable Product) for a hackathon, with plans to expand its features and functionality in the full version of the application.


## Technical Specifications

- The app must track geolocation in both online and offline mode with user permission
- The app requests user access to the following functions:
  - Access to contacts
  - Access to geolocation tracking
- Users can add each other as friends
- The app must share geolocation with other users with the same app with user permission
- The app requests user permission for contact data
- The user adds trusted contacts
- The app contains an emergency button

When pressing the emergency button:
  - Press and hold for 1 second:
    - Sends messages to trusted contacts
  - Press and hold for 3 seconds:
    - Activates alarm at maximum speaker volume
    - Activates audio recording and video recording
    - Activates the phone's rear flashlight at maximum power
  - Press and hold for 5 seconds or more:
    - Calls security services to the current geolocation
- The app contains a map (Google Maps) displaying the user's geolocation
- The map allows tracking other users' geolocation with their permission
- The app contains in-app purchases
- Purchasing a subscription unlocks the following features:
  - Main page contains a menu with a list of all pages
  - The app has a timer

The app contains a main page with: Map, Menu button, Emergency button, Profile button, Add contacts button

## App Components (Demo Version)

Main page content:
  - Emergency button
  - Google Maps
  - Button to navigate to the profile page
  - Button to navigate to the contacts addition page

Contacts page content:
  - Search bar
  - "Trusted Contacts" header
  - List of contacts
  - Separate list of already added contacts
  - Add / do not add icon next to each contact
  - Button to return to the main page

Profile page content:
  - Profile photo
  - Button to return to the main page
  - Data:
    - First name
    - Last name
    - Nickname
    - Phone number
    - Email
