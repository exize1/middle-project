# [Employeely](https://employeely.netlify.app/) - Intra-organizational social network. 
In many companies, we can find several similar guidelines that are the pillars of the company.
One of them - creating a work environment that is organized, pleasant, proactive, cohesive, and contributive.
During the planning phase, we chose to emphasize three main aspects:
- Organized
- Cohesive
- Contributive

We will see how this manifests itself later on.

## Table of contents 
- [Employeely](#employeely)
  - [Why was Employeely made](#why-was-employeely-made)
  - [Running the project](#running-the-project)
  - [Screenshots](#screenshots)
    + [Create user / Login](#create-user-and-login)
    + [Home page](#home-page)
    + [Archive](#archive-page)
    + [Profile Page](#profile-page)
  - [Technologies](#technologies)
  - [Tools and libraries:](#tools-and-libraries)
  - [Whats Next](#whats-next)
  
## Why was Employeely made

This web application was made as part of a 50 hours assignment, in order to show:  
1. Our ability to work with React and its concepts.
2. Demonstrate our understanding of React structure.
3. Practice coding as a team.

## Running the project

1. Clone the repo.
2. Run `npm install`
3. Run 'npm start'
4. Navigate to `http://localhost:3000`.

## Screenshots

### Create user and Login
Login page with Yup validation, and the option to login as a guest (not as a feature but as a tool for making it easy to take a look at the website, instead of signing-up)

<p align="center"><img src="https://res.cloudinary.com/diggwedxe/image/upload/v1666350800/Screenshots/employeely/login_jjswpq.jpg" /></p>

### Home page

On the top-left side you can see a message icon. Its open a chat where the employees can chat with each other in any part/page on the website. 

<p align="center"><img src="https://res.cloudinary.com/diggwedxe/image/upload/v1666350747/Screenshots/employeely/home_ble4df.jpg"/></p>

This section contains the company news. This part contains articles about the company/workers activity in the big society. This part  is focusing on the Contributive aspect:
1. Keep the workers updated about the latest activities. 
2. Motivate the employees to be helpful and contributive themselves. 
3. Give the employee a sense of belonging to a quality place, with depth and values 

<p align="center"><img src="https://res.cloudinary.com/diggwedxe/image/upload/v1666350768/Screenshots/employeely/posts_e844pd.jpg"/></p>

The Company's events, containe a list of the comapny's events, and a calendar with an option to add a payment method, for the company events. This part is focusing on the Cohesive aspect:
1. Employees can be updated about the events the company is planning.
2. Some of the events will cost symbolic price, so the emloyees who decied to take part in it, will feel more belonging to it. 

<p align="center"><img src="https://res.cloudinary.com/diggwedxe/image/upload/v1666350806/Screenshots/employeely/events_dphtly.jpg"/></p>

### Archive

This side of the site focuses on the order aspect, the goal is to create an orderly work environment where you can find all the files in the organization. 

In the Archive page you can see all the file types the company use, and search your desired file type.

<p align="center"><img src="https://res.cloudinary.com/diggwedxe/image/upload/v1666350811/Screenshots/employeely/archive_sh6rel.jpg"/></p>

### Profile page

To find your profile, you need to click the avatar on the navbar, and it will open you a dropdown with 3 options:
Profile, Archive and Logout. 

On this page we have the employee details:
- Name
- Picture
- Role in the company
- Links to the emplyee social networks if he choose to add them (on the "edit' icon)
- Email
- Birthday date

In addition, other workers can add feedback to other employees. This feature also come along with the Cohesive aspect.

<p align="center"><img src="https://res.cloudinary.com/diggwedxe/image/upload/v1666350768/Screenshots/employeely/profile_page_v4vtfd.jpg"/></p>

## Technologies:

* React.JS

### Tools and libraries:

  * react-redux
  * react-router
  * Mui
  * formik and yup


## What's next:
- [ ] Archive page - add a modal for each file type, where you have a list of all the files of the picked type, with an option to search or/and fitler.
- [ ] Events - connect the list to th. 
- [ ] Navbar - Add a searching orion to find other users 
