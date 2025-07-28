 Build a Personal Portfolio Webpage
mandatory

Objective
Create a personal portfolio webpage that effectively showcases your skills, projects, and contact information.

Detailed Requirements
Create a Github repository named My_First_Portfolio if not already created and within it create a directory called portfolio

HTML File:

Create an HTML file within the portfolio directory and name your HTML file index.html.
Page Structure and Semantic HTML:

The document must start with the <!DOCTYPE html> declaration.
Use <html lang="en"> to define the document language.
The <head> section must contain <meta charset="utf-8"> and a <title> element with your full name followed by - Personal Portfolio (e.g., John Doe - Personal Portfolio).
The body of the document must include the following semantic HTML5 elements in order: <header>, <nav>, <section>, <article>, and <footer>.
Header:

The <header> must contain an <h1> element with your name.
Include a <p> tag beneath the <h1> with a brief tagline or professional statement.
Navigation Bar (<nav>):

Include a list of links (<ul> containing <li> elements) that allows navigation to the different sections of the webpage: Introduction, Projects, About Me, and Contact.
Each list item must contain an <a> tag with the href attribute pointing to the corresponding section ID (e.g., href="#projects" for the Projects section).
Content Sections:

Introduction Section (<section id="introduction">): Include an <h2> heading titled “Introduction” and a paragraph <p> describing yourself.
Projects Section (<section id="projects">): Use an <h2> heading titled “Projects”. Each project must be wrapped in <article> tags with a class of “project”. Each <article> must contain an <h3> for the project title, a <p> for the description, and an <a> tag linking to the project with target="_blank".
About Me Section (<section id="about">): Include an <h2> heading titled “About Me” and paragraphs or lists describing your background, skills, or hobbies.
Contact Section (<section id="contact">): Use an <h2> heading titled “Contact” and provide an email link using <a href="mailto:your.email@example.com"> and links to your LinkedIn and GitHub profiles, ensuring these links open in a new tab using target="_blank".
Footer:

The <footer> must contain a <p> element with copyright information (e.g., &copy; 2024 Your Name).
Repo:

GitHub repository: My_First_Portfolio
Directory: portfolio
File: index.html