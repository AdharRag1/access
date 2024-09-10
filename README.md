Accessibility Widget Documentation
Overview
The Accessibility Widget is a versatile tool designed to enhance the user experience on websites by providing a range of accessibility features. This widget offers functionalities to adjust text size, color schemes, contrast, and other visual and auditory elements to accommodate diverse user needs.
Project Details
Languages and Libraries Used:
HTML: For structuring the content and layout of the widget.
CSS: For styling the widget, including layout, color schemes, and animations.
JavaScript: For implementing the widget's interactive functionalities.
Google Fonts: To include custom fonts (Inter and Material Icons) for improved readability and design.
External Resources
Google Fonts:
Inter Font
Material Icons
Material Symbols
Features
⦁	Font Size Adjustment
Increase or decrease the font size of the content.
Implemented via adjustFontSize() function in JavaScript.
⦁	Text and Background Color Customization
Allows users to change text, title, and background colors.
Color picker options are provided for user convenience.
Implemented via changeTextColor(), changeTitleColor(), and changeBackgroundColor() functions in JavaScript.
⦁	High Contrast Mode
Toggles between normal and high-contrast modes for better readability.
Implemented via toggleContrast() function in JavaScript.
⦁	Reading Ruler
Provides a visual ruler to help users follow along with the text.
Activated and updated via toggleReadingRuler() and updateRulerPosition() functions in JavaScript.
⦁	Text Alignment and Spacing
Options to align text and adjust letter spacing and line height.
Implemented via alignText(), toggleLetterSpacing(), and toggleLineHeight() functions in JavaScript.
⦁	Dyslexia-Friendly Font
Option to switch to a dyslexia-friendly font for improved readability.
Implemented via toggleDyslexiaFont() function in JavaScript.
⦁	Highlighting Headings and Links
Allows users to highlight headings and links for better visibility.
Implemented via toggleHighlightHeadings() and toggleHighlightLinks() functions in JavaScript.
⦁	Large Cursor
Provides an option to enable a larger cursor for better visibility.
Implemented via enableBigCursor() function in JavaScript.
⦁	Screen Reader
Activates or deactivates a screen reader to read out the content.
Implemented via toggleScreenReader(), startScreenReader(), and stopScreenReader() functions in JavaScript.
⦁	Image Visibility
Toggles the visibility of images on the page.
Implemented via toggleImages() function in JavaScript.
⦁	Content Scaling
Adjusts the scale of the entire content for better readability.
Implemented via scaleContent() function in JavaScript.
⦁	Saturation and Monochrome Modes
Options to adjust color saturation or switch to monochrome mode.
Implemented via toggleHighSaturation(), toggleLowSaturation(), and toggleMonochrome() functions in JavaScript.
Usage
To integrate the widget into a website, include the provided HTML, CSS, and JavaScript files into your project. Ensure that the external CSS libraries are linked correctly in the <head> section of your HTML. The widget's functionalities can be accessed through the user interface provided by the HTML structure.

HTML Integration
Embed the provided HTML code into your webpage where you want the widget to appear. Ensure that all required IDs and classes are used as referenced in the JavaScript.
CSS Integration
Include the provided CSS code in your project's stylesheet or directly within a <style> tag in the HTML <head> section. Ensure that the styles are correctly applied to the elements of the widget.

JavaScript Integration
Include the provided JavaScript code in a <script> tag at the end of your HTML <body> section or in an external JavaScript file linked to your HTML. Ensure that all functions and event listeners are correctly set up to handle user interactions.

Improvement Ideas
Tooltip Support: Add tooltips or help texts for each button to provide users with more information on what each feature does.
Customizable Shortcuts: Allow users to customize keyboard shortcuts for accessibility features to improve efficiency.
Language Options: Provide translations for the accessibility menu and features to support users who speak different languages.
Help Center: Create a help center or FAQ section within the widget to provide users with answers to common questions and troubleshooting tips.
Customizable Themes: Allow users to select from a range of themes or create their own to better suit their visual preferences.
Content Highlighting: Add options for users to highlight specific types of content, such as keywords or important phrases, which can aid in better comprehension.

Working on 
⦁	Adhd focus mode 

Conclusion
This Accessibility Widget aims to provide a comprehensive solution for improving website accessibility. By integrating this widget, website administrators can offer a more inclusive experience to users with various needs, ensuring better usability and compliance with accessibility standards.
## Preview
![1](https://github.com/swethatheresa/Accessibility-Widget/assets/83918978/a8be9d0d-ae17-49fd-be72-72a74a00efeb)
