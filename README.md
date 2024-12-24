# How to Be Carried Gracefully In Video Games - Technical Documentation Page

## Project Overview

"How to Be Carried Gracefully" is a lighthearted technical documentation project built entirely with HTML and CSS. It offers a humorous, self-deprecating guide for gamers on how to embrace their role as the teammate being carried, all while keeping things fun and entertaining.

## Features

- **Static Documentation Page:**

  - Main content with technical documentation organized into clearly defined sections.
  - Smooth navigation through a sticky sidebar.

- **Responsive Design:**

  - The layout adapts to various screen sizes with the help of CSS media queries.

- **Humorous and Relatable Content:**
  - Fun, self-deprecating tips for gamers about recognizing their shortcomings, offering support, and avoiding sabotaging their team.

## Technologies Used

- **HTML:** Provides the structure of the page, including headers, paragraphs, lists, and links.
- **CSS:** Adds styling and layout, including:
  - Sidebar positioning and styling.
  - Main content formatting.
  - Responsive design using media queries.

## User Stories Fulfilled

1. A `main` element with id `main-doc` contains the page's main content.
2. Multiple `section` elements with class `main-section` exist within `main-doc`, each:
   - Starting with a header element describing the topic.
   - Having an id matching the header text, with spaces replaced by underscores.
3. At least 10 paragraphs, 5 code elements, and 5 list items are included across all `main-section` elements.
4. A `nav` element with id `navbar` contains:
   - A header introducing the documentation.
   - Navigation links (`a.nav-link`) for each `main-section`, linking to corresponding sections.
   - Links displayed on the left and always visible on larger screens.
5. Clicking a `nav-link` scrolls to the corresponding section in `main-doc`.
6. A CSS media query ensures responsiveness.

## File Structure
```
guide-to-being-carried-fcc/
├── index.html
├── styles.css
└── README.md
```
## Sections Included

1. **Recognizing When You're Being Carried**
   - Signs that you're not the MVP.
2. **Clear Comms: Words That Don’t Make You Sound Like a Clown**
   - Tips for effective communication.
3. **Cheerlead Without Being Annoying**
   - Encouragement tactics that don’t make your carry roll their eyes.
4. **Give Credit Without Sounding Sarcastic**
   - How to genuinely thank your carry.
5. **How to Not Be a Liability**
   - Avoiding common mistakes like feeding the enemy or rushing in recklessly.

## How to Run the Project

1. Clone or download the repository.
2. Open the `index.html` file in any modern web browser.
3. Enjoy the documentation and get ready to embrace your role as the team’s comedic relief!

## Acknowledgements

This project is a fun, creative exercise in HTML and CSS, inspired by gaming experiences and the humor found in being a less-than-perfect teammate.
