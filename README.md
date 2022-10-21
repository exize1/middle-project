# Employeely - Intra-organizational social network. 
In many companies, we can find several similar guidelines that are the pillars of the company.
One of them - creating a work environment that is organized, pleasant, proactive, cohesive, and contributive.
During the planning phase, we chose to emphasize three main aspects:
- Organized
- Cohesive
- Contributive

We will see how this manifests itself later on.

The main project objective is to show our ability to work with React and its concepts combined with  in order to 


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

<p align="center"><img src="https://res.cloudinary.com/diggwedxe/image/upload/v1666347642/Screenshots/employeely/res-console.cloudinary_z8iwvo.jpg" /></p>

### Home page
Welcome page  

<p align="center"><img src="https://res.cloudinary.com/diggwedxe/image/upload/v1666347644/Screenshots/employeely/res-console.cloudinary_ysgzzi.jpg"/></p>



<p align="center"><img src="https://res.cloudinary.com/diggwedxe/image/upload/v1666277608/Screenshots/employeely/res-console.cloudinary_ni2p50.jpg"/></p>
<p align="center"><img src="https://res.cloudinary.com/diggwedxe/image/upload/v1666347640/Screenshots/employeely/res-console.cloudinary_af7ws3.jpg"/></p>

### Archive

This side of the site focuses on the order aspect, the goal is to create an orderly work environment where you can find all the files in the organization. 

In the Archive page you can see all the file types the company use, and search your desired file type.

<p align="center"><img src="https://res.cloudinary.com/diggwedxe/image/upload/v1666347650/Screenshots/employeely/res-console.cloudinary_gv6r2v.jpg"/></p>

### Profile page

<p align="center"><img src="https://res.cloudinary.com/diggwedxe/image/upload/v1666277622/Screenshots/employeely/res-console.cloudinary_vnihdk.jpg"/></p>

## Technologies:

* React.JS

## Tools and libraries:

  * react-redux
  * react-router
  * Mui
  * formik and yup


## What's next:
- [ ] Archive page - add a modal for each file type, where you have a list of all the files of the picked type, with an option to search or/and fitler.
- [ ] Add 'change password' and 'Delist all my auctions' options in the setting section. 
- [ ] Replace the Credit Card option with Paypal or/and Tranzila instead of saving the user's card details in the DB. 
- [ ] Improve the list of 'Most popular' (on the home page) so it will show the most popular at different times (24 hours, 7 days, 30 days).
- [ ] Link the search output to the product page.
- [ ] Show in the auction page, only the Active products
