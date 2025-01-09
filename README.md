CST-210 Project April 2020 Sophmore year Comp Sci

**Description of the App**
The app is a role-playing game (RPG) where players can create and manage multiple characters, each with distinct attributes and progression. It employs object-oriented programming (OOP) principles to ensure modularity, reusability, and maintainability.

**Encapsulation:**
Data members like choice, playing, activeCharacter, and characters are private and accessed via public member functions, ensuring controlled interaction with the class.

**Abstraction:**
Complex operations like loading/saving characters, leveling up, or event handling are abstracted into dedicated methods (e.g., loadCharacters(), saveCharacters(), levelUpCharacter()).
Inheritance and Polymorphism (Potential but not visible in this snippet):
If the Character class supports subclasses for different character types (e.g., Warrior, Mage), polymorphism could be leveraged to extend functionality.

**Modularity:**
The Game class centralizes all game-related functionality, keeping it separate from other components like Character or Event, which likely exist in separate files.
This separation ensures that each class focuses on a single responsibility.

**Reusability:**
The Game class can be reused or extended for additional features like multiplayer support, more complex game mechanics, or new events.

Scalability:
The use of vectors (std::vector) to manage characters enables the system to handle a variable number of characters dynamically.
![finalFantasy](https://github.com/user-attachments/assets/33f51f4c-65a2-4365-9303-730ad0a39ac5)

