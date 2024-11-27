# survey-form-project
A survey form for freeCodeCamp It includes input validation and a user-friendly layout with checkboxes, radio buttons, and a text area for additional information.
## Survey Form Overview


This **survey form** is designed to gather information for a restaurant reservation. It includes the following key features:

- **Title and Description**: The page starts with a title (`h1` with `id="title"`) and a brief description (`p` with `id="description"`).
- **Input Fields**: 
  - **Name**: A text input field (`id="name"`) with a placeholder and required validation.
  - **Email**: An email input field (`id="email"`) that triggers HTML5 validation for correct email format.
  - **Guests**: A number input field (`id="number"`) with a range set by the `min` and `max` attributes.
- **Select Dropdown**: A dropdown (`id="dropdown"`) for seating preference with multiple options.
- **Checkboxes**: Multiple checkboxes allow users to select items like drinks, desserts, and the chef's menu.
- **Radio Buttons**: A pair of radio buttons asks whether the user has any food allergies, with a corresponding text area for additional details (`id="about-allergies"`).
- **Submit Button**: A submit button (`id="submit"`) to send the form data.

### CSS Styling

- **Responsive Design**: The form is centered with a flexible width (`max-width: 500px`), ensuring it adapts well to different screen sizes.
- **Form Layout**: `fieldset` elements group form fields, with padding for readability and styling. The last `fieldset` has no border to separate it from the submit button.
- **Input Styling**: Inputs, select dropdowns, and text areas have a soft background color (`#f6f3ec`), rounded corners, and full width to enhance user experience.
- **Checkbox Group**: The checkboxes are laid out using `flex` to space them evenly, ensuring an organized display.
- **Submit Button**: The submit button is styled to match the form's design, centered, and easy to click.

This layout provides a clean, user-friendly experience while collecting detailed reservation information.
