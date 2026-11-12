# User Manual – The Mindful Kitchen

This manual explains how to start and interact with the *The Mindful Kitchen* console application.

---

## 1. Starting the Application
1. Open your terminal or IDE (e.g., IntelliJ IDEA, Eclipse, or VS Code).
2. Compile and run `Main.java`.
3. Upon starting, the console will greet you and introduce a randomly selected customer along with a hint about their food preferences.

---

## 2. Navigating the Main Menu
The application is controlled via numbered commands in the console. Type the desired number and press **Enter**:

| Command | Action | Description |
| :--- | :--- | :--- |
| `1` | **View Cookbook** | Displays preparation methods (baked/boiled) and cooking times in minutes for ingredients. |
| `2` | **View Ingredients** | Lists the ingredients currently available in your kitchen inventory. |
| `3` | **Cook Dish (Prototype)** | Runs a basic test preparation and displays a sample satisfaction score. |
| `0` | **Exit Game** | Safely closes the console application. |

---

## 3. Input Rules & Error Handling
- Only enter the **numbers** listed in the menu (`0`, `1`, `2`, or `3`).
- If you accidentally type letters or invalid numbers, the program will display an error message and ask you to try again without crashing.