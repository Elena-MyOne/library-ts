# Library

## Overview

Library JS is a responsive and interactive web application for managing a digital book library. It
features an adaptive layout, semantic HTML, and pixel-perfect design based on the
[Figma template](https://www.figma.com/design/SGY7eOpXC1xBddFNsb72o7/%D0%91%D0%B8%D0%B1%D0%BB%D0%B8%D0%BE%D1%82%D0%B5%D0%BA%D0%B0-stage0?node-id=0-1&p=f).&#x20;

## Features

- **Adaptive Layout** – Optimized for 1440px, 768px, and 380px screen sizes.
- **Pixel-Perfect Design** – Matches the provided Figma template.
- **Semantic HTML** – Ensures accessibility and proper document structure.
- **Book Management** – Add, edit, delete, and categorize books.
- **Search & Filters** – Find books by title, author, or category.
- **Pagination** – Browse books efficiently with paginated results.
- **Local Storage Support** – Saves library data between sessions.

## Technologies Used

- **HTML** – Structured and semantic document markup.
- **CSS (Flexbox & Grid)** – Responsive and visually appealing layout.
- **JavaScript (ES6)** – Handles interactivity and data management.
- **Local Storage API** – Persists data between sessions.

## Installation & Usage

1. Clone the repository:
   ```sh
   git clone https://github.com/Elena-MyOne/library-ts.git
   ```
2. Navigate to the project directory:
   ```sh
   cd library-ts
   ```
3. Open `index.html` in a web browser.

## How to Use

- Add new books with title, author, and category.
- Edit or delete books from the library.
- Use the search bar to find books quickly.
- Apply filters to organize the library.
- Navigate through the book collection using pagination.
- Switch between light and dark modes.

## Future Enhancements

- User authentication for personalized book collections.
- Integration with external book APIs for extended metadata.
- Drag-and-drop book organization.

## Functionality

#### 1. When the user is not registered.

- A slider-like carousel in the About block with a fixed start and end: On a large screen, 3
  transitions will be available. When you click on the button, one picture will smoothly replace
  another (a cast. The transition from the far left state to the far right occurs only by scrolling
  through all the elements in the middle, and in the opposite direction. The same applies to the
  width of the screens for tablets, only now there will be 5 buttons. And in the extreme positions,
  the arrows of the corresponding side will become inactive.

- A "slider" in the form of dimming/appearing (fade in / fade out) in the Favorites block: all 4
  cards with books will smoothly fade out, and then the next ones will smoothly appear. The
  animation can be interrupted by the next click on the season selection button. It is also possible
  to implement this item with tabs.

#### 2. When user at the registration stage

- Clicking the Register or Sign Up button opens a modal registration window. After registration, the
  user's user icon will change to capital letters of the name. All data (including the password!) is
  saved in localStorage.

- In the Digital Library Cards section, checking the user's card will become available. If the
  entered name and card number match the user's data, a panel with information is displayed instead
  of the check the card button for 10 seconds. After which the button returns to its previous state.

#### 3. When user at the stage of logging into an account after registration

- Clicking on the Log In or Buy button opens a modal authorization window. After this, manipulations
  with the profile will become available, and each authorization will affect the visit counter.

#### 4. When user after logging into account

- Profile window is available, the ability to purchase a subscription, displaying information in
  Digital Library Cards.

## License

This project is licensed under the MIT License.
