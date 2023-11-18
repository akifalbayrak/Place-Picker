# PlacePicker App

PlacePicker is a simple React application that allows users to create a personal collection of places they would like to visit or have visited. Users can select places from a list of available options, sorted by distance from their current location.

## Features

- **Pick Places:** Choose places from the list of available options to add to your personal collection.
- **Remove Places:** Remove selected places from your collection.
- **Geolocation Sorting:** Available places are sorted by distance based on the user's current location.

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/place-picker.git
   ```

2. Install dependencies:

   ```bash
   cd place-picker
   npm install
   ```

3. Run the application:

   ```bash
   npm start
   ```

   The app will be accessible at [http://localhost:3000](http://localhost:3000).

## Usage

- **Select Places:** In the "Available Places" section, click on the places you would like to visit. They will be added to the "I'd like to visit..." section.
- **Remove Places:** Click on a selected place in the "I'd like to visit..." section to initiate the removal process. Confirm the action in the displayed modal.

## Local Storage

The selected places are stored locally using the browser's `localStorage` API, allowing the user's collection to persist across sessions.


## Contributing

Feel free to contribute by submitting issues or pull requests. Bug reports, feature requests, and feedback are welcome!

---

Happy place picking! 🌍✨

![image](https://github.com/akifalbayrak/Place-Picker/assets/142679378/3b251082-5818-4a85-ad26-b4d3587187ff)
