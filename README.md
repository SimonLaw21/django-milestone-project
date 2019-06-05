# Issue tracker

Mission statement for project: "Create a web application that allows users to add and edit/store bugs and features requests for a piece of software.""

## Project guidelines

BUILD AN ISSUE TRACKER

Now that you’re a full-fledged web developer you’ve decided it’s probably time for you to start your very own cool, modern startup, offering the extremely awesome UnicornAttractor web app to your users. It’s really really amazing, but we don’t care about it at all in this project. The exciting thing is the business model that you’ve decided upon – you chose to offer the service and bug fixes for free, but ask for money from your users to develop additional features.
The primary entity in the Issue Tracker is a ticket describing a user’s issue, and similar to Github’s issue tracker, you should allow users to create tickets, comment on tickets, and show the status of the ticket (e.g. ‘to do,’ ‘doing,’ or ‘done’). As mentioned, issues come in two varieties – ‘bugs’ (which you’ll fix for free, eventually), and ‘features’ which you’d only develop if you’re offered enough money. To help you prioritize your work, your users will be able to upvote bugs (signifying ‘I have this too’), and upvote feature requests (signifying ‘I want to have this too’). While upvoting bugs is free, to upvote a feature request, users would need to pay some money (with a minimum amount of your choice) to pay for your time in working on it. In turn, you promise always to spend at least 50% of your time working on developing the highest-paid feature.
To offer transparency to your users, you decide to create a page that contains some graphs showing how many bugs or features are tended to on a daily, weekly and monthly basis, as well as the highest-voted bugs and features.
Add any additional pages that would help you attract users to the Issue Tracker (and have them pay you well). To make the users participate as much as possible in your online community, make sure that your UI/UX is sublime. Feel free to add additional features, such as a blog, extra perks for active participants, etc.
If you want to have some more fun with this, feel free also to add pages describing your fictional UnicornAttractor application.
And of course, as this project is going to be the lifeblood of your company, it’s essential that new developers that join the company will be able to get up and running as quickly as possible. Documentation is the best way to achieve this.
 
## UX and Design
 
The user interface has been design to be contrasting and simple to read and use. I have used bold colours to make the information and buttons stand-out on a plain white background which should be easily readable for all capable users on any device.
The font is simplistic and the styling of the content area is centred on the screen to make the site easily responsive on any screen size.
The buttons and functions are clearly labelled with plain text and relatable icons to help aid the users understanding of what each part of the site does.
The navbar also has few options to keep things as simple as possible.

## Features and functions

The features of the app are simple and easy to use:

1. Login in to an existing account or register a new one.
2. Filter issues by either bugs or features.
3. Add new issues.
4. Edit existing issues.
5. Delete existing issues that logged in user owns.
6. Allow admin access to change and update status of issues.
7. View the status of all existing issues in a dashboard.


## Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- [Materialize](https://materializecss.com/)
    - The project uses **Materialize** to simplify DOM manipulation, and provide structural and styling templates.
- [AWS](https://aws.amazon.com/)
    - This project uses **MongoDB** to create and manage the database used to store the recipe information.
- [Cloud9](https://c9.io/)
    - This project was written with and terminalised through **Cloud9**, to host the code files and use the bash console asa command line interface(CLI)
- [Heroku](https://www.heroku.com/home)
    - This project was deployed to an application using the **Heroku** deployment interface.
- [GitHub](https://github.com)
    - The code for this project is publically accessible through **GitHub**.
- [Highcharts](https://www.highcharts.com/?credits)
    - To display the status of issues on the dashboard in easy to read charts.


## Testing

For the testing phase I used my own desktop PC with various browsers and my android smartphone.
 
I tested the responsiveness of the design by re-sizing the browser windows on the desktop as one of my challenges I faced was ensuring that the textareas for the ingredients and method of each recipe was large enough and still scrollable for varying amount of information.
 
I used the criteria below:

Browser | Navbar Buttons | Adding Issues | Editing Issues | Deleting Issues | Viewing Issue Dashboard | Logging in | Registering | Admin access 
--- | --- | --- | --- | --- | --- | --- | --- | ---
**Chrome** | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes
**Firefox** | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes
**Edge** | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes
**Opera** | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes
**Safari** | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes 
**Mobile** | Yes | Yes | Yes | Yes | Yes | Yes | Yes | Yes

If you would like to view the admin panel simply add "/admin" to the end of the base url and use the credentials:

##### Username

admin

##### Password

Arnold21!


## Deployment

This project was deployed using **Heroku** from the master branch. As of writing this file, there is no difference between the development and deployed version of this project. In order to deploy this project through Heroku, I first had to create the Heroku app on their website. Then, through the terminal, I used `Heroku login ` to connect my Cloud9 environment with Heroku. After entering my credentials I used Heroku apps to check that my recipe app was there. I then pushed the project to Heroku using `git push Heroku master `. I then used `heroku ps:scale web=1` to start the Heroku app.

I then followed the instructions from the codeinstitute MINI PROJECT for adding my STATIC files to the AWS bucket and linking this to my project. A database also had to be created using the "postresql" command in the bash terminal on Cloud9, then adding the databas_url to the config vars of my heroku app.

Once I had these settings in place, I went to the Heroku app and configured and set the **IP (0.0.0.0)** and **PORT (5000)**. Once this was finished I clicked the ‘Open App’ button and my project was officially deployed.

To run this code locally, you may clone this repository from the **Clone or Download** button at the top of the page and write `git clone` followed by the cloned URL into an editor of your choosing. To cut ties with GitHub, use git remote rm origin in the terminal.

The finished application can be visited [Here](https://django-milestone-project.herokuapp.com/)

# Author

[Simon Law](https://github.com/SimonLaw21)


