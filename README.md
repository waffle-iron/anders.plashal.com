## Table of Contents ##
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
 - [Logo – Text](#logo--text)
 - [Logo – Image](#logo--image)
 - [Logo – Alignment](#logo--alignment)
 - [Navbar Links – Text](#navbar-links--text)
 - [Navbar Links – Alignment](#navbar-links--alignment)
- Footer
- Blog
- Portfolio
- [Social](#social)
 - Open Graph
 - Social Fallback Image
- [Site Icons](#site-icons)
- Menus

> **Bold** variables denotes items of interest

#### Renew Colors/ Unsorted ####

- Topbar Background:
- Logobar Background:
- **Navbar Background**: rgb(231,29,54)
- Mobile Button Color:
- Mobile Button Background:
- Mobile Button Background Hover:
- **Footer Background**: rgb(51,51,51)

---

## Layout and Design ##
Note: "Site Width" is the percentage of the screen the site should take up while think of "Site Max Width" as an upper limit that the site will *never* be wider than. "Content Layout" has to do with the site's global setup of having a sidebar or not.

- **Site Layout**: Fullwidth
- **Content Layout**: Content Left, Sidebar Right
- **Site Max Width**: 1200px
- **Content Width** (%): 70
- **Site Width** (%): 80%
- 
#### Background Options ####
Note: The "Background Pattern" setting will override the "Background Color" unless the image used is transparent, and the "Background Image" option will take precedence over both. The "Background Image Fade (ms)" option allows to set a time in milliseconds for an image to fade in. value of "0" disables. 

- **Background Color**: rgb(204,204,204)
 - Hex3: #CCC
- Background Pattern: none
- Background Image: none
- Background Image Fade (ms): 750

## Typography ##
Note: Global typography options for the body copy and headings, while more specific typography options for elements like your navbar are found grouped with that element section to make customization more streamlined. If using Google Fonts, I can also enable custom subsets here for expanded character sets.

Google Fonts Subsets: null/ off

#### Body and Content ####
INFO: "Body Font Size (px)" will affect the sizing of all copy outside of a post or page content area. "Content Font Size (px)" will affect the sizing of all copy inside a post or page content area. Headings are set with percentages and sized proportionally to these settings.

- **Body Font**: [Roboto Slab](https://fonts.google.com/specimen/Roboto+Slab) (Google)
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
- **Navbar Top Height** (px): 80px

#### Logo – Text ####
The logo will show up as text by default. Alternately, if using an image, upload and the code will automatically switch over.

- Logo Font: [Lato](https://fonts.google.com/specimen/Lato) (Google)
- Logo Font Color: rgb(255, 255, 255)
- Logo Font Size (px): null
- Logo Font Weight: null
- Logo Letter Spacing (em): null
- Logo Text-transform/ Uppercase: null/ no

#### Logo – Image ####
Note: To make logo retina ready, enter in the width of uploaded image and use the processor code to take care of all the calculations. If i want the logo to stay the original size, then leave the field blank.

- **Logo Upload**: plashal-logo.svg
- **Logo Width** (px): 200

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

#### Navbar Links – Alignment ####
Note: the vertical alignment of links for both top and side navbar positions as well as the vertical spacing between links for top navbar positions with the `Navbar Top Link Spacing`.

- **Navbar Top Link Alignment** (px): 30
- **Navbar Top Link Spacing** (px): 10

## Footer ##
- **Excerpt Length**: 60 words

## Blog ##

## Portfolio ##

## Social ##

#### Open Graph ####
Note: This will output standard Open Graph tags for the content. If i decide to employ another solution for this, I can disable Open Graph tag output here. 

- Open Graph: null/ Off

#### Social Fallback Image  ####
Note: The "Social Fallback Image" is used with various social media network APIs. It is used as a default on pages that do not have a featured image set. I don't have to specify one; however, it is recommended if I'm using the native Open Graph implementation to set this option, entry sharing, et cetera.

- Social Fallback Image: null/ No image

## Site Icons ##
Note: touch icons for mobile devices and tile icon for the Windows 8/10 Metro interfaces are set in this section. If an image is not set, nothing will be output for that particular icon type. When setting the path to the favicon, make sure to use the ".ico" format. A 152x152 PNG should be used for the touch icon, and a 144x144 PNG should be used for the tile icon. The color set for the tile icon will be used behind the image.

- **Favicon**: /favicon.ico
- Touch Icon (iOS and Android): null/ No image
- Tile Icon (Microsoft): null/ No image
- Tile Icon Background Color: rgb(255, 255, 255)

## Menus ##