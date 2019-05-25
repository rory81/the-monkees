# The Monkees

The Monkees were the One Direction of the Sixties, but where actually put together for a television show rather than a band. The music on this TV show were top-of-the-charts hits, eventhough they had to compete against the popularity of all those Beatles songs.
The challenge is to be able to give people who grew up being a Monkees'fan the sixties vibe, but still make it accessible for other target audiences. Fans should be able to relive old memories by seeing old TV shows or by booking them and make some new memories along the way.
Most people who did not grew up with the Monkees will recognize the music when they hear it, but simply did not know it were the Monkees singing it. So its the music rather than the tv show that eventuallly made their legacy.

Even though not all the members of the Monkees are still alive the remaining Monkees still know how how to create a illuminating performance. 
A music critic from _"Music in Minnesota"_, Erik Ritland, described it best after seeing them perform:
**_"The Monkees'Best kept secret: Their Music is really, really good"_**

 
## UX
 
The main user experience is to get the sixties vibe. When looking at sites from similar bands from that time it screams color and unlike most current sites it is very crowded. Which is probably how the sixties were, colorful and lively.

**The fan from back in the day wants:**
- quick access to recognisable music
- to see the Monkees again the way they remembered
- quick access to news and background about their idols from the past
- to be able to follow them again on socials
- quick access to dates and locations where they can see the Monkees perform to relive the old memories
- the option to book The Monkees for an event of there own

**The user curious about The Monkees wants:**
- quick access to the Monkees' music they recognize but didn't know it where the Monkees
- to put faces to the band _'The Monkees'_
- easy access to more material
- to know the origin story behind _'The Monkees'_ 
- to be part of The Monkees' community by following them on socials
- dates and locations for live performances - if the location and price is right people might be curious about them

In the folder mockups - under the folder assets - a PDF- as well as a Pencil-project version is available of the initial mockups.

**Deviations from the mockups**
- In the final version the Media page (Orange tab) for the mobile and iPad version have titles, which weren't in the inital mockups. For the mobile version this was added so the page content could fill the page and there was some spacing between the three different media elements. For the ipad spacing was the only reason. The title wasn't added to the desktop version, because it was more calming without it and the media items were also bigger there and less need for spacing between the three media elements. 
- The banner of the about page eventuallly did not get a green background color, because the banner with the Monkee picture were enough and the green turned out to be more of a distraction rather than an addition.



## Features

This project has 4 pages. A short description of these pages is written below.

### 1. Homepage
Due to the color scheme - with is directly related to the colors in the navigation - the underlining 3 features are easily noticeable by the user.

- The user can instantly see what is new with The Monkees
- The white in between the colors makes the dates and location of upcoming events for the Monkees pop out.
- Top three of the most known hits by The Monkees can be heard. The middle video shows the album _'The Birds, The Bees, & the Monkees'_ and is a direct reference to the anniversary mentioned in the News section. The other 2 video's show photo's and video of the monkees back in the day. This section is meant to make the user want to see/hear more of The Monkees and the orange is therefore directly linked to the media tab in the navigation.

### 2. Media page
This page gives the user access to more material then the given top three on the homepage. It gives the user access to
- Video about the monkees and TV episodes of the monkees
- Pictures of albums of the monkees which are nice as pictures, but also gives the user album titles to search for music on mediums like Spotify.
- The user can listen to some Monkee recordings in the music section, but also has a link available to see the corresponding lyrics to the song.

### 3. About page
A short origin story of The monkees is given as wel as a short biography of all four Monkees.

### 4. Book page
For the Monkees it is very important that users can easily find the way to book them. Therefore, a link is readily available in the footer linking to the book page.
The form on the book pages is validated but the checkbox for validation is made invisible to the user so validation is standard.
Due to privacy considerations a disclaimer is added.

### General
All pages have socials in the footer, linking the user directly to the Monkee community.



## Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- [HTML](https://www.w3.org/html/)
    - The project uses **HTML** as it is World Wide Web’s core markup language
- [CSS](https://www.w3.org/Style/CSS/)
    - The project uses **CSS** to style the HTML
    - Bootstrap (https://getbootstrap.com/) classes are used
- [JQuery](https://jquery.com)
    - The project uses **JQuery** to simplify DOM manipulation.
    - Bootstrap (https://getbootstrap.com/) plugins are used



## Testing

##### General:
    1. Make github pages and test them on
        - Windows
        - Apple

**Bug:** The pages worked on Apple (OS Sierra) using Cloud9 preview but when testing the Github pages on a 27 inch screen **not** all pages where displayed as intended. Not all pages filled up the entire page. There was an error in the consul:

**Error:**  Failed to load resource: the server responded with a status of 404 () https://rory81.github.io/favicon.ico 

However, testing the Github pages on a iPad Air 2 (OS 12.2) **did** give the intented results of every page.

##### Navigation:
    1. Go to the "Media" page and check if it is redirected to the Media page
    2. Go to the "About Us" page and check if it is redirected to the About US page
    3. Go to the "Book Now!" page and check if it is redirected to the Book page
    4. Go to the "Home" page and check if it is redirected to the Home page
    5. Use the inspect developer tool and select the mobile device (Galaxy S5) and check if a hamburger menu is shown. Open the hamburger and repeat the previous 4 steps.
    6. Use the inspect developer tool and select the ipad as a device and repeat the above mentioned first four steps

##### Footer:
    1. Go to the "Media" page and check if
        - the Book Us Now! redirects the page to the Book Now! page
        - all the social media icon redirect to the Monkee page of the corresponding social
    2. Go to the "About Us" page and check if
        - the Book Us Now! redirects the page to the Book Now! page
        - all the social media icon redirect to the Monkee page of the corresponding social
    3. Go to the "Book Now!" page and check if
        - the Book Us Now! refreshes the Book Now! page
        - all the social media icon redirect to the Monkee page of the corresponding social
    4. Go to the "Home" page and check if
        - the Book Us Now! redirects the page to the Book Now! page
        - all the social media icon redirect to the Monkee page of the corresponding social

##### Pictures, Video's and Audio fragments:
    1. Go to the "Media" page and check if 
        - the caroussel for the video/tv fragments moves with the right as well as the left indicator
        - the video/tv fragments can be played and paused
        - the caroussel for the pictures moves with the right as well as the left indicator
        - the caroussel for the audio fragments moves with the right as well as the left indicator
        - the audio fragments can be played and paused
        - the "Want the lyrics" link redirects to the www.azlyrics.com site and displays the lyrics of the corresponding audio fragment
        - the picture banner is correctly displayed
    2. Go to the "About Us" page and check if the picture banner is correctly displayed
    3. Go to the "Home" page and check if 
        - the video fragments can be played and paused
    4. Use the inspect developer tool and select the mobile device (Galaxy S5) and repeat the previous 3 steps.
    5. Use the inspect developer tool and select the ipad as a device and repeat the above mentioned first three steps

##### Booking form:
    1. Go to the "Book Now!" page
    2. Use the inspect developers option to check the page on mobile (Galaxy S5) and iPad. Running the page without the inspect developer option represent the dtp version.
    3. Try to submit the empty form and verify that an error message about the required fields appears
    4. Try to submit the form with an invalid email address and verify that a relevant error message appears
    5. Try to submit the form with all inputs valid and verify that a success message appears.



In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

## Deployment

Github pages were made using the master branch (https://rory81.github.io/the-monkees/)


## Credits

### Content
- The text for section Y was copied from the [Wikipedia article Z](https://en.wikipedia.org/wiki/Z)

### Media
- The photos used in this site were obtained from ...

### Acknowledgements

- I received inspiration for this project from X
