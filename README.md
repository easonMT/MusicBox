# MusicBox
A platform to discover and showcase favorite new artists and genres. Tailored to provide recommendations based on user's genre preference.

## Description
This application is designed to help users discover new music artists based on their preferred genres. The platform highlights both featured artists and provides curated recommendations to enhance the user's music discovery journey.

## Team Members and Responsibilities:
This project was built collaboratively by a dedicated team. Below are the tasks and responsibilities of each member:

[__Tristin Eason__]:

Role: Product Manager/Backend Developer/Frontend Developer
*  Responsibilities:
  -  Ideation and conceptualization of the project.

*  Backend development:
  -  Design and implementation of the FeaturedArtist entity, repository, controller, and service class.
*  Frontend development:
  -  Development of the select.html page.
  -  Design and coding of the styles.css and app.js pages.
  -  Coordination and management of team tasks and project direction.

[__Ibrahiim King__]

Role: Frontend Developer/Backend Developer

* Responsibilities:
  -  Development of the HTML pages: about, bio, errorAddLanding, errorsignpage, guestselect, landingpage2, landingpageform, signinform, signinselect
  -  Design and coding of the CSS pages of the same name and guest.js file.
  -  Partnered with Denise to design and implement the WelcomePage entity, repository, controller, and service class. 

[__Winston Leacock II__]

Role: Frontend Developer/Backend Developer
*  Responsibilities:
  -  Development of the recommendations.html page.
  -  Design and coding of the recommendations.css page.
  -  Winston also began to design and implement the Genres entity, but we decided to not go with this option. 

[__Denise Manning__]

Role: Backend Developer
*  Responsibilities:
  -  Design and implementation of the WelcomePage entity, repository, controller, and service class along with Mr. King. 

[__Kentavious Boyd__]

Role: Backend Developer
*  Responsibilities:
  -  Design and implementation of the ArtistPopulator file, along with Kevin Duong.
  -  Design and implementation of the FeaturedArtistData.txt file, prepopulating data into our database.

[__Kevin Duong__]

Role: Backend Developer
*  Responsibilities:
  -  Design and implementation of the ArtistPopulator.java file, along with Mr. Boyd.
  -  Design and implementation of the Data.txt file, prepopulating data into our database.
  -  Design and implementation of the FaveNewArtist entity, repository, controller, and service class along with a little help from myself.

## Set Up

In designing our application, we adopted the Model-View-Controller, or MVC, design pattern, allowing us to create a scalable and maintainable application. Keeping the MVC design in mind, the FeaturedArtists were represented by a model that will display to the view the Featured Artists, which is rendered at an endpoint created in our FeaturedArtist Controller. 
To build the backend we used SpringBoot with an H2 database, Thymeleaf, and Java, where the models represent our data, the controllers handle user interactions and Thymeleaf is used to inject the backend data into the view. On the front end, we crafted a user-friendly interface by using HTML, CSS, and JavaScript, creating a visually appealing and intuitive interface for our users. So, as you will soon see, when a user interacts with our featured artists page and selects an artist the controller handles this request, updates data in the model, and our frontend seamlessly displays to the user the recommendations of our favorite new artists.


  
