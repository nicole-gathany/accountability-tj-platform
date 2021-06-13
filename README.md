# Accountability app

In the past decade, there have been many instances of police brutality that have led to murder of black people in the US (George Floyd, Breonna Taylor, etc).

Many have argued that prisons and prison labor have been used to continue the exploitation of black and brown people's labor that should have ended during slavery (see Yaa Gyasi's Homegoing or Angela Davis's Are Prison's Obsolete).

As a result of the violence committed by police and prisons onto black and brown communites, many community black and brown grassroots organizers from groups like SNAPCo in Atlanta or the Audre Lorde Project in New York have sought to build and promote systems of transformative justice.

Increasingly, transformative justice processes of accountability are being looked at as possibilities for justice outside of the criminal justice system.

For survivors, transformative justice (ideally) would involve a focus on healing and support for the survivor as opposed to an environment where they are forced to rehash their trauma and prove that it happened.

Unfortunately, unlike the criminal justice system (which can be accessed by dialing 911), alternative processes of accountability are not accessible to everyone who experiences harm, especially victims/survivors who lack in person community. This web application seeks to serve as an open source platform for accountablity especially during the COVID-19 pandemic where many people cannot meet in person.

## Approach

The approach of this platform is using an approach by The Chrysalis Collective which was found in The Revolution Starts at Home. The book says that "The Chrysalis Collective was formed when a friend and member of the community experienced rape by another local activist."

## The accountability and healing approach from The Chrysalis Collective involves 8 steps:

1. Gathering: forming a survivor support team
2. Explanding: forming an accountability team
3. Communicating: defining the relationship between teams
4. Storming & developing: create a transformative justice plan
5. Summoning: prepare for the first approach
6. Building: the first meeting
7. Transforming: meetings with the accountability team
8. Evaluating: lessons learned

## Features

1. User login for suvivors and support team
1. Invitation capabilities for suvivors to invite allies to their support team

For more information: https://www.akpress.org/revolutionstartsathome.html

Disclaimer: this web application cannot provide legal advice. If you are in the midst of an abusive relationship where you are in eminant danger, please call 800.799.SAFE (7233) or go to https://www.thehotline.org/.

## Instructions for deploying to Heroku

### Install

`npm install`

---

### Things to add

- Create a `.env` file and add the following as `key = value`
  - PORT = 4000 (can be any port example: 3000)
  - DB_STRING = `your database URI`
  - CLOUD_NAME = `your cloudinary cloud name`
  - API_KEY = `your cloudinary api key`
  - API_SECRET = `your cloudinary api secret`

---

### Run

`npm start`
