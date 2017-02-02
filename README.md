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
 - [Logo – Text](#logo-text)
 - [Logo – Image](#logo-image)
 - [Logo – Alignment](#logo-alignment)
 - [Navbar Links – Text](#navbar-links-text)
 - [Navbar Links - Alignment](#navbar-links-alignment)
 - Mobile Button


- Footer
- Blog
- Portfolio
- [Social](#social)
 - Media Accounts
 - Open Graph
 - Social Fallback Image
- [Site Icons](#site-icons)
- Menus


> **Bold** selectors denotes items of importance

## Layout and Design ##
Note: "Site Width" is the percentage of the screen the site should take up while think of "Site Max Width" as an upper limit that the site will *never* be wider than. "Content Layout" has to do with the site's global setup of having a sidebar or not.

- Site Layout: Fullwidth
- **Site Max Width** (px): 1200
- **Site Width** (%): 80
- Content Layout: Content Left, Sidebar Right
- **Content Width** (%): 70

#### BACKGROUND OPTIONS ####
Note: The "Background Pattern" setting will override the "Background Color" unless the image used is transparent, and the "Background Image" option will take precedence over both. The "Background Image Fade (ms)" option allows to set a time in milliseconds for an image to fade in. value of "0" disables.

- **Background Color**: rgb(255,255,255)
- Background Pattern: none
- Background Image: none
- Background Image Fade (ms): 750

## Typography ##
Note: Global typography options for the body copy and headings, while more specific typography options for elements like your navbar are found grouped with that element section to make customization more streamlined. If using Google Fonts, I can also enable custom subsets here for expanded character sets.

Google Fonts Subsets: null/ off

#### BODY AND CONTENT ####
INFO: "Body Font Size (px)" will affect the sizing of all copy outside of a post or page content area. "Content Font Size (px)" will affect the sizing of all copy inside a post or page content area. Headings are set with percentages and sized proportionally to these settings.

- **Body Font**: [Open Sans](https://fonts.google.com/specimen/Open+Sans) (Google)
- **Body Font Color**: rgb(9,7,7)
 - hex6: #090707
 - hex3: #100
- **Body Font Size** (px): 16
- **Content Font Size** (px): 16
- **Body Font Weight**: 400 – Regular

#### HEADINGS ####
Note: The letter spacing controls each heading level and will only affect that heading if it does not have a "looks like" class or if the "looks like" class matches that level. example, an `<h1>` with no modifier class, the `<h1>` slider will affect that heading. However, if the `<h1>` has an `.h2` modifier class, then the `<h2>` slider will take over as it is supposed to appear as an `<h2>`.

- **Headings Font**: [Roboto](https://fonts.google.com/specimen/Roboto) (Google)
- **Headings Font Color**: rgb(39, 39, 39)
 - hex6: #272727
- **Headings Font Weight**: 400 – Regular
- h1 Letter Spacing (em): -0.035
- h2 Letter Spacing (em): -0.035
- h3 Letter Spacing (em): -0.035
- h4 Letter Spacing (em): -0.035
- h5 Letter Spacing (em): -0.035
- h6 Letter Spacing (em): -0.035
- Text-Transform: none
- Widget Icons: null/ off


#### SITE LINKS ####
Note: Site link colors are also used as accents for various elements throughout the site, (make sure I select something i enjoy and keep an eye out for how it affects the rest of the design.)

- **Site Links**: rgb(0, 135, 216)
 - Hex6: #0087D8
- **Site Links Hover**: rgb(255, 0, 90)
 - Hex6: #FF005A
- Highlight Color Dark: :heavy_exclamation_mark:
- Highlight Color Light: :heavy_exclamation_mark:

## Buttons ##
- Button Style: Flat
- Button Shape: Square

#### BUTTONS COLORS ####
- Button Text: rgb(255, 255, 255)
- Button Background: rgb(0, 70, 140)
 - Hex6: #00468C
- Button Border: rgb(255, 255, 255)

#### HOVER COLORS ####
- Button Text: rgb(255, 255, 255)
- Button Background: rgb(255, 0, 90)
 - Hex6: #FF005A
- Button Border: rgb(255, 255, 255)

## Header ##
Navbar, Logo and Navigation elements

#### NAVBAR ####
Note: "Navbar Top Height (px)" must be set even when using "Fixed Left" or "Fixed Right" positioning because on tablet and mobile devices, the menu is pushed to the top.

- Layout: Inline
- Navbar Position: Static Top
- **Navbar Top Height** (px): 90

#### LOGO – TEXT ####
The logo will show up as text by default. Alternately, if using an image, upload and the code will automatically switch over.

- Logo Font: [Open Sans](https://fonts.google.com/specimen/Open+Sans) (Google)
- Logo Font Color: rgb(255, 255, 255)
- Logo Font Size (px): 40
- Logo Font Weight: 700 – Bold
- Logo Letter Spacing (em): -0.070
- Logo Text-transform: none

#### LOGO – IMAGE ####
Note: To make logo retina ready, enter in the width of uploaded image and use the processor code to take care of all the calculations. If i want the logo to stay the original size, then leave the field blank.

- Logo Upload: logo-plashal.svg
- Logo Width (px): 200

#### LOGO – ALIGNMENT ####
Note: Use the following controls to vertically align the logo. Make sure to adjust top alignment even if the navbar is `fixed` to a side as it will reformat to the top on smaller screens (this control will be hidden if side navigation position is not implemented).

- **Navbar Top Logo Alignment (px)**: 22

#### NAVBAR LINKS – TEXT ####

- Navbar Font: [Roboto](https://fonts.google.com/specimen/Roboto) (Google)
- Navbar Links Color**: rgb(255, 255, 255)
- Navbar Links Hover Color: rgb(255, 255, 255)
- Navbar Links Accent Color: :heavy_exclamation_mark:
- **Navbar Font Size** (px): 19
- Navbar Font Weight: 500 – Medium
- Navbar Letter Spacing (em): 0.09
- Navbar Text-Transform: none

#### NAVBAR LINKS – ALIGNMENT ####
Note: the vertical alignment of links for both top and side navbar positions as well as the vertical spacing between links for top navbar positions with the `Navbar Top Link Spacing`.

- **Navbar Top Link Alignment** (px): 37
- **Navbar Top Link Spacing** (px): 25

#### MOBILE BUTTON ####
The vertical alignment and size of the mobile button that appears on smaller screens.

- Mobile Navbar Button Size (px): 24
- Mobile Navbar Button Alignment (px): 20

## Footer ##
	need to populate

## Blog ##
- Columns: 3

#### CONTENT ####
Note: The "Enable Full Post Content on Index" option will allow the entire contents of the posts to be shown on the post index pages for all stacks. Deselecting will allow to set the length of the excerpt.

- Post Meta: off 
- Excerpt Length: 60 words



## Portfolio ##
	need to populate

## Social ##

#### MEDIA ACCOUNTS ####
- Facebook: https://www.facebook.com/andres.plashal
- Twitter: https://twitter.com/andresplashal
- LinkedIn: https://www.linkedin.com/in/andresplashal
- GitHub: https://github.com/plashal
- Slack: https://plashal.slack.com/
- Skype: live:plashal

#### SOCIAL MEDIA - COLORS ####
- **Facebook**:
 - Primary: Blue
   - rgb(59, 89, 152)
   - HEX: #3B5998


- **Twitter**:
 - Primary: Blue
   - rgb(29, 161, 242)
   - HEX: #1DA1F2
 - Secondary: Black
   - rgb(20,23, 26)
   - HEX: #14171A


- **LinkedIn**: 
 - Primary: Blue
   - rgb(0, 119, 181)
   - HEX: #10077B5
 - Secondary: Dark Gray
   - rgb(49, 51, 53)
   - HEX: #31335


- **GitHub** (as of: 08/20/2015 v.2.3.3)
 - Primary: Dark Gray
   - rgb(51, 51, 51)
   - HEX: #333333
 - Secondary: Blue
   - rgb(64, 120, 192)
   - HEX: #4078c0


#### BRANDING GUIDELINES ####
- Facebook:
 - https://en.facebookbrand.com/, 
 - https://developers.facebook.com/docs/apps/review/branding
- Twitter:
 - https://brand.twitter.com/
- LinkedIn
 - https://brand.linkedin.com/
- GitHub
 - https://github.com/logos
 - https://github.com/styleguide
 - http://primercss.io/colors/	
- Slack  
 - https://slack.com/brand-guidelines
 - https://brandfolder.com/slack


#### OPEN GRAPH ####
Note: This will output standard Open Graph tags for the content. If i decide to employ another solution for this, I can disable Open Graph tag output here.

- Open Graph: null/ Off

#### SOCIAL FALLBACK IMAGE ####
Note: The "Social Fallback Image" is used with various social media network APIs. It is used as a default on pages that do not have a featured image set. I don't have to specify one; however, it is recommended if I'm using the native Open Graph implementation to set this option, entry sharing, et cetera.

- Social Fallback Image: none/ No image

## Site Icons ##
Note: touch icons for mobile devices and tile icon for the Windows 8/10 Metro interfaces are set here. If an image is not set, nothing will be output for that particular icon type. When setting the path to the favicon, make sure to use ".ico" extension. A 152x152 PNG should be used for the touch icon, and a 144x144 PNG should be used for the tile icon. The color set for the tile icon will be used behind the image.

- Favicon: /favicon.ico
- Touch Icon (iOS and Android): null/ No image
- Tile Icon (Microsoft): null/ No image
- Tile Icon Background Color: rgb(255, 255, 255)

## Menus ##
Note: using conditional menus to redirect when needed. 
- index-onepage: Primary
	- About – 
	- Services – 
	- Blog – 
	- Contact – 


- index-sitewide
	- About – 
	- Services – 
	- Blog – 
	- Contact – 