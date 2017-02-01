.plan file for andres.plashal
--
Taken inspiration from Carmack, I'd like to document the happenings of this project. What i thought would be a quick turnaround progressed into a whirl-wind exorcise in [murphy's law](https://en.wikipedia.org/wiki/Murphy's_law). Crashed hdds, Monitors falling off mounts, a forced windows upgrade and a new baby on the way. I've tried my best to correct and compensate and we're still kicking over here, pushing out updates on the daily. With a need to update and migrate my work to a standardized development environment, I begin with [anders.plashal.com](http://andres.plashal.com).  
	
	2/1/17 4:20:54 PM: 
	- Need to convert site colors into #websafe standard notation format (.css file)
	- Add image block color to designations in this .md (for eyedropper ease)
	- Continue to add to the TOC/ Complete hyperlinks

Table of Contents
--
- [Layout and Design](#layout-and-design)
 - [Background Options](#background-options)
- [Typography](#typography)
 - [Body and Content](#body-and-content)
 - [Headings](#headings)
 - [Site Links](#site-links)
- [Buttons](#buttons)
 - [Buttons Colors](#buttons-colors)
 - [Hover Colors](#button-hover-colors)
- [Header](#header)
 - [Navbar](#navbar)
 - Logo – Text
 - Logo – Image
 - Logo – Alignment
 - Links – Text
 - Links – Alignment


References & Resources
--

**Useful tools**
- [GitHub Flavored Markdown Reference ](https://help.github.com/articles/basic-writing-and-formatting-syntax/)
- [CSS Color Converter](http://maettig.com/?page=PHP/CSS_Color_Converter)
- [Quick Type Change Case](https://convertcase.net/)
- [Wikipedia: Web Colors](https://en.wikipedia.org/wiki/Web_colors)


**Color Calculations**
- **To calculate the percentage values** (0% to 100%), the integer values (0 to 255) are divided by 2.55 and then rounded to whole numbers.
- **To calculate the short hex values** (0 to 9 and A to F), the integer values (0 to 255) are divided by 17 and then rounded to whole numbers.
- **To calculate the web-safe values** (0, 3, 6, 9, C and F), the integer values (0 to 255) are divided by 51, rounded to whole numbers and the multiplied with 3.


## Layout and Design ##
Note: "Site Width" is the percentage of the screen the site should take up while think of "Site Max Width" as an upper limit that the site will *never* be wider than. "Content Layout" has to do with the site's global setup of having a sidebar or not.

- **Site Layout**: Fullwidth
- **Content Layout**: Content Left, Sidebar Right
- **Site Max Width**: 1200px
- **Site Width**: 80%
- **Sidebar Width**: 250px

#### Background Options ####
Note: The "Background Pattern" setting will override the "Background Color" unless the image used is transparent, and the "Background Image" option will take precedence over both. The "Background Image Fade (ms)" option allows to set a time in milliseconds for an image to fade in. value of "0" disables. 

- **Background Color**: rgb(255, 255, 255)
 - Hex3: #FFF
- Background Pattern: none
- Background Image: none
- Background Image Fade (ms): 750

## Typography ##
Note: Global typography options for the body copy and headings, while more specific typography options for elements like your navbar are found grouped with that element section to make customization more streamlined. If using Google Fonts, I can also enable custom subsets here for expanded character sets.

Google Fonts Subsets: none

#### Body and Content ####
INFO: "Body Font Size (px)" will affect the sizing of all copy outside of a post or page content area. "Content Font Size (px)" will affect the sizing of all copy inside a post or page content area. Headings are set with percentages and sized proportionally to these settings.

- **Body Font**: [Lato](https://fonts.google.com/specimen/Lato) (Google)
- **Body Font Color**: rgb(0, 0, 0)
- **Body Font Size** 17px
- **Content Font Size**: 17px
- **Body Font Weight**: 400 – Regular

#### Headings ####
Note: The letter spacing controls each heading level and will only affect that heading if it does not have a "looks like" class or if the "looks like" class matches that level. example, an `<h1>` with no modifier class, the `<h1>` slider will affect that heading. However, if the `<h1>` has an `.h2` modifier class, then the `<h2>` slider will take over as it is supposed to appear as an `<h2>`.

- **Headings Font**:[Lato](https://fonts.google.com/specimen/Lato) (Google)
- **Headings Font Color**: rgb(0, 0, 0)
 - Hex3: #000
- **Headings Font Weight**: 700 – Bold
- **h1 Letter Spacing** (em) -0.035
- **h2 Letter Spacing** (em) -0.035
- **h3 Letter Spacing** (em) -0.035
- **h4 Letter Spacing** (em) -0.035
- **h5 Letter Spacing** (em) -0.035
- **h6 Letter Spacing** (em) -0.035


- Text-Transform: none
>Prefer 'Title Case'

#### Site Links ####
Note: Site link colors are also used as accents for various elements throughout the site, (make sure I select something i enjoy and keep an eye out for how it affects the rest of the design.)

- **Site Links**: rgb(0, 135, 216)
 - Hex6: #0087D8
 - Hex3: #08D
 - **WebSafe**: #09C
 - %: rgb(0%,53%,85%)


- **Site Links Hover**: rgb(255, 0, 90)
 - Hex6: #FF005A
 - Hex3: #F05
 - **WebSafe**: #F06
 - %: rgb(100%,0%,35%)
 
## Buttons ##
- **Button Style**: Flat
- **Button Shape**: Square

####Buttons Colors ####
- **Button Text**: rgb(255, 255, 255)
 - Hex3: #FFF
- **Button Background**: rgb(0, 70, 140)
 - Hex6: #00468C
 - Hex3: #048
 - **WebSafe**: #039
 - %: rgb(0%,27%,55%)
- **Button Border**: rgb(255, 255, 255)
 - Hex3: #FFF

####Buttons Hover Colors ####
- **Button Text**: rgb(255, 255, 255)
 - Hex3: #FFF
- **Button Background**: rgb(255, 0, 90)
 - Hex6: #FF005A
 - Hex3: #F05
 - **WebSafe**: #F06
 - %: rgb(100%,0%,35%)
- **Button Border**: rgb(255, 255, 255)
 - Hex3: #FFF


## Header ##
Navbar, Logo and Navigation elements

#### Navbar ####
Note: "Navbar Top Height (px)" must be set even when using "Fixed Left" or "Fixed Right" positioning because on tablet and mobile devices, the menu is pushed to the top.

- **Layout**: Inline
- **Navbar Position**: Fixed Top
- **Navbar Top Height **(px): 80px

#### Logo – Text ####
The logo will show up as text by default. Alternately, if using an image, upload and the code will automatically switch over.

- Logo Font: [Lato](https://fonts.google.com/specimen/Lato) (Google)
- Logo Font Color: rgb(255, 255, 255)
- Logo Font Size (px): none
- Logo Font Weight: none
- Logo Letter Spacing (em): none
- Uppercase?: none/ no

#### Logo – Image ####
Note: To make logo retina ready, enter in the width of uploaded image and use the processor code to take care of all the calculations. If i want the logo to stay the original size, then leave the field blank.

- **Logo Upload**: andresfoxplashal.logo_yellow.svg
- **Logo Width (px)**: 425px

#### Logo – Alignment ####
Note: Use the following controls to vertically align the logo. Make sure to adjust top alignment even if the navbar is `fixed` to a side as it will reformat to the top on smaller screens (this control will be hidden if side navigation position is not implemented).

- **Navbar Top Logo Alignment (px)**: 20px

#### Navbar Links – Text ####

- **Navbar Font**: [Lato](https://fonts.google.com/specimen/Lato) (Google)
- **Navbar Links Color**: rgb(255, 255, 255)
 - Hex3: #FFF
- **Navbar Links Hover Color**: rgb(255, 228, 0)
 - Hex6: #FFE400
 - Hex3: #FD0
 - **WebSafe**: #FC0
 - %: rgb(100%,89%,0%)
- **Navbar Links Accent Color**: rgb(255,0,90)
 - Hex6: #FF005A
 - Hex3: #F05
 - **WebSafe**: #F06
 - %: rgb(100%,0%,35%)
- **Navbar Font Size** (px): 17px
- **Navbar Font Weight**: 700 – Bold
- **Navbar Letter Spacing (em)**: 0.048
- **Navbar Text-Transform**: Uppercase


#### Links – Alignment ####
Note: the vertical alignment of links for both top and side navbar positions as well as the vertical spacing between links for top navbar positions with the `Navbar Top Link Spacing`.

- **Navbar Top Link Alignment** (px): 30
- **Navbar Top Link Spacing** (px): 10

## Footer ##

## Blog ##

## Portfolio ##

## Social ##

## Menus ##