# Programmer Hub

Social network developed during the "Semana Super Full Stack" of the [**OneBitCode**](http://onebitcode.com/). The project was developed using [**Ruby on Rails**](http://rubyonrails.org/).

## Access link for example

The social network can be accessed for testing through the following link:

* [**Programmer Hub**](https://programmerhub-wagner.herokuapp.com/)

## Running the project locally

Make the clone in the repository to a local directory on the computer. After entering the directory ***programmer_hub*** by the terminal and install the dependencies with the command below:

```$ bundle install```

It is necessary to configure the database with local settings of your machine. The database used was PostgreSQL. To change the settings simply update the file ***config/database.yml***.

After configuring the database, create the database and running the migrations:

```$ rails db:create db:migrate```

Run the projetc with command:

```$ rails server```

Open your browser and go to:

```http://localhost:3000```
