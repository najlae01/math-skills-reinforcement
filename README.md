# Math Reinforcement Mini-Games

## Overview
Welcome to **Math Reinforcement Mini Games**, an engaging suite of mini-games designed to reinforce key math skills through fun, interactive gameplay. This README provides an overview of the project, development setup, and contribution guidelines. These mini-games aim to enhance mathematical learning by integrating educational concepts with immersive game mechanics. The mini-games cover a wide range of math topics, including arithmetic, geometry, logical reasoning, fractions, and quick calculations.

## Table of Contents
1. [Market Math](#market-math)
2. [Shape Builder](#shape-builder)
3. [Delivery Dash](#delivery-dash)
4. [Restaurant Rush](#restaurant-rush)
5. [Math Hoops](#math-hoops)
6. [System Components](#system-components)
7. [Installation Instructions](#installation-instructions)
8. [Teacher Dashboard Integration](#teacher-dashboard-integration)
9. [Contributing](#contributing)
10. [Contact](#contact)

---

## Market Math

![Scene Reference Image](Market.png)

### **Marketplace - 💰 Money Management**
**🕹️ Gameplay Mechanics**: 
- 🎯 **Goal**: Sell items, calculating totals, change, and discounts.
- 🛒 **Scenarios**: Act as a shopkeeper with interactive shopping tasks.

**🌍 World Setting & NPCs**:
- 📍 **Location**: Busy marketplace with stalls (vegetables, bakery, clothing).
- 👥 **NPCs**: Shopkeepers and customers requesting purchases.

**🎥 Camera Perspective & Movement**:
- 👁️ **Perspective**: Third-person, slightly above the player.
- 🎯 **Movement**: Follows the player smoothly, slight lag for a dynamic feel.

**🕹️ Player Controls & Actions**:
- 🚶‍♂️ **Movement**: Joystick (mobile) / WASD (PC).
- 🤝 **Interact**: Tap/click to speak with NPCs.
- 🔢 **UI**: Select or type numerical answers.

**🎁 Rewards System**:
- ✅ **Correct answers**:  Coins, XP (GameLevel).
- ⚡ **Fast, accurate responses**: Bonus Gems.

**🛠️ Unreal Engine Development Directives**:
- 🗝️ **Key Systems**:
   - 💬 **Dialogue System**: Integrated with random math problem prompts either calculating totals, change, or discounts.
   - 📦 **Inventory System**: Simple buying/selling mechanics.
   - 💰 **Currency System**: Track Coins/Gems.
- 🖼️ **UI Components**: Numeric keypad, answer submission panel.
- 🎬**Animation**: Idle animations, interactive triggers.

**🐈‍⬛ GitHub Branch**: `market`

---

## Shape Builder

![Scene Reference Image](Mechanic.png)

### **Mechanic - 📏 Geometry Puzzle**
**🕹️ Gameplay Mechanics**: 
- 🎯 **Goal**: Construct shapes from pieces or match objects to geometric forms.
- 🛒 **Scenarios**: Drag-and-drop puzzles, object matching.

**🌍 World Setting & NPCs**:
- 📍 **Location**: mechanic shop (machine parts).
- 👥 **NPCs**: mechanic providing shape tasks.

**🎥 Camera Perspective & Movement**:
- 👁️ **Perspective**: Top-down or isometric for clear puzzle visibility.
- 🎯 **Movement**: Locked position, slight zoom in/out with player actions.

**🕹️ Player Controls & Actions**:
- ✋ Drag and drop shapes.
- 🔄 Rotate pieces as needed.
- ✅ Confirm completed puzzles.

**🎁 Rewards System**:
- 🎯 **Completed puzzles**:  Coins, XP (GameLevel).
- ⚡ **Quick, precise solutions**: Bonus Gems.

**🛠️ Unreal Engine Development Directives**:
- 🗝️ **Key Systems**:
   - 🎯 **Drag-and-Drop System**: Physics-enabled for smooth interactions.
   - 🧠 **Puzzle Validator**: Check correct shape formation.
- 🖼️ **UI Components**: Shape inventory panel, rotation buttons.
- 🎬**Animation**: Snap-to-place effects for satisfying completion.

**🐈‍⬛ GitHub Branch**: `builder`

---

## Delivery Dash

### **Police Station / Hospital - 🚚 Logical Sequences**
**🕹️ Gameplay Mechanics**: 
- 🎯 **Goal**: Deliver packages to correct locations using math-based clues.
- 🛒 **Scenarios**: Decode clues, navigate city, confirm deliveries.

**🌍 World Setting & NPCs**:
- 📍 **Location**: Low-poly 3D city with key landmarks.
- 👥 **NPCs**: Post officer or doctor assigning deliveries.

**🎥 Camera Perspective & Movement**:
- 👁️ **Perspective**: Third-person driving view.
- 🎯 **Movement**: Follows vehicle dynamically, slight tilt during turns.

**🕹️ Player Controls & Actions**:
- 🚗 Drive with joystick (mobile) / arrow keys (PC).
- 🗺️ Select locations on mini-map.
- ✅ Confirm deliveries at destinations.

**🎁 Rewards System**:
- 📦 **Correct deliveries**:  Coins, XP (GameLevel).
- ⚡ **Fast, accurate routes**: Bonus Gems.

**🛠️ Unreal Engine Development Directives**:
- 🗝️ **Key Systems**:
   - 🗺️ **Mini-Map System**: Real-time tracking of player and objectives.
   - 🚗 **Vehicle Controller**: Smooth physics-based driving mechanics.
   - 🧩 **Clue Logic System**: Dynamic math problem generation for clues.
- 🖼️ **UI Components**: Interactive mini-map, delivery checklist.
- 🌍 **World Design**: Optimized city layout for fun navigation.

**🐈‍⬛ GitHub Branch**: `delivery`

---

## Restaurant Rush

![Restaurant Scene Reference Image](Restaurant.png)
![Coffee Scene Reference Image](Coffee.png)

### **Restaurant / Coffee Shop - 🍕 Fractions & Decimals**
**🕹️ Gameplay Mechanics**: 
- 🎯 **Goal**: Prepare and serve food based on fraction-based recipes.
- 🛒 **Scenarios**: Measure ingredients, serve customers quickly.

**🌍 World Setting & NPCs**:
- 📍 **Location**: Cozy restaurant or bustling coffee shop.
- 👥 **NPCs**: Customers with specific food orders, chef giving instructions.

**🎥 Camera Perspective & Movement**:
- 👁️ **Perspective**: Third-person, slightly above kitchen view.
- 🎯 **Movement**: Semi-locked with slight pan to follow player within kitchen.

**🕹️ Player Controls & Actions**:
- 🍳 Select ingredients.
- ✂️ Drag to pour/cut portions.
- ✅ Serve dishes before customer patience runs out.

**🎁 Rewards System**:
- 📦 **Accurate servings**:  Coins, XP (GameLevel).
- ⚡ **Fast service**: Bonus Gems.

**🛠️ Unreal Engine Development Directives**:
- 🗝️ **Key Systems**:
   - 🥗 **Ingredient System**: Interactive objects with quantity tracking.
   - ⏱️ **Customer Patience Timer**: Affects rewards based on service speed.
   - 📏 **Recipe Validator**: C++ logic to check correct portions.
- 🖼️ **UI Components**: Recipe book, fraction sliders.
- 🎬**Animation**: Pouring effects, cooking animations.

**🐈‍⬛ GitHub Branch**: `restaurant`

---

## Math Hoops

### **Basketball Court - 🏀 Quick Calculations**
**🕹️ Gameplay Mechanics**: 
- 🎯 **Goal**: Score baskets by solving quick math problems correctly.
- 🛒 **Scenarios**: Each successful answer gives the player a chance to shoot. The difficulty of the problem and shot increases as the player progresses.

**🌍 World Setting & NPCs**:
- 📍 **Location**: A lively basketball court with cheering NPCs.
- 👥 **NPCs**: Teammates and a coach giving math challenges. Opponents may appear in higher levels to add pressure.

**🎥 Camera Perspective & Movement**:
- 👁️ **Perspective**: Third-person, positioned slightly behind and above the player during shooting. Dynamic follow when moving around the court.
- 🎯 **Movement**: Follows the player with smooth transitions between solving problems and taking shots.

**🕹️ Player Controls & Actions**:
- 🤔 Solve math problems via multiple-choice or quick input.
- 🏃 Move with joystick (mobile) / WASD (PC).
- 🎯 Aim and shoot with a swipe (mobile) or mouse click/drag (PC).

**🎁 Rewards System**:
- ✅ **Correct answers and successful shots**:  Coins, XP (GameLevel).
- ⚡ **Streaks of correct answers**:  Bonus Gems and power-ups (like speed boost or accuracy aid).

**🛠️ Unreal Engine Development Directives**:
- 🗝️ **Key Systems**:
   - 🔢 **Quick Math Problem Generator**: Generates rapid-fire math questions tailored to player grade level.
   - 🏀 **Basketball Shooting Mechanic**: Physics-based system for aiming and shooting.
   - 🔥 **Combo System**: Rewards streaks with visual effects and bonus points
- 🖼️ **UI Components**: Timer bar, score tracker, quick answer buttons.
- 🎬**Animation**: Dribbling, shooting, celebratory animations after successful shots.

**🐈‍⬛ GitHub Branch**: `hoops`

---

## System Components

### ⚙️ **Existing Classes & Structures**

![Class Diagram](class-diagram.png)

- **`ANPC`**: Base class for non-playable characters (NPCs) that guide players.
- **`UMathoriaGameInstance`, `UMathoriaPlayerProfile`, `AMathoriaPlayerState`**: Core player data and game management.
- **`UMathoriaGameInstance`**: Manages overall game state, player data, and progression.
- **`UMathoriaPlayerProfile`**: Stores player-specific data such as player name, XP,  achievements, levels, and preferences.
- **`AMathoriaPlayerState`**: Tracks current player profile and session data.

For a detailed explanation of the class structure, please refer to the diagram above.

### ⚙️ **Insights and Hints about Classes and Structures Needed**

#### 🧠 **NPC & Interaction System**
- **`ANPC`** *(Base Class)*: Manages basic NPC behavior, dialogue, and interaction triggers, and is extended into specific NPC types for each mini-game.
- **`UDialogueComponent`**: Handles dialogues and interactions between the player and NPCs.
- **NPC Child Classes**:
   **1. `AMarketNPC` (Market Math Mini-Game)**
   - **Role**: Represents shopkeepers and customers in the marketplace.
   - **Attributes**:
   - `ShopType`: The type of shop (e.g. bakery, clothing store).
   - `CustomerRequest`: The math problem or purchase request the customer presents.
   - **Methods**:
   - `GeneratePurchaseRequest()`: Generates a math problem (e.g., total cost, change, or discount).
   - `ProvideFeedback()`: Gives feedback to the player based on their response (correct/incorrect).

   **2. `AMechanicNPC` (Shape Builder Mini-Game)**
   - **Role**: Represents the mechanic who provides shape-building tasks.
   - **Attributes**:
   - `ShapeType`: The type of shape the player needs to build (e.g., triangle, square, circle).
   - `PuzzleDifficulty`: The difficulty level of the shape puzzle.
   - **Methods**:
   - `ProvideShapeTask()`: Gives the player a shape-building task.
   - `ValidateShape()`: Checks if the player has correctly built the shape.

   **3. `APostOfficerNPC` (Delivery Dash Mini-Game)**
   - **Role**: Represents the post officer or doctor who assigns delivery tasks.
   - **Attributes**:
   - `DeliveryLocation`: The destination for the delivery.
   - `Clue`: The math-based clue the player must solve to find the delivery location.
   - **Methods**:
   - `AssignDeliveryTask()`: Assigns a delivery task with a math-based clue.
   - `ConfirmDelivery()`: Validates if the player has delivered to the correct location.

   **4. `AChefNPC` (Restaurant Rush Mini-Game)**
   - **Role**: Represents the chef or customer who provides cooking tasks.
   - **Attributes**:
   - `Recipe`: The fraction-based recipe the player must follow.
   - `PatienceTimer`: The time limit for completing the task.
   - **Methods**:
   - `ProvideRecipe()`: Gives the player a fraction-based recipe to follow.
   - `ValidateDish()`: Checks if the player has prepared the dish correctly.

   **5. `ACoachNPC` (Math Hoops Mini-Game)**
   - **Role**: Represents the coach or teammate who provides quick math challenges.
   - **Attributes**:
   - `MathProblem`: The quick math problem the player must solve.
   - `DifficultyLevel`: The difficulty of the math problem (increases as the player progresses).
   - **Methods**:
   - `GenerateMathProblem()`: Generates a quick math problem for the player to solve.
   - `ProvideShootingOpportunity()`: Allows the player to shoot a basket if they solve the problem correctly.

#### 🗺️ **World & Environment Management**
- **`AMiniGameMap`**: Defines unique environments for each mini-game (Market, Garden, City, etc.).
- **`UObjectSpawner`**: Dynamically spawns items, puzzles, or NPCs based on game scenarios.
- **`ULocationManager`**: Manages different in-game locations and transitions between them.

#### 📊 **Math Problem Generation & Validation**
- **`UMathProblemGenerator`**: Generates math problems tailored to math skill level.
- **`UMathValidator`**: Validates player answers and triggers corresponding feedback mechanisms.
- **`UAdaptiveDifficultySystem`**: Adjusts the difficulty of problems based on player performance.

#### 🕹️ **Mini-Game Controllers**
- **`AMarketMathController`**: Handles logic for the Market Math mini-game, including transactions and currency management.
- **`AShapeBuilderController`**: Manages shape construction mechanics and puzzle validation.
- **`ADeliveryDashController`**: Controls delivery missions, vehicle navigation, and clue decoding.
- **`ARestaurantRushController`**: Oversees cooking mechanics, ingredient measurements, and order validation.
- **`AMathHoopsController`**: Manages quick calculation challenges, shooting mechanics, and combo scoring.

#### 🏆 **Rewards & Progression Systems**
- **`URewardSystem`**: Distributes rewards such as coins, XP, and gems based on performance.
- **`UComboSystem`**: Encourages streaks of correct answers, offering bonus points and power-ups (Math Hoops mini-game).

#### 📈 **Analytics & Learning Insights**
- **`UAnalyticsManager`**: Collects gameplay data for performance analysis.
- **`ULearningProgressTracker`**: Monitors educational progress, highlighting strengths and areas for improvement.
- **`UTeacherDashboardAPI`**: Facilitates data synchronization with the Teacher Dashboard for real-time performance tracking.

#### 📱 **User Interface Components**
- **`WBP_HUDManager`**: Manages in-game UI elements like scoreboards, timers, and progress bars.
- **`WBP_NPC_Dialogue`**: Displays interactive dialogues with NPCs.
- **`WBP_MiniGame`**: Tailored UI layouts for each mini-game, including answer panels, inventory, and mini-maps.

---


## Teacher Dashboard Integration

- **Real-Time Monitoring of Student Performance**: Track student performance in real-time while they are engaging with the mini-games.
- **Analytics & Reports**: Teachers have access to detailed analytics, showing student progress, areas of strength, and areas for improvement. Reports can be generated based on student performance, helping educators adjust teaching strategies as needed.
- **Link to GitHub Repo**: [GitHub Repository for Teacher Dashboard](https://github.com/najlae01/math-web.git)

---

## Installation Instructions

1. Clone or download the project files from the repository.

2. **Create a Firebase Console Account:**
   - Go to [Firebase Console](https://console.firebase.google.com/).
   - Create a new project named "Math Reinforcement Game."

3. **Add Android and Web Apps:**
   - In your Firebase project settings, add an Android app and a Web app.

4. **Enable Authentication:**
   - Go to "Authentication" and enable Email and Google sign-in methods.

5. **Configure Realtime Database:**
   - Enable "Realtime Database" and set up the rules as needed.

6. **Download Configuration File:**
   - In "Project Settings" under Android apps, download the `google-services.json` file.
   - Add your Developer SHA Certificate Fingerprints for Android.

7. **Organize Project Files:**
   - Create a `Services` folder in the project directory and place `google-services.json` inside.
   - Create a `Plugins` folder and add the shared Firebase plugin there.

8. **Build the Project:**
   - Right-click the `.uproject` file.
   - Choose "Show more options" > "Generate Visual Studio Project files."
   - Open the `.sln` file in Visual Studio and build the project.

9. **Run the Game:**
   - After a successful build, open the `.uproject` file and run the game.

---

## Contributing

We welcome contributions to improve these mini-games!

1. Fork the repository.
2. Create your group branch (`git checkout -b group-one`).
3. Commit your changes (`git commit -am 'Add group-one'`).
4. Push to your branch (`git push origin group-one`).
5. Open a pull request with detailed descriptions of your changes.

---

## Contact

For support, contact [Najlae](mailto:najlae.abarghache@etu.uae.ac.ma).

The updated **System Components** section now includes detailed descriptions of the **NPC child classes** and their roles in each mini-game. This addition enhances the clarity of the system architecture and provides developers with a clear understanding of how NPCs will function within the **Math Reinforcement Mini-Games**. Below is a refined version of the section with some minor adjustments for consistency and readability:

---