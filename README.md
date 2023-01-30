# meet3 

meet3 is an app that will show upcoming events by city so a user will never miss out on a concert.

Key Features: It must be able to filter events by city. It must be able to show/hide an event's details. It must specify the number of events. It must be available offline. It must add an app shortcut to the user’s home screen. It must display a chart showing the number of upcoming events by city.

Feature 1: Filter Events by City User story: As a user, I should be able to filter events by city So that I can see the list of events that take place in that city. Scenario 1: Given user hasn’t searched for any city
When the user opens the app Then the user should see a list of all upcoming events Scenario 2: Given the main page is open When user starts typing in the city textbox Then the user should see a list of cities (suggestions) that match what they’ve typed Scenario 3: User can select a city from the suggested list. Given the user was typing “Berlin” in the city textbox And the list of suggested cities is showing When the user selects a city (e.g., “Berlin, Germany”) from the list Then their city should be changed to that city (i.e., “Berlin, Germany”) And the user should receive a list of upcoming events in that city

Feature 2: Show/Hide an Event's Details User Story : As a user, I should be able to view and hide an event's details So that I can get more information when needed and hide it when not needed. Scenario 1: Given an event element is collapsed by default When the user expands an event Then the user should be able to see the event's details Scenario Scenario 2: Given an event is open When the user collapses an event Then the user should not be able to see the event's details Feature 3: Specify Number of Events

User Story : As a user, I should be able to specify the number of events I want to see So that I can customize my experience. Scenario 1: Given the user has not specified a number When the user loads the page Then 32 events should be the default number of events Scenario Scenario 2: Given the user is on the page When the user changes the number of events they want to see Then the page should update to reflect the new number of events. Feature 4: Use the App When Offline

User Story : As a user, I should be able to use the app while offline So that I can access it regardless of my internet connection. Scenario 1: Given the user is offline
When the user attempts to access the app Then the user should be able to see cached data Scenario 2: Given the user is offline When the user attempts to change the settings (city, time range) Then the user should see an error.

Feature 5: Data Visualization User Story : As a user, I should be able to visualize data So that I can better understand the upcoming events. Scenario 1: Given the user is on the page When the user loads the page Then the page should show a chart with the number of upcoming events in each city.
