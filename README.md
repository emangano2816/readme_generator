# Readme Generator

## URLs
1 GitHub Repository: https://github.com/emangano2816/readme_generator

## User Story
```
AS A developer
I WANT a README generator
SO THAT I can quickly create a professional README for a new project
```

## Acceptance Criteria
```
GIVEN a command-line application that accepts user input
WHEN I am prompted for information about my application repository
THEN a high-quality, professional README.md is generated with the title of my project and sections entitled Description, Table of Contents, Installation, Usage, License, Contributing, Tests, and Questions
WHEN I enter my project title
THEN this is displayed as the title of the README
WHEN I enter a description, installation instructions, usage information, contribution guidelines, and test instructions
THEN this information is added to the sections of the README entitled Description, Installation, Usage, Contributing, and Tests
WHEN I choose a license for my application from a list of options
THEN a badge for that license is added near the top of the README and a notice is added to the section of the README entitled License that explains which license the application is covered under
WHEN I enter my GitHub username
THEN this is added to the section of the README entitled Questions, with a link to my GitHub profile
WHEN I enter my email address
THEN this is added to the section of the README entitled Questions, with instructions on how to reach me with additional questions
WHEN I click on the links in the Table of Contents
THEN I am taken to the corresponding section of the README

```
## Achieving Acceptance Criteria
1. Upon invoking the application through the terminal, the user will be prompted to respond to questions about the content to be included in the generated README. Once all questions are answered a README.md is generated for the user.  The file follows mark-down formatting and is high-quality.
2. The title of the project is displayed as the first header in the generated README file.
3. The user provided description, installation instructions, usage information, contribution guildelines, and test intructions are displayed in the sections of the README titled Description, Installation, Usage, Contributing, and Tests.
4. The user is given a choice of 10 different licenses.  A badge of the selected license is displayed under the title of the project.  Additionally, under the section titled License, a sentence explaining which license the application is covered under is included.
5. The user's GitHub username is added to the Questions? section as a link to their GitHub profile.
6. The user's email address is also added to the Questions section.
7. Each section of the README (with the exception of the Description) is included in the TOC.  The links within the TOC take the user to the specified section of the README.


