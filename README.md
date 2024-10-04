Code Description
Directory Structure:

assets/: Contains image files used in the application.
lib/: Main directory for the application code, including data/, pages/, and main.dart.
data/: Contains property.dart, which defines the Property class that holds information about each property.
pages/: Contains three Dart files:
home.dart: Displays a list of properties.
description.dart: Shows details about a selected property.
property_info.dart: Provides additional information about the property.
Main Function (main.dart):

Initializes the Flutter application by running the MaterialApp widget with Home as the home screen.
Property Class (data/property.dart):

Defines a class Property with four fields: name, image, price, and description. This class is used to create property objects for the app.
Home Screen (pages/home.dart):

Contains a StatefulWidget that displays a list of properties using a ListView.builder.
Each property is represented by a Card with an image, name, and price, and tapping on a property navigates to its description.
Description Screen (pages/description.dart):

Displays detailed information about a selected property, including its image, name, description, and price.
Includes a button that navigates to the Property_info screen for further details.
Property Info Screen (pages/property_info.dart):

Provides additional information about the selected property, including its features and a contact message.
User Interface:

Uses Flutter's built-in widgets such as Scaffold, AppBar, ListTile, and Card to create a visually appealing layout.
Centers the text and images for better alignment and aesthetics.
