# PawsAbode

Welcome to **PawsAbode**, a pet adoption platform dedicated to connecting homeless dogs with caring families. Our mission is to rescue, rehabilitate, and rehome dogs in need, ensuring every dog has a warm bed, a full belly, and a wagging tail.

## Table of Contents

[Features](#features)
[Installation](#installation)
[Usage](#usage)
[User Roles](#user-roles)
[Admin Functions](#admin-functions)
[User Functions](#user-functions)
[Contributing](#contributing)
[License](#license)

## Features

**User Authentication:** Secure login and registration for users and admins.
**Adoption Forms:** Users can fill out adoption forms to apply for adopting pets.
**Pet Listings:** Admins can list pets available for adoption, including details and photos.
**User Management:** Admins can view and manage user information.
**Responsive Design:** User-friendly interface optimized for all devices.

## Installation

To get a local copy up and running, follow these steps:

### Prerequisites

Python 3.x
Django 3.x
Other dependencies listed in requirements.txt

### Steps

1. Clone the repository:
   bash
    git clone https://github.com/yourusername/pawsabode.git
   
2. Navigate to the project directory:
   bash
    cd pawsabode
   
3. Create a virtual environment:
   bash
    python -m venv venv
   
4. Activate the virtual environment:
    - On Windows:
       bash
        venv\Scripts\activate
           - On MacOS/Linux:
       bash
        source venv/bin/activate
       
5. Install the dependencies:
   bash
    pip install -r requirements.txt
   
6. Apply migrations:
   bash
    python manage.py migrate
   
7. Create a superuser for admin access:
   bash
    python manage.py createsuperuser
   
8. Start the development server:
   bash
    python manage.py runserver
   
9. Open your web browser and go to http://127.0.0.1:8000.

## Usage

### User Roles

**Admin:**
  - Can list pets available for adoption.
  - Can view and manage user/customer information.
  - Perform all administrative actions.

**User:**
  - Can browse pet listings.
  - Can fill out adoption forms to apply for adopting pets.

### Admin Functions

1. **List Pets:**
   - Admins can add, edit, and delete pet listings.
   - Each listing includes details such as name, breed, age, description, and photos.

2. **View Customers:**
   - Admins can view and manage user information.
   - Admins can review adoption applications submitted by users.

### User Functions

1. **Fill Adoption Form:**
   - Users can fill out and submit adoption forms, providing details about their lifestyle, preferences, and expectations.

2. **Browse Pets:**
   - Users can view the list of available pets and their details.

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (git checkout -b feature/AmazingFeature)
3. Commit your Changes (git commit -m 'Add some AmazingFeature')
4. Push to the Branch (git push origin feature/AmazingFeature)
5. Open a Pull Request

## Team F
1. Srijan Adhikari
2. Alisha Shrestha
3. Karuna Tachamo
4. Prakriti Adhikari
5. Nischal Acharya

Made with ❤️ for pets in need.