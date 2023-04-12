# Women's Networking App for Emergency Situations

Highlighted in yellow - Technical specifications required for MVP at hackathon
Not highlighted in yellow - Technical specifications for the full version of the app

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
