# Lab Title
## HTML and CSS Fundamentals Using Selectors

## 1. Introduction
This lab assignment is designed to strengthen students' understanding of basic HTML
structure and Cascading Style Sheets (CSS) up to selectors. The assignment focuses on
creating a structured web page using semantic HTML elements and applying styles using
different types of CSS selectors. No advanced CSS techniques or scripting languages are
included in this lab.

## 2. Learning Objectives
Upon successful completion of this lab, students will be able to:
- Create a well-structured HTML document
- Use semantic HTML elements correctly
- Apply CSS using element, class, ID, group, and descendant selectors
- Maintain separation between content and presentation
- Inspect and analyze applied CSS using browser developer tools

## 3. Prerequisites
Students must have prior knowledge of:
- Basic HTML tags and attributes
- HTML document structure
- Introduction to CSS
- CSS selectors up to element, class, ID, group, and descendant selectors

## 4. Lab Scenario
You are assigned to design a Student Profile Web Page for an academic institution. The
webpage should present student information, enrolled courses, hobbies, and contact details.
The webpage must be developed using only HTML and external CSS, focusing strictly on
selector usage.
Advanced CSS features such as Flexbox, Grid, animations, media queries, and JavaScript
are strictly prohibited.

## 5. Tools and Technologies
- Code Editor (Visual Studio Code or equivalent)
- Web Browser (Google Chrome or Mozilla Firefox)

## 6. Folder Structure
Students must create the following directory structure:
```
student-profile/
├── index.html
└── style.css
```

## 7. Task Description

### 7.1 HTML Structure Requirements
Create an HTML file named index.html that includes the following sections:

#### Header Section
- College Name using a level-one heading
- Page title using a level-two heading

#### Student Information Section
- Student Name
- Roll Number
- Program
- Semester

#### Course Information Section
- A list of at least five enrolled courses using ordered or unordered lists

#### Hobbies Section
- A list of at least four hobbies

#### Contact Information Section
- Email address
- Phone number

#### Footer Section
- Copyright information

Semantic elements such as header, main, section, and footer should be used wherever
appropriate.

### 7.2 CSS Styling Requirements
Create an external CSS file named style.css and apply the following styles:

#### Element Selectors
- Style all level-one headings with a text color and center alignment
- Style all paragraph elements with an appropriate font size

#### Class Selectors
- Create a reusable class named section-box
- Apply border, padding, and margin to all sections using this class

#### ID Selectors
- Assign an ID named student-name to the student's name
- Apply a distinct color and font weight using this ID

#### Group Selectors
- Apply common styles to level-two and level-three headings using group selectors

#### Descendant Selectors
- Apply different styles to list items inside the course list and hobbies list

#### Universal Selector
- Use the universal selector to reset default margin or padding

Inline CSS and internal CSS are not allowed.

## 8. Inspection and Analysis Task
Students must perform the following steps:
- Open the web page in a browser
- Use the browser's Inspect tool
- Identify one element styled using a class selector
- Identify one element styled using an ID selector

The identified elements must be documented as HTML comments within the index.html file.

## 9. Constraints
The following restrictions must be strictly followed:
- No inline CSS
- No internal style tags
- No JavaScript
- No advanced CSS properties such as Flexbox, Grid, or Media Queries

## 10. Submission Guidelines
Submit the GitHub repository link. The repository must contain a properly structured
README.md file that includes screenshots of the completed task.

## 11. Evaluation Criteria
| Criteria | Marks |
|----------|-------|
| HTML Structure and Semantics | 10 |
| CSS Selector Usage | 15 |
| Inspection Task Completion | 5 |
| Code Organization and Readability | 5 |
| **Total Marks** | **35** |

## 12. Academic Integrity
Students must submit original work. Any form of plagiarism or code sharing will be treated as
a violation of academic integrity policies and may result in disciplinary action.

## 13. Expected Learning Outcome
By completing this lab assignment, students will gain confidence in writing structured HTML
and applying CSS selectors correctly, forming a strong foundation for advanced styling and
layout techniques in subsequent labs.
