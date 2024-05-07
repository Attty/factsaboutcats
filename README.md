# FactsAboutCats

## Description:

FactsAboutCats is an application that provides users with interesting facts about cats presented in the form of cards. The main feature of this application is the ability to swipe through the cards, indicating whether you liked or disliked the facts.

## Key Features:

1. Display of Facts: The application fetches interesting facts about cats using an API.

2. Swipeable Cards: Each fact is presented in the form of a card that can be swiped.

3. Fact Rating: Users can indicate whether they liked a fact by swiping the card right (like) or left (dislike).

4. Local Storage of Liked Facts: Facts that the user liked are stored in a local database using Room.

5. View Liked Content: Users can view all the facts they liked by tapping on the heart icon in the top left corner of the screen.

## Technologies:

- Jetpack Compose is used for UI development.
- Retrofit is used for fetching data from a remote server.
- A local database is created using the Room library.

## Installation:

To run the application locally, follow these steps:

1. Clone this repository.
2. Open the project in Android Studio.
3. Build and run the application on an emulator or physical device.

## Usage:

Upon launching the application, users are presented with cards containing interesting facts about cats. They can swipe left or right to indicate whether they like or dislike a fact. Liked facts are saved locally and can be viewed by tapping on the heart icon.
