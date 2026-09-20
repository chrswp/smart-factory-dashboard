Deployment Guide: Hosting Wizurai Digital Factory MVP on GitHub Pages
This guide will walk you through the process of hosting your single-file index.html MVP dashboard on GitHub Pages for free. This is perfect for sharing the prototype with your client.

Prerequisites
A GitHub account (create one for free at github.com if you don't have one).
The index.html file generated in the previous step.
Step-by-Step Instructions
Step 1: Create a New GitHub Repository
Log in to your GitHub account.
In the upper-right corner of any page, click the + icon, and select New repository.
Repository name: Give your repository a relevant name (e.g., wizurai-digital-factory-mvp).
Description: (Optional) Add a short description (e.g., "MVP Dashboard for PT Kayu Timber Indonesia").
Visibility: Keep it Public (GitHub Pages is free for public repositories).
Initialize this repository with:
Check the box for "Add a README file".
Click the green Create repository button.
Step 2: Upload Your index.html File
You should now be on the main page of your newly created repository.
Click the Add file button near the top right, then select Upload files.
Drag and drop the index.html file you saved earlier into the designated area, or click "choose your files" to select it from your computer.
Once the file is listed as ready to upload, scroll down to the Commit changes section.
Add a short commit message (e.g., "Initial commit: Added dashboard HTML").
Ensure "Commit directly to the main branch" is selected.
Click the green Commit changes button.
Important Note: The file MUST be named exactly index.html for GitHub Pages to serve it as the default page.

Step 3: Enable GitHub Pages
In your repository, look at the tabs near the top (Code, Issues, Pull requests, etc.) and click on Settings (it has a gear icon).
In the left sidebar menu of the Settings page, scroll down and click on Pages (under the "Code and automation" section).
Under the Build and deployment section:
Source: Ensure "Deploy from a branch" is selected.
Branch: Click the dropdown that says "None", select main, and ensure the folder dropdown next to it says /(root).
Click the Save button.
Step 4: Access Your Deployed Site
After clicking Save, GitHub will start building your site. This can take a minute or two.
Refresh the page after a short wait. You should see a notification at the top of the GitHub Pages settings screen that looks like this:
"Your site is live at https://[your-username].github.io/[repository-name]/"

Click that URL to view your live, dynamic MVP dashboard!
You can now share this URL directly with your client for their presentation. Any future updates you make to the index.html file in this repository will automatically update the live site.
