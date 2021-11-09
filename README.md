# The Bike People

## Welcome - [Preview The Bike People](https://jamitag.github.io/The-Bike-People/)

This is a website intended for bike users and enthusiasts alike. For anyone wishing to service or maintain 
their bicycle, The Bike People offer service and maintenence plans to meet various requirements and budgets. 
The website will also provide an opportunity for cyclist to come together and socialise by providing access 
to a community of like minded cycling enthusiasts who arrange regular rides around the Edinburgh and Lothian 
region several times a week. Our passionate cycling professionals are knowledgable and skilled, ensuring 
everyone has a cycling experience to remember. Visitors to the website will be able to book their maintenence
 requirements as well as book onto any of our group rides which roll out each morning, catering to a range of 
 abilities.

## Features 

### Existing Features

- __Navigation Bar__

The Navigation bar appears at the top of all three pages, maintaining a consistant look across the website. 
Within, users will find links to a relavant area of interest i.e Services or Social Spins. The company name 
appears in the left of the Navigation bar which will direct the user back to the homepage if clicked. Each 
item in the Navigation bar will appear highlighted when on that particular page, to aid navigation.

- __Motivational Image__

The first feature that will be apparant to users is the hero image displayed on the homepage coupled with a 
motivational quote from the legendary, Eddy Merckx. This will leave no doubt in the users mind that this is 
a website designed for cyclists.

- __What we do section__

This section displays the services available to our customers. Two simple options are clearly represented 
leaving the user wihtout any doubt as to their purpose. The user will click on they relevant option and will 
be directed to the page they have selected.

- __Footer__

The footer is made up of links to several social media sites which will open in a new tab when selected.  
The Bike People's social media presence provides us an additional opportunity to provide information to our 
customers and where they can engage with ourselves as well as fellow cyclists.

- __Services page__

This page will display all information relating to services available. It will detail each level of service 
and the price so the user can decide which service best fits their needs.

- __Social Spins page__

This page provides information to the user about regular Social Spins which take place 4 times a week. 
Here, the user will discover the when and where as well as suitability of the ride to ensure each participant 
has an enjoyable ride. There is a form on this page for users to book their place on a ride.


### Features for the future

- A chat feature whereby customers can be directed to a chat function with one of our technicians to 
discuss any maintenance / servicing queries.
- A gallery, illustrating the various scenic rides we offer.
- Some animation features across the whole site once developers skill improves.

### Design

## Color scheme

## Typography

## User Experience (UX)

### User Stories

#### As a user

- I want to navigate through the site as smooth as possible.
- Few button clicks to get to my destination.
- Easily identifiable information on rides available.
- Clear method of booking onto rides.
- A way of interacting with The Bike People via social media.

#### As a site owner

- I want display all the products and services clearly to customers and potential customer.
- I want users to have a smooth and intuitive experience on this website.
- I want users to use the form for booking onto rides instead of contacing us via email/telephone.
- I want our users to stay in touch through our social media presence.

## Technologies

### Editor
- GitPod


### Languages
- HTML5
- CSS3


### Version control
- GitHub


### Libraries
- Font Awesome
- Google Fonts
- Stock Images

## Testing

### Compatability

I tested the sites compatabillity on different browsers and screen resolutions. Across multiple browsers 
(Chrome, Safari and Mozilla) the site appeared largely as expected, the exception being on Safari; 
my selected font, Raleway failed to function. Several devices of varying screen sizes 
(Iphone 12, MacBook Pro, Ipad) where also tested.

### Validator testing 

#### HTML

I tested the HTML for each page using the [W3C HTML validation service](https://validator.w3.org/nu/)

Both Home and Servicing pages where found to have no issues. Issues uncovered on the Social Spin page can 
be seen below;

<img src="assets/images/readme-images/social_spin_validation_issue.webp">

As you can see, the errors where mostly stray tags and unclosed elements which were easily debugged.

#### CSS

My style.css file was tested using the [W3C CSS validation service](https://jigsaw.w3.org/css-validator/) and 
showed no errors.

### Performance testing

Performance was tested using the Lighthouse report function within Chrome Dev Tools.

The following results where gernerated;

- Homepage for desktop result

<img src="assets/images/readme-images/homepage_desktop.webp">

- Homepage for mobile result

<img src="assets/images/readme-images/homepage_mobile.webp">

- Servicing page for desktop result

<img src="assets/images/readme-images/servicing_desktop.webp">

- Servicing page for mobile result

<img src="assets/images/readme-images/servicing_mobile.webp">

- Social Spin page for desktop result

<img src="assets/images/readme-images/social_spin_desktop.webp">

- Social Spin page for mobile result

<img src="assets/images/readme-images/social_spin_mobile.webp">

### Issues

<b>Issue</b>
There was difficulty aligning link elements within the nav-bar to the right.

<b>Solution</b>
Following a quick discussion with a tutor, it was discovered I simply had to target the actual link items 
for styling instead of the parent container DIV.

<b>Issue</b>
I was unable to align the three service plan DIVs horizontially to make responsive for mobile screens. 
They where originally floated to make them appear inline.

<b>Solution</b>
I tried a solution from stackoveflow.com which suggested I had to wrap a container around each DIV 
representing each service plan and style it as display: flex; to appear horizontially and then add 
display: block in the media query to revert to a vertical position.

<b>Issue</b>
I created a table displaying the ride details on the Social Spin page which when viewed on a desktop, appeared 
nicely acros the width og the screen. However, when the screen size was reduced, I had difficulty making the 
table display vertically.

<b>Solution</b>
I was unable to find a solution to make the table display correctly for mobile devices and therefore decided 
to replace the table with multiple divs displaying the necessary information which I was the able to make 
responsive.


