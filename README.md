# Superheroes
# Overview
The Hero Power Management System is a web application that allows users to manage superheroes and their associated powers. This application utilizes SQLAlchemy for database management and Flask for the web framework. It provides functionalities to create, retrieve, update, and delete heroes and powers, as well as their associations through a join table.

## Table of Contents
.Hero Management
.Power Management
.Hero-Power Association
.Data Serialization



## Hero Management
  -  Create, update, delete, and retrieve superheroes.

## Power Management
  - Create, update, delete, and retrieve superpowers.

## Hero-Power Association 
  - Manage the relationship between heroes and their powers, including the strength of each power for a given hero.

## Data Serialization 
   - Convert objects to dictionaries for easy JSON serialization.
    

## Technologies Used  
   . Python
   . Flask
   . SQLAlchemy
   . SQLite3  

## Setup & Installation
   . Prerequisites
   - Ensure you have the following installed on your machine:
        . Python 3.7 or higher
        . pip (Python package installer)
        . A virtual environment tool (e.g., venv, virtualenv, or pipenv)

   To get a local copy of the project up and running, follow these steps:

     1. *Clone the Repository:*
      git clone https://github.com/SaraAchieng/Superheroes
   
     2. *Create a virtual environment:*
      pipenv install
      pipenv shell

     3. *Install the required packages:*
      pip install -r requirements.txt

     4. *Set up the database:*
      from app import db
      db.create_all()
    
     5. *Run the application:* 
      flask run

## API Endpoints
   - GET /heroes: Retrieve all heroes.
   - GET /heroes/<id>: Retrieve a hero by ID.
   - GET /powers: Retrieve all powers.
   - GET /powers/<id>: Retrieve a power by ID.
   - PATCH /powers/<id>: Update a power partially by ID.
   - POST /hero_powers: Create a new hero-power association.


## Contributing

Contributions are welcome! If you have any suggestions, bug reports or feature requests please create an issue or submit a pull request.

If you wish to contribute follow the steps below:

1. Fork the repository.
2. Create a new branch (git checkout -b feature/your-feature).
3. Make your changes and commit them (git commit -m 'Add some feature').
4. Push to the branch (git push origin feature/your-feature).
5. Open a pull request.

## Support & Contact
  - email :: achieng997@gmail.com

## License
*Licenced under the MIT License Copyright (c) 2024 **Sara Achieng


    


