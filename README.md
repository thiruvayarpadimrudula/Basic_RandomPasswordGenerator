# Random Password Generator

## Description
This project is a simple **Random Password Generator** built using **HTML**, **CSS**, and **JavaScript**. The application generates a secure and random password of a fixed length (12 characters by default) consisting of uppercase letters, lowercase letters, numbers, and special symbols. Users can copy the generated password with a single click.

---

## Features
1. **Random Password Generation**: Ensures each password includes at least one character from each category: uppercase, lowercase, number, and symbol.
2. **Copy to Clipboard**: Copy the generated password to the clipboard with a simple click on the copy icon.
3. **Responsive Design**: Works well on devices of all sizes.
4. **Simple User Interface**: Clean and easy-to-use interface.

---

## File Structure
```
RandomPasswordGenerator/
├── index.html      # Main HTML file for the structure
├── style.css       # CSS file for styling
├── script.js       # JavaScript file for password generation and interactivity
├── copy.png        # Icon for the copy button
```

---

## Installation and Setup
1. Clone the repository or download the project folder.
2. Place all files (`index.html`, `style.css`, `script.js`, and `copy.png`) in the same directory.
3. Open the `index.html` file in any modern web browser to use the application.

---

## Usage
1. Open the application in a browser.
2. Click the **"Generate"** button to create a random password.
3. The generated password will appear in the input field.
4. Click the **copy icon** to copy the password to the clipboard.

---

## Code Overview

### 1. **HTML (`index.html`)**
- **Head Section**: Includes links to CSS and JavaScript files.
- **Body Section**: Contains the main UI elements:
  - A heading for the app title.
  - A display area with:
    - An input box for showing the generated password.
    - A copy icon to trigger the copy functionality.
  - A "Generate" button to trigger the password generation function.

### 2. **CSS (`style.css`)**
- Provides a clean, responsive design with a dark-themed background.
- Styled elements:
  - Input fields and buttons.
  - Colors for a professional look.

### 3. **JavaScript (`script.js`)**
- **Variables**:
  - `passwordbox`: Represents the password display input.
  - `length`: The fixed length of the password (default is 12).
  - `uppercase`, `lowercase`, `number`, `symbol`: Strings containing the respective character sets.
  - `allchars`: Combination of all character sets.
- **Functions**:
  - `createpassword()`: Generates a random password:
    - Ensures at least one character from each category.
    - Fills the remaining length with random characters from all categories.
  - `copypassword()`: Copies the generated password to the clipboard using `document.execCommand`.

---

## Browser Compatibility
The application is compatible with:
- **Google Chrome**
- **Mozilla Firefox**
- **Microsoft Edge**
- **Safari**

---
