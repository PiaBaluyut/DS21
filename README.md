# Setup guide (README)

**Prerequisites**

- A computer with a supported Java Development Kit (JDK).
- Apache NetBeans or another Java IDE.
- The project source files in the package com.mycompany.finals.
- The pet image resources, if the image display feature is to be used.

**Build and Run**

- Open the Tamagotchi project in Apache NetBeans.
- Confirm that the package declaration in all three files is com.mycompany.finals.
- Confirm that FINALS.java, Game.java, Creature.java, DatabaseConnection.java, and BackgroundPanel.java are in the matching package folder.
- Place the pet/expression images and background image in the resources/images folder using the exact filenames expected by the code.
- Clean and Build the project in NetBeans.
- Run FINALS.java (the class containing public static void main).
- Choose a species, enter a name, and test the Play, Eat, Sleep, and Quit buttons.

# User guide

- Launch the application.
- A message will appear asking you to choose a pet species such as Cat, Dog, or Fox.
- Enter your desired pet name.
- If the name is left blank, the program automatically assigns the name Pawgotchi.
- The system checks whether a pet with the entered name already exists. If there's already an existing name, its saved information will be loaded otherwise, a new pet will be created.
- Once the pet is loaded or created, the main game window will appear, displaying the pet's name, species, and current Hunger, Happiness, and Energy levels. Each stat starts at 15 for a newly created pet and updates whenever the user performs an action.
