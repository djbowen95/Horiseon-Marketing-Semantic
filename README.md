# Marketing Agency - Code Refactor Project
This is a code refactor of a single webpage for the marketing agency Horiseon. The refactor should look to improve accessibility requirements

Here is a step-by-step outline of the modifications I have made to reach these requirements, explaining each commit I made to the repository and the process I went through to reach the finished product.

As this was challenge set to test my understanding not only of HTML and basic CSS but also of Git and the command line, I have talked through the GitHub process and a few of my initial mistakes. This is for personal reference and to justify a few of the initial commits.   

### 0: Initial Set Up of Repository
Before starting, I created a repository on GitHub and moved the core files - the html index file and linked css style sheet - into it. Once I pushed these into the repository, I began to edit the files - but realised that I had not correctly indexed the two files and the page would not display correctly.

I made too further commits to solve this: first, I imported the image files and uploaded those to the folder. Secondly, I moved the style.css file to its own css folder, so that it was where the HTML expected it to be. I chose to do this rather than modify the pathway in the HTML because I thought it would be better practice to keep the source pathway/the relation between the two files the same as it was in the given broken code.

### 1: Semantic HTML
#### 1A: Header and Navigation
The first change I made to the HTML file was to change the first two /'<div>' tags to '<header>' and '<nav>' tags respectively. I made corrosponding changes in the CSS file so that the formatting would remain the same: changing ".header" to "header" and ".nav" to "nav" at every occurance. I checked this in the Live Server and then committed these changes.

#### 1B: Central Image
The next set of changes centered on the central image to the webpage. This element was coded as a single line '<div>' in the broken code, with the image itself included as part of the css for this file. I decided not only to redefine this element as a figure, but to move the image from the CSS into the HTML file: so that I could improve accessibility to screen readers, and provide alternative text. The '<div>' was initially refered to by the class 'hero' - but I instead formatted my new image under the class 'central-image'; making it more obvious to other developers what the element being coded was. 

### X. Additional Notes
The first few commits didn't follow a consistent rule in terms of tense. I googled and tried to change to an imperative present tense ('as though you are telling the code what to do') from the 7th commit onwards.

Next I worked on the central image on the webpage. For this element, I changed a '<div>' that was defined in the css into a '<figure>' element containing an image. The image was originally coded into the css file, as a background for this '<div>' element. I chose

The div element had contained the image in the css file as a background , but I chose to code this image into the HTML: allowing me to 


### Breakdown of tasks:
1: Read through and understand the HTML and CSS files.
2: Add semantic HTML tags; read up on semantic HTML.
3: Put all elements of HTML file in a logical structure.
4: Make sure all images and icons have alt text/alt attributes.
5: Make sure all headings are in sequential order.
6: Give the HTML a short, descriptive title*. 
7: Review all submission criteria, make sure website + upload fully fits the given brief. 
