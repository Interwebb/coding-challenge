# INTER-WEBB INTERVIEW CODING CHALLENGE

Hello potential Inter-webb Intern, In this challenge you are required to build a full-stack Vehicle management web app.

Your app should be able to receive user input from a frontend form, save the data into a database and display the entries.

Please read all the instructions before you get started.

## Instructions:

Clone this repo to your local machine

1. Run npm install to install npm packages, `prisma` for CRUD and `Zod` for backend validation
2. Navigate to the folder called `pages/vehicle`:
    - In this folder create a `form.tsx` file. This is where your form logic will be.
    - The form should consist of 3 fields, `name`, `model` and `number of wheels`. The number of wheels should have 3 options, 2 wheels, 3 wheels and 4 wheels.
    - The form fields should be `required` and only accept input of the right type.
    - In the same folder create an `index.tsx` file where you will display all the vehicles in the db.
    - The vehicle data should be displayed alongside `edit` and `delete` buttons. Both should be functional
3. In the `pages/api` folder you are required to create 2 api endpoints:
   - The first api endpoint will handle `creation` of a single vehicle entry and `retrieval` of all vehicle entries
   - The second api endpoint will handle `updating`, `deleting` and `retrieving` a single entry.
   - Data received at both api endpoints should be validated with ZOD.
4. Once the web app is complete, you are required to `push your code to a public github repo` and then share with us the link to your repo at this email: interwebbbc@gmail.com

## Technologies to be used
- Next.Js
- TypeScript
- Prisma
- Zod
- SQL database of your choice

## Additional notes:
Extra points will be awarded to candidates with:
- Good UI
- Commented code

