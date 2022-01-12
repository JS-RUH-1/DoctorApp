
# Create a Doctor App 


We'll build this back-end and front-end app in a group.

# Version 1

### Step 1 (Express)

We did in the lesson earlier. Give it a name that suggests it's a Doctor app.

- Create a REST controller.
- Create a `/home` endpoint that returns a `'Welcome to the Doctor App'` string.
- Use Postman to test the API.


### Step 2 (Data)

Your app will have  two data models: `Doctor` and `Appointment`. You'll use MongoDB as your database to talk to your database.

### Step 3

In this step, you'll only create a `Doctor` model. 

- The `Doctor` should have at least three fields: `name` , `specialty` and `picture`.
- Create APIs to update and delete.

### Step 4

In the next step, you'll add the `Appointment` model and map it with `Doctor`.

- The `Appointment` table should have at least two columns: `date`, `patientName`, and `reasonForAppointment`.
- The `Doctor` and `Appointment` tables should be mapped to each other.
- A user can add and delete a Appointment.
- A user should be able to view all of the Appointments added
  
### Step 5(React)

In this step, create a front-end app using react. Make sure you create several components that connected to the `Doctor` and `Appointment` models.


**Again, the mapping between the `Doctor` and `Appointment` models is one-to-many mapping.** 


### Bonus

1- Add authentication

2- Use uploading files to uplaod an image from your Computer for `Doctor` Picture.

3- Deploy your Application using Heroku.

# Version 2

We will be working with differnt team lead.


### Step 1 

Your app will have  three data models: `Doctor`, `Appointment`, and `Patient`. You'll use MongoDB as your database to talk to your database.
### Step 2

In this step, you'll only create a `Patient` model. 

- The `Patient` should have at least three fields: `name`, `phoneNumber` and `email`.
- Create APIs to read, create, update, and delete.

### Step 3 

In this step, create a front-end app using react. Make sure you create several components that connected to the `Doctor` ,`Appointment`, and `Patient` models.

### Step 4
Deploy your Application using Heroku.

### Bonus

- For emails, you can integrate with https://www.mailgun.com. They have a free tier that you can utilize.


**Again, the mapping between the `Doctor` and `Appointment` models is one-to-many mapping, and the mapping between the `Patient` and `Appointment` models is one-to-many mapping** 