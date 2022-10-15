
# Meshwar

Here in Palestine, when you’re bored and looking for something to do, many things like going to the cinema, or to the beach, are usually out of reach. Also, in each city, there are many hidden gems and places only people from the city know about.

Our idea is to provide a platform for Palestinians to *share and learn about different events* in their area, or an area they are visiting, and to *get new ideas about activities they can do anytime*. 

Our website depends on user-generated content; we want users to add any events happening around them and to share ideas for experiences they would like other people to have in their favorite places. 



## Deployment

This project was deployed using AWS

- #### Public IP Address: http://18.234.167.182/

## Functionalities and Features

- Users can register or login to our website. 
- Once logged in, users can create events and activities, and later be able to edit or remove them.
- Users can browse activities added by other users, divided by city. 
- Users can view each activity for more information and details. 
- Users can “up-vote” or “down-vote” activities. 
- Users can check their profile for activities they added, and activities they up-voted. 
- Users can use a random generator, where they select a city, click the random button, and they receive a random activity that corresponds to this city. 
- All pages include a navigation bar that provides a smooth and intuitive navigation experience and easy access to all pages.
- All pages in our website are fully responsive to different screen sizes.



## Demo
User Registration:

We used server side validation to make sure data is entered correctly in the corresponding fields.

![](https://github.com/karam-taha/gifs-test/blob/master/gifs/register%20validation.gif)



E-mail and password field validation is implemented using AJAX, validations are done in real time to check if e-mail is already registered and if passwords match.

![](https://github.com/karam-taha/gifs-test/blob/master/gifs/email%20and%20password%20ajax.gif)

Dashboard:

Users can easily navigate between different cities. Clicking on any city leads to its corresponding city dashboard. 

![](https://github.com/karam-taha/gifs-test/blob/master/gifs/dashboard.gif)

Create Activity:

Users can add an activity, with the date being optional. They have to specify the city using a dropdown menu. 

![](https://github.com/karam-taha/gifs-test/blob/master/gifs/create%20activity.gif)

View Activity:

Users can view each activity to see more details. If this activity was added by them, they can edit or remove it. If not, they can only up-vote or down-vote. 

![](https://github.com/karam-taha/gifs-test/blob/master/gifs/view%20activity%20and%20upvote.gif)

Edit Activity:

Users can modify the information of activities they previously added. The same validations apply as when creating the activity. 

![](https://github.com/karam-taha/gifs-test/blob/master/gifs/updating%20activity.gif)

Profile:

Users can check their profile for content they added, and access this content to edit or remove it. They can also see the content they “up-voted” or liked.

![](https://github.com/karam-taha/gifs-test/blob/master/gifs/view%20profile.gif)

Random generator:

Users have the option to receive a random activity in their desired city.

![](https://github.com/karam-taha/gifs-test/blob/master/gifs/random.gif)


## Tech Stack
This project was built using Django framework, and uses the following technologies:

**Client:** HTML, CSS, Javascript, Bootstrap, Jquery

**Server:** Django, AJAX


## Tools
Different tools were used to plan and manage the project, such as:
- Balsamiq: For creating the wireframe
- Trello: For managing the progress of the project and organizing the workflow between the different team members
## Visual Identity 

| Colors             | Hex                                                                |
| ----------------- | ------------------------------------------------------------------ |
| Cultured | ![#f5f5f5](https://via.placeholder.com/10/f5f5f5?text=+) `#F5F5F5` |
| Royal Blue Dark | ![#10316B](https://via.placeholder.com/10/10316B?text=+) `#10316B` |
| Queen Blue | ![#326B9A](https://via.placeholder.com/10/326B9A?text=+) `#326B9A` |
| Arctic Lime | ![#E0FF4F](https://via.placeholder.com/10/E0FF4F?text=+) `#E0FF4F` |
| Tart Orange | ![#FF4949](https://via.placeholder.com/10/FF4949?text=+) `#FF4949` |

## Logo

![logo](https://github.com/karam-taha/meshwar/blob/master/python_project/dashboard_app/static/images/logo-navy.png)


## Authors

- [@karam-taha](https://github.com/karam-taha)
- [@reinahandal](https://github.com/reinahandal)
- [@SaeedQatanani](https://github.com/SaeedQatanani)
