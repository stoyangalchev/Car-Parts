
# Car Part Ordering App

This is a JavaScript-based web app for submitting and confirming car part orders. Users can input car details and part information, review the data, and proceed with the order process. The app provides functionality to edit, continue, confirm, or cancel the order.

## Features

- **Form Submission**: Users can enter car model, year, part name, part number, and part condition.
- **Edit Entry**: After submitting, users can edit the entered information.
- **Order Process**: Users can proceed to confirm the part order or cancel it.
- **Order Confirmation**: A message and image appear once the order is confirmed.

## Installation

To run the app locally:

1. Clone the repository:

   ```bash
   git clone https://github.com/stoyangalchev/Car-Parts.git
   ```

2. Navigate to the project folder:

   ```bash
   cd car-part-ordering-app
   ```

3. Open `index.html` in your browser:

   ```bash
   open index.html
   ```

## Usage

1. Enter the car model, year (between 1980 and 2023), part name, part number, and condition.
2. Click the **Next** button to submit the part information.
3. Review the entered data:
   - **Edit**: Modify the details and resubmit.
   - **Continue**: Move to the confirmation step.
4. On the confirmation step:
   - **Confirm**: Finalize the order.
   - **Cancel**: Remove the part order.
5. Upon confirmation, a message "Part is Ordered!" will appear with a visible image.

## Code Structure

- **HTML**: The form elements and layout are found in `index.html`.
- **CSS**: Basic styling is in `styles.css`.
- **JavaScript**: All logic for the form handling, editing, and confirming orders is in `script.js`.

## Future Improvements

- Implement validation messages for users when entering incorrect year ranges.
- Add persistent storage (localStorage) to save part orders across sessions.
- Improve UI/UX with better styling and animations.

## Contributing

Feel free to contribute by submitting issues or pull requests. For major changes, please open an issue first to discuss the planned modifications.

## License

This project is licensed under the MIT License.

---

This README file provides an overview of the app's functionality and how to use it. Feel free to adjust any parts according to your actual project setup before uploading it to GitHub.