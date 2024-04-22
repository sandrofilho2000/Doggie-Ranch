# 🦴 Doggie Ranch

<div style="display: inline"><br>
    <img align="center" alt="Doggie Ranch-HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/6910f0503efdd315c8f9b858234310c06e04d9c0/icons/html5/html5-original.svg">
    <img align="center" alt="Doggie Ranch-CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/6910f0503efdd315c8f9b858234310c06e04d9c0/icons/css3/css3-original.svg">
    <img align="center" alt="Doggie Ranch-JS" height="30" width="40" src="https://github.com/devicons/devicon/blob/master/icons/javascript/javascript-plain.svg">
    <img align="center" alt="Doggie Ranch-Django" height="30" width="40" src="https://github.com/devicons/devicon/blob/master/icons/django/django-plain.svg">
    <img align="center" alt="Doggie Ranch-Python" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg">
    <img align="center" alt="Doggie Ranch-SQLite" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/6910f0503efdd315c8f9b858234310c06e04d9c0/icons/sqlite/sqlite-original-wordmark.svg" />
    <img align="center" alt="Doggie Ranch-PHP" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-original.svg" />
    <img align="center" alt="Doggie Ranch-Pandas" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/6910f0503efdd315c8f9b858234310c06e04d9c0/icons/pandas/pandas-plain-wordmark.svg">
</div>
<br />

![Doggie Ranch](https://github.com/sandrofilho2000/Doggie-Ranch/assets/75636911/02c2d023-868e-4019-985a-ef3fb7bd70e4)

> This README guides through the process of creating new features and fixing bugs in the Doggie Ranch project.

My version of Doggie Ranch includes pages for viewing, adding, editing, and deleting project Models.

## Services

> This model includes the fields: name and cost.

### Service List

![Service List](https://github.com/sandrofilho2000/Doggie-Ranch/assets/75636911/80aad888-26cf-4dae-bad7-c2bf09b2c1f0)

> It lists every added service with a delete button included.

### Service Adding

![Service Adding](https://github.com/sandrofilho2000/Doggie-Ranch/assets/75636911/70d5306b-e5d2-4121-9a9a-6e25cfb192db)

> This form makes it possible to add any service with any cost.

### Service Editing

![Service Editing](https://github.com/sandrofilho2000/Doggie-Ranch/assets/75636911/e86ac311-b282-421f-85f0-2e29155b1d18)

> Works similarly to the add form. Once the item is updated, it will update every related appointment.

## Pets

> This model includes the fields: first name, last name, species, and profile image (optional).

![Pets](https://github.com/sandrofilho2000/Doggie-Ranch/assets/75636911/f04829c0-33a3-4586-a2c0-7f845cb1ae19)

### Pet Adding

![Pet Adding](https://github.com/sandrofilho2000/Doggie-Ranch/assets/75636911/45dcb554-4281-42b6-8263-a2562a6031f3)

> Even though the profile image is not a required field of the form, we can notice that the newly created item receives the image from the species model.

### Pet Editing

![Pet Editing](https://github.com/sandrofilho2000/Doggie-Ranch/assets/75636911/7a2c14b8-cc50-41b2-bdbb-7b01ddc6fd03)

> Works the same as the adding model, but the input receives values of the model as default.

## Customers

> This model includes the fields: first name, last name, email, and profile image (optional).

![Customers](https://github.com/sandrofilho2000/Doggie-Ranch/assets/75636911/00dfa9f5-1a81-4f6e-85c3-bad096d17781)

### Customer Adding

![Customer Adding](https://github.com/sandrofilho2000/Doggie-Ranch/assets/75636911/ed7e3cf8-caa3-4b42-a356-ce520730afe4)

> If the user doesn't upload a profile image, the model contains a default one which will fill the field.

### Customer Editing

![Customer Editing](https://github.com/sandrofilho2000/Doggie-Ranch/assets/75636911/927d1cd6-2b89-46e3-b146-e89d617a1df7)

> Similarly to the Dog Model, it's still possible to upload a custom image for the Customer item too.

## Appointments

The Appointment model has pages for listing, adding, editing, and deleting its items.

![Appointments](https://github.com/sandrofilho2000/Doggie-Ranch/assets/75636911/dfb18a7b-ade8-453c-bfa8-6ef415b3af2a)

> A Navbar containing browsable pages

<br />

![Search Functionality](https://github.com/sandrofilho2000/Doggie-Ranch/assets/75636911/5479aeb6-37a0-4433-92f3-8b5ba3b32499)

> A functional search input which returns real data from the database model

<br />

![Current Appointments](https://github.com/sandrofilho2000/Doggie-Ranch/assets/75636911/4c8374dc-f9e8-41d0-83a8-af3ec9625b26)

> A list of the current appointments

<br />

### Appointment Details

> This page brings information such as appointment date, clickable pet links, services, and total costs.

![Appointment Details](https://github.com/sandrofilho2000/Doggie-Ranch/assets/75636911/86bd4186-17b3-4515-a254-5768b3b81788)

### Appointment Adding

![Appointment Adding](https://github.com/sandrofilho2000/Doggie-Ranch/assets/75636911/a1f12b1d-9d75-455a-8ecf-8bffb73918ee)

> This form contains a script that automatically updates the cost of the service according to its type and the number of scheduled pets.

### Appointment Editing

![Appointment Editing](https://github.com/sandrofilho2000/Doggie-Ranch/assets/75636911/4e2b6eb7-3164-4fec-b941-a42b17f9dc8b)

> The script works for the editing form too.
