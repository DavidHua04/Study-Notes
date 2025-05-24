## Nielsen's 10 Usability Heuristics with Examples
### 1. Visibility of System Status
A well-designed system should always keep users informed about what is happening through appropriate feedback within a reasonable time.

Real-Life Example:
When you use your smartphone, you immediately see the battery percentage, Wi-Fi connectivity, and notifications for missed calls or messages. This immediate feedback helps users stay aware of their device’s status and take necessary actions.

Best Practice:
- Display loading indicators when a process is in progress.
- Provide real-time feedback, such as a progress bar during file downloads.
- Show confirmation messages after an action is completed successfully.

### 2. Match Between the System and the Real World
The system should use language, icons, and visuals that users are familiar with, reducing cognitive load and making interactions more intuitive.

Real-Life Example:
In e-commerce apps like Amazon, the shopping cart icon resembles a physical cart, making it instantly recognizable.

Best Practice:
- Use real-world metaphors, such as a trash bin icon for deleting files.
- Keep terminology simple and understandable for the target audience.

### 3. User Control and Freedom
Users should have the ability to easily navigate and undo actions if they make mistakes.

Real-Life Example:
Gmail allows users to “Undo Send” an email within a few seconds after sending it. This feature prevents accidental emails from being permanently sent.

Best Practice:
- Offer undo and redo options.
- Allow users to exit processes quickly without losing progress.

### 4. Consistency and Standards
Maintaining consistency in UI elements and interactions ensures users do not have to relearn new patterns when navigating an interface.

Real-Life Example:
On most websites, clicking the logo takes users back to the homepage. This convention is widely recognized, reducing confusion.

Best Practice:
- Maintain a uniform layout and design across all pages.
- Use standard icons and interface elements (e.g., a magnifying glass for search).

### 5. Error Prevention
Preventing errors is better than providing error messages. A well-designed system anticipates mistakes and guides users accordingly.

Real-Life Example:
Google Chrome warns users when they are about to close multiple tabs, preventing accidental loss of data.

Best Practice:
- Implement confirmation dialogs before irreversible actions (e.g., deleting an account).
- Use inline validation to prevent form errors before submission.

### 6. Recognition Rather Than Recall
The user interface should display important information, reducing the need for users to remember details.

Real-Life Example:
Netflix suggests “Continue Watching” for users, so they don’t have to remember where they left off.

Best Practice:
- Provide dropdown menus instead of requiring users to type frequently used inputs.
- Display recently accessed files or search history.

### 7. Flexibility and Efficiency of Use
A system should cater to both beginners and advanced users by offering shortcuts and customization options.

Real-Life Example:
Microsoft Word allows users to use both menus and keyboard shortcuts (e.g., Ctrl + C for copy), making it suitable for all skill levels.

Best Practice:
- Enable keyboard shortcuts for frequent actions.
- Allow users to customize dashboards and toolbars.

### 8. Aesthetic and Minimalist Design
A clutter-free interface improves user experience by focusing on essential elements.

Real-Life Example:
Apple’s website has a clean design with minimal text and high-quality images, making navigation effortless.

Best Practice:
- Remove unnecessary elements and distractions.
- Use whitespace effectively to improve readability.

### 9. Help Users Recognize, Diagnose, and Recover from Errors
Error messages should be clear and constructive, helping users resolve issues without frustration.

Real-Life Example:
When entering the wrong password, most websites highlight the issue and offer a “Forgot Password” link.

Best Practice:
- Provide error messages that explain the problem and suggest a solution.
- Use color codes (e.g., red for errors, green for success) to make messages more intuitive.

### 10. Help and Documentation
Even though a well-designed system should be easy to use, having accessible documentation is essential for troubleshooting.

Real-Life Example:
Software like Adobe Photoshop provides tooltips and a help section with step-by-step tutorials for new users.

Best Practice:
- Include a search function in the help section.
- Provide FAQs and video tutorials for common issues.

---

## Usability Engineering Steps: 

### 1. knowing about all potential users
- **Study the intended users and the use of the product**
  - Best if developers go and interview them personally

- **Difficult because**
  - May want to hide the developers
  - Reluctance of sales people
  - Reluctance of users

- **User Characteristics**
  - Work experience, education level, age, previous computer experience
  - Time for learning, training
  - Available hardware (monitor size, acceptance of plugins, cell-phones vs. desktop)
  - Social context of use

#### "Personas"
- Popularized by Alan Cooper
- User archetype you can use to help guide decisions about design decisions
- Created *after* contextual inquiry or equivalent
- Summarizes properties of a group of users
- Use: helps keep designers & implementers focused on user needs
- Include: behavior patterns, goals, skills, attitudes, and environment, with a few fictional personal details to bring the persona to life
- Have a small number for each product
  - One for each important group of users

**Persona Example**
(From: [http://www.steptwo.com.au/papers/kmc_personas/](http://www.steptwo.com.au/papers/kmc_personas/))
```
Bob is 52 years old and works as a mechanic with an organisation offering road service to customers when their car breaks down. He has worked in the job for the past 12 years and knows it well. Many of the younger mechanics ask Bob for advice when they meet up in the depot as he always knows the answer to tricky mechanical problems. Bob likes sharing his knowledge with the younger guys, as it makes him feel a valued part of the team.

Bob works rolling day and night shifts and spends his shifts attending breakdowns and lockouts (when customers lock their keys in the car). About 20% of the jobs he attends are complex and he occasionally needs to refer to his standard issue manuals. Bob tries to avoid using the manuals in front of customers as he thinks it gives the impression he doesn’t know what he’s doing.

Bob has seen many changes over the years with the company and has tried his best to move with the times. However he found it a bit daunting when a new computer was installed in his van several years ago, and now he has heard rumours that the computer is going to be upgraded to one with a bigger screen that’s meant to be faster and better.

Bob’s been told that he will be able to access the intranet on the new computer. He has heard about the intranet and saw once in an early version on his manager’s computer. He wonders if he will be able to find out what’s going on in the company more easily, especially as customers seem to know more about the latest company news than he does when he turns up at a job. This can be embarrassing and has been a source of frustration for Bob throughout his time with the company.

Bob wonders if he will be able to cope with the new computer system. He doesn’t mind asking his grandchildren for help when he wants to send an email to his brother overseas, but asking the guys at work for help is another story.
```
#### Task analysis

- What tasks the users will do?
- Involve users in this
- Important to include exceptions and error conditions
- Many different kinds and variations on TaskAnalyses
  - Nielsen's
  - “Hierarchical Task Analysis”-in textbook
  - (Better to use Cl)
- Need tasks to design Cls, usability analysis, scenarios

### 2. carrying out competitive analysis
### 3. establishing appropriate usability goals
### 4. carrying out parallel designs
### 5. carrying out participatory design
### 6. coordinating the entire user interface
### 7. applying guidelines
### 8. prototyping
### 9. carrying out interface evaluation
### 10. performing iterative design
### 11. obtaining data from actual field applications.


