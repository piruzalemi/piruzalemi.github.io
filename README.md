# piruzalemi.github.io




                            piruz alemi github io for alemi websites served on github

This is Piruz Alemi Website created by Piruz Alemi tested from both Client & Server sides. This is a prototype of what
ultimately becomes a TV-Channel, for a world-wide web review of Alternative cinema.

The first program on this site consists of A Web based HTML - CSS interfacing with Flask & MangoDB
to stream video files, selected by a user interface on the basis of Country of Origin, Name of Director or
Title of Films, from any country in the world.

The input data is being fed live about every 2 minutes, receiving films from any country in the world, subject to
filmmkers approval for its visualization on this POC-TV-Channel.
Currenty we have archived 2000 received films, which is rapidly expanding to 10,000 in 3 months from now.

Some design considerations included:

    1. Simplicity of use. 
    2. A set of Navigations
    3. An interface with a backend data base
    4. A user friendly front end selection / navigation process
    5. A set of external links for additional routings
    6. Scalability
    7. Rapid/local deployment, with perhaps also SQLITE, for watching films on a hand watch!!!
    
                                        Thank you! Piruz Alemi Jan 20, 2020
                                        
                                        
                    Note to the users: The data used in this site is proprietory information and may not be used or
                    circulated in public, without the written permission of the director of the film and its web designer
                    Piruz Alemi.
                    
                    Current data used is solely for illustration purposes.
                    
Website Requirements and specifications follows:

    This website consisted of 7 pages total, including:

A landing page containing:

    An explanation of the project.
    Links to each visualizations page.


    Four visualization pages, each with:

        A descriptive title and heading tag.
        The plot/visualization itself for the selected comparison.
        A paragraph identifying a. Name of Director, b. Title of Film and c. Country of Origin.


A "Comparisons" page that:

        Contains all of the visualizations on the same page so we can easily visually compare them.
        Uses a bootstrap grid for the visualizations.

        The grid has two types of visualizations across on screens medium and larger, 
        and 1 across on extra-small and small screens.

A "Data" page that:

Displayed a responsive table containing the data used in the visualizations.
In this case supplementary information about the film director + synopsis of the film. 

        1. The table must be a bootstrap table component.
        2. The data must comes from exporting the .csv file as HTML, or converting it to HTML.
        3. I used a tool I already knew, pandas: Pandas has a nifty method appropriately called
            to_html that allows one to generate an HTML table from a pandas dataframe. 
        
        See the documentation here


The website at the top of every page, included a navigation menu that:

        1. Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
        2. Contains a dropdown on the right of the navbar named "Films" which provides links to each Directors' 
            visualization page + film
        3 Provides two more links on the right: 
                a. "Comparisons" which links to the comparisons page
                b. "Data" which links to the data page.
            
The NAV: Is responsive (using media queries). 
            The nav has similar behavior as the screenshots "Navigation Menu" section 
            (notice the background color change).

Finally, the website was deployed to GitHub pages.
            When finished, it was submitted to BootcampSpot the links to:
            1) the deployed app and 2) the GitHub repository.

Considerations:

    I chose my film dataset. Alternatively, I used Director's own datasets and pulled their images from my assets folder.

    I used bootstrap. This included using:

        1. The bootstrap navbar component for the header on every page,
        2. The bootstrap table component for the data page, and 
        3. The bootstrap grid for responsiveness on the comparison page.
        
I deployed my website to GitHub pages, with the website working on a live, publicly accessible URL as a result.

        1. I used a CSS media query for the navigation menu.
        2. I MADE sure THE website works at all window widths/sizes.
        
I took some liberty in the visual aspects, but kept the core functionality the same.


Bonuses

    Used a different dataset! The requirements above still holds, but make it your own.
        1. I UseD a bootstrap theme to customize MY website. 
        2. I useD a tool like Bootswatch. Make it look snazzy, give it some attitude.
            If using this, be sure you also meet all of the requirements listed above.
            
    Added extra visualizations! The more comparisons the better, right?
    Used meaningful glyphicons next to links in the header.
    Had visualization navigation on every visualizations page with an active state. See the screenshots below.