# Gudang-Vokasi

Gudang-Vokasi is a web application designed to manage vocational warehouse inventories. It allows users to add, update, and delete inventory items, track item quantities, and generate reports.

## Features

- Add, update, and delete inventory items
- Track item quantities
- Generate inventory reports
- User authentication and authorization

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js and npm installed
- MongoDB installed and running
- Any modern web browser

## Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/FauzanTanzil/Gudang-Vokasi.git
    cd Gudang-Vokasi
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Set up environment variables:
    - Create a `.env` file in the root directory of the project and add the following variables:
        ```plaintext
        MONGO_URI=mongodb://localhost:27017/gudang-vokasi
        JWT_SECRET=your_jwt_secret
        ```

4. Run the application:
    ```bash
    npm start
    ```

5. Open your browser and navigate to `http://localhost:3000` to access the application.

## Usage

- Add new inventory items by navigating to the "Add Item" page.
- Update existing items by clicking on the item in the inventory list.
- Delete items from the inventory list.
- Generate reports by navigating to the "Reports" page.

## Directory Structure

- `src/` - Contains the main application code.
    - `controllers/` - Contains the controller functions.
    - `models/` - Contains the database models.
    - `routes/` - Contains the route definitions.
    - `views/` - Contains the view templates.
    - `middlewares/` - Contains the middleware functions.
- `public/` - Contains static assets like CSS, JavaScript, and images.
- `config/` - Contains configuration files.

## Contributing

If you wish to contribute, please fork the repository and make a pull request. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For more information, you can contact Fauzan Tanzil Habibi via [GitHub](https://github.com/FauzanTanzil).
