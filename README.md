# Property Management Application
This is a property management application built using CakePHP that allows users to manage and view properties

##Features
- **Add Property**: Add new properties with details such as address, bedrooms, baths, price, and a upload a photo
- **Property Information**: View properties and details for each property
- **Search Functionality**: Easily search for properties

##Installation
1. Clone the repository to your local machine.
2. Install dependencies using Composer.
   ```bash
   composer install
Configure your database settings in config/app.php.
Run database migrations to set up the required tables.
    ```bash
    
    bin/cake migrations migrate
    
Start the CakePHP development server.
    ```bash
    
    bin/cake server
Access the application in your browser at http://localhost
