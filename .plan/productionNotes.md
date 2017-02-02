.plan file for andres.plashal
--
Taken inspiration from Carmack, I'd like to document the happenings of this project. What i thought would be a quick turnaround progressed into a whirl-wind exorcise in [murphy's law](https://en.wikipedia.org/wiki/Murphy's_law). Crashed hdds, Monitors falling off mounts, a forced windows upgrade and a new baby on the way. I've tried my best to correct and compensate and we're still kicking over here, pushing out updates on the daily. With a need to update and migrate my work to a standardized development environment, I begin with [anders.plashal.com](http://andres.plashal.com).

	Wed. Feb 01, 2017- 4:20 PM:
	- Need to convert site colors into #websafe standard notation format (.css file)
	- Add image block color to designations in this .md (for eyedropper ease)
	- Continue to add to the TOC/ Complete hyperlinks


References & Resources
--
**Code & Markdown**
- [GitHub Flavored Markdown Reference ](https://help.github.com/articles/basic-writing-and-formatting-syntax/)

**Type & Measurement**
- [Google Fonts](https://fonts.google.com/)
- [Quick Type Change Case](https://convertcase.net/)
- [Approximate Conversions: Points> Pixels> Ems> %](http://reeddesign.co.uk/test/points-pixels.html)
- [CSS Font-Size: em vs. px vs. pt vs. percent](http://kyleschaeffer.com/development/css-font-size-em-vs-px-vs-pt-vs/)
 Meet the Units: **1em = 12pt = 16px = 100%**
 - **“Ems” (em)**: The “em” is a scalable unit that is used in web document media. An em is equal to the current font-size, for instance, if the font-size of the document is 12pt, 1em is equal to 12pt. Ems are scalable in nature, so 2em would equal 24pt, .5em would equal 6pt, etc. Ems are becoming increasingly popular in web documents due to scalability and their mobile-device-friendly nature.
 - **Pixels (px)**: Pixels are fixed-size units that are used in screen media (i.e. to be read on the computer screen). One pixel is equal to one dot on the computer screen (the smallest division of your screen’s resolution). Many web designers use pixel units in web documents in order to produce a pixel-perfect representation of their site as it is rendered in the browser. One problem with the pixel unit is that it does not scale upward for visually-impaired readers or downward to fit mobile devices.
 - **Points (pt)**: Points are traditionally used in print media (anything that is to be printed on paper, etc.). One point is equal to 1/72 of an inch. Points are much like pixels, in that they are fixed-size units and cannot scale in size.
 - **Percent (%)**: The percent unit is much like the “em” unit, save for a few fundamental differences. First and foremost, the current font-size is equal to 100% (i.e. 12pt = 100%). While using the percent unit, your text remains fully scalable for mobile devices and for accessibility.



**Color Related**
- [CSS Color Converter](http://maettig.com/?page=PHP/CSS_Color_Converter)
- [Wikipedia: Web Colors](https://en.wikipedia.org/wiki/Web_colors)
 Color Calculations
 - **To calculate the percentage values** (0% to 100%), the integer values (0 to 255) are divided by 2.55 and then rounded to whole numbers.
 - **To calculate the short hex values** (0 to 9 and A to F), the integer values (0 to 255) are divided by 17 and then rounded to whole numbers.
 - **To calculate the web-safe values** (0, 3, 6, 9, C and F), the integer values (0 to 255) are divided by 51, rounded to whole numbers and the multiplied with 3.