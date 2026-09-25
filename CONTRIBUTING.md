0:00 / 7:40

Practice Project: Part 1 - GitHub UI
Estimated Time: 30 minutes

Overview
In this lab you will start your journey with the GitHub implementation for your organisation by creating a repository in your GitHub account and then initialising the repository with a README.md file and a License. Following this, you'll update the README file to include a Code of Conduct and Contribution Guidelines markdown files. After making these changes, you'll commit the files to your repository.

Next, you'll create a new branch and add code for Shipping logistics calculation. To wrap up, you'll merge this branch into the main branch using a Pull Request.

Objectives
After completing this lab, you will have demonstrated that you can:

Create a repository with a README.md file and a license.
Update the existing files.
Commit the files to your repository.
Create a new branch and add files to it.
Merge this branch to the main branch using a Pull Request.
Task 1: Create a repository with a README file and a license.
At the top right of the GitHub home page, click on the + icon and select New repository.



Create a new GitHub repository called LogisticsShippingRates and make sure that it is Public.

Select the Add a README file field. Click on the Choose a license field and select Apache License 2.0 from the drop down. Finally, click on Create repository.

pp01.png

After successfully creating a new repo, you will see the following screenshot.
PP1.png

Your repository is created and includes the README and LICENSE files. Now, you are ready to update your repository files to include useful information for your community.

Task 2: Update the README file.
Click on README.md file to open it and click the pencil icon to edit it.



Add the following information to the file:
plaintext

Please consider the below factors while contributing

Code Style:
Maintain a consistent code style for readability.

Documentation:
Ensure well-documented code for effective collaboration.

Testing:
Thoroughly test your changes before submitting a pull request.

Issue Tracker:
Check the Issue Tracker for tasks.

Code Review:
All contributions undergo a code review process.

Licensing:
Contributions are licensed.
Now click on Commit changes
readme pic.png(1)

Ensure that the radio button to commit directly to the main branch is selected. Add a commit message and click on Commit Changes
PP2.png

NOTE: After completing the steps in each of the tasks, if you are unable to see the options depicted in the provided screenshots, click on the Code option as highlighted in below screenshot:

code pic.png

Task 3: Add a code of conduct.
A code of conduct helps set ground rules for the behavior of your project's participants. It defines standards for how to engage in a community.

GitHub provides templates for common codes of conduct to help you quickly add one to your project.

To create a new file click on Add file and then Create New File.



Add a new file named CODE_OF_CONDUCT.md to the root folder of the repository. The Choose a code of conduct template button is displayed.
COC.png

Click the Choose a code of conduct template button. You will see a popup mentioning you may lose unsaved changes. Click on OK.
pop up pic.png

Click on Contributor Covenant to load this template. Then click Review and submit to add the file to your project.



Scroll down the page to read the content. Click on Commit changes.
PP4.png(1)

Ensure that the radio button to Commit directly to the main branch is selected and click Commit changes.
PP5.png

If the page is zoomed in, you may see only the Commit changes button and not the radio button. Zoom out or scroll down to see the radio button.


Your project now contains a code of conduct.PP6.png
Task 4: Establish contribution guidelines.
Contribution guidelines provide clear instructions for individuals looking to contribute to the project. To implement these guidelines, please follow these steps:

Create a new file in the repository's root directory and name it CONTRIBUTING.md.

Inside the file, include the following information:

plaintext

Contribution guidelines
Welcome Contributors!
Thank you for considering contributing to the centralized repository. This document outlines the guidelines for contributing to the development of Shipping Rates and Calculations.

Code style
Please follow the coding style and conventions used in the existing codebase. This helps maintain consistency across the project.

Documentation
Ensure that your contributions are well-documented. Include comments in your code where necessary and provide a clear and concise description of your changes in the pull request.

Testing
Before submitting a pull request, make sure your changes have been tested thoroughly. Include relevant test cases and ensure that existing tests pass.

Issue tracker
Check the issue tracker for any open issues or feature requests. If you're working on something, please comment on the issue to let others know.

Code review
All contributions will go through a code review process. Be open to feedback and be willing to make changes if necessary. Code reviews help maintain code quality and consistency.

Thank you for your contribution!
