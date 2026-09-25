## 📋 Project Assessment: Lab #8 - Loteria + Event Handling

### 1. Development & Workflow
- [ ] **Repository Setup:** Project cloned into IntelliJ and existing codebase verified (`LoteriaCard.java` model class reviewed, ensure “hello world” window pops up).
- [ ] **Commit Messages:** Descriptive and incremental commits tracking layout build and event handling milestones.

### 2. Functional Requirements

#### Front-End Layout & Styling
- [ ] **Scene Setup:** Window initialized to appropriate dimensions (about `350x500`).
- [ ] **Component Hierarchy:** Components organized cleanly within a `VBox` layout matching the wireframe:
    - [ ] `titleLabel` (Styled with custom fonts, colors, and centered alignment).
    - [ ] `cardImageView` (Configured to render `Image` objects from `LoteriaCard.getImage()`).
    - [ ] `messageLabel` (Positioned to provide feedback to the player).
    - [ ] `drawCardButton` (Styled button placed beneath message output).
- [ ] **UI/UX Polish:** Visual layout matches sample working screenshots (appropriate padding, colors, font sizes, and alignments).

#### Event Handling & Logic
- [ ] **Anonymous Inner Class:** Event handler for `drawCardButton` explicitly implemented using an **anonymous class** syntax (e.g., `new EventHandler<ActionEvent>()`).
- [ ] **Card Selection Logic:** Button click dynamically retrieves and displays a `LoteriaCard` image in `cardImageView`.

### 3. Code Quality & Standards
- [ ] **Event Handler Style:** Verified strict use of anonymous inner classes for button event handling.
- [ ] **Model Preservation:** Left `LoteriaCard.java` unmodified as instructed.
- [ ] **Naming Conventions:** `camelCase` for JavaFX variables/methods; `PascalCase` for classes.
- [ ] **Formatting:** Clean, well-indented layout and event handling code.

### 4. Hacker Challenge (Optional)
- [ ] **Non-Repeating Card Deck:** Implemented deck drawing logic using arrays so cards do not repeat.
- [ ] **ProgressBar Integration:** Added `gameProgressBar` displaying dynamic progress bounded between `0.0` and `1.0`.
- [ ] **Game Over State:** When all cards are drawn:
    - [ ] `messageLabel` updates to `"GAME OVER. No more cards! Exit and run program again to reset ^_^"`.
    - [ ] `cardImageView` displays the EChALE logo.
    - [ ] `drawCardButton` is disabled (`setDisable(true)`).
    - [ ] `gameProgressBar` turns red via JavaFX styling/CSS.
