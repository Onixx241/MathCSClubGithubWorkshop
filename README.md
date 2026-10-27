___
<h1>Welcome to the Math And CS Club Beginners Github Workshop!</h1>

___

<h2>Workshop Outline</h2>
<ol>
  <li>What is Source Control?</li> <br/>
  <li>What is Git?</li> <br/>
  <li>What is Github?</li> <br/>
  <li>Why use Github?</li> <br/>
  <li>Account Creation / Login </li> <br/>
  <li> Your Github Profile and READMEs </li> <br/>
  <li>Your First Repository</li> <br/>
  <li>Structuring Your Repository</li> <br/>
  <li>What are Github Codespaces?</li> <br/>
  <li>After Your First Commit</li> <br/>
  <li>Pull Requests</li> <br/>
  <li>Github Pages</li> <br/>
  <li>Github Education Pack</li> <br/>
  <li>End / Questions</li> <br/>
  <li>My email</li> <br/>
  <li>Resources</li>
</ol>

---

<h2>What is Source Control?</h2>

 `Source Control` or `Version Control` is the practice of keeping track of changes to your codebase over time.

 `Source Control` is an important part of development, without it there would be no way to keep track of who committed what or when they committed it, leading to missing changes and unreversible broken code.

---

<h2>What is Git?</h2>

Git is a `Source Control` software created in 2005 and widely used today to track changes to codebases and help developers collaborate.

A `Repository` is a centralized storage for a codebase where all developers commit and pull changes from. This is the heart of source control !

`Commits` are snapshots of your repository over time, usually created when you push changes to the repo.

`Pushing` changes means that you are pushing changes to the repository from your files (for example, changing a line of code) in order for Git to track your changes.

`Pulling` changes from the repository means just that, retrieving all the changes made to the repository by other developers.

`Branches` are branched off versions of your codebase in your repository, usually used to separate production development and feature versions of your codebase.
Branches are always based off of other branches whether it be the master branch or any other. `Merging` is the act of literally merging changes between two branches in your repository.

`Pull Requests` are a big part of source control collaboration, allowing you or others to review changes from a branch before it gets merged into the main branch. 

> [!NOTE]
> Although this workshop is about GitHub, knowing these source control basics is very helpful to learning GitHub and getting comfortable with its source control features

---

<h2>What is Github?</h2>
<p>GitHub is a web based application and open source collaboration platform based off and built on top of Git source control!</p>

<p>Some core features of GitHub is access to many open source projects, free hosting for static webpages (this workshop site was made with GitHub pages!), and most importantly, access to a free source control platform built on top of the most used source control software which is Git.</p>

<p>Other features include project board, issue tracking, CI/CD deployment via GitHub Actions, and codespaces.</p>

---

<h2>Account Creation / Login</h2>

Create your account at [Github Signup](https://github.com/signup).

---

<h2>Your Github Profile and READMEs</h2>

Your profile is a very important part of your GitHub, since it's usually the first impression given of you to other people who view your work!

<img width="797" height="367" alt="image" src="https://github.com/user-attachments/assets/40c54317-9e2c-46e0-8f55-c73bb96bee12" />

Make sure to put a good description about what you're interested in or what you're working on! Also show off your best projects on your pinned !

<h4>Contribution Graph</h4>

<img width="491" height="286" alt="image" src="https://github.com/user-attachments/assets/f72d7283-30f6-4e02-97da-060bc3126b45" />

The `Contribution Graph` is a good way to track your activity on your projects, although it should be noted that the contribution graph will only track commits to the main branches of your projects, feature branches and other branches will be ignored in this graph. However this will also pick up commits to other users projects.



<h4>READMEs</h4>

A `README` is an important file on GitHub ( This workshop's site was made in a README! ) which usually uses [GitHub Markdown formatting](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

`READMEs` are used for everything from customizing your profile, to documentation for repositories to simple websites hosted on `GitHub Pages`.

A good mature repository usually has a well formatted `README` explaining the repository and its usage, as well as instructions on building the project if applicable.

When customizing your GitHub profile, take advantage of the `README` to make your profile stand out!

> [!NOTE]
> To create your profile `README` create a new repository (covered in next section) and name the repository exactly the same as your GitHub username.


---

<h2>Your First Repository</h2>

Click the top right where your profile portrait is, go to repositories:

<img width="371" height="365" alt="image" src="https://github.com/user-attachments/assets/c042d0d0-6e1e-4f09-a1b7-00ff8146f69d" />

To create your repository, hit the `New` Button on the top right of the repositories screen:
<img width="793" height="361" alt="image" src="https://github.com/user-attachments/assets/877273b9-a59f-4810-b69c-bee33621ee54" />


Set your repository name and description. Also configure your visibility, license and others:
<img width="381" height="571" alt="image" src="https://github.com/user-attachments/assets/c927b01c-6289-417b-b0e9-6630b7312d84" />

---

<h2>Structuring Your Repository</h2>

To maintain a clean repository it's important to structure it correctly. Different approaches can be taken but my personal favorite is keeping the **ROOT** folder as the container to different parts of your repository such as the actual source, documentation and other things such as files to include or Readme's. 

> [!NOTE]
> A good rule of thumb is to keep your source code inside a folder called `src` in the root of your repository, and example files or documentation in either the root folder or a specified docs folder.


ROOT

├── src/                      
├── tests/                    
├── docs/                    
├── scripts/                  
├── .gitignore                
├── LICENSE                   
└── README.md                 



<img width="924" height="424" alt="image" src="https://github.com/user-attachments/assets/ebe389e9-beed-4652-8e52-1a51490d1e49" />

---

<h2>What are Github Codespaces?</h2>

`Codespaces` is a browser based VS code environment accessible from anywhere. It comes preloaded with many major runtime environments for languages or frameworks like .NET or Python.

<h3>How To Set Up A Codespace</h3>

For a fresh repository:
1. Press create a codespace.
2. Confirm your choice on the next screen.
3. That's it!


After your first upload / existing repos:
1. Go to your repository and hit the code button.
2. Go to the `Codespace` tab.
3. Press the plus icon to create a new `Codespace`, it'll open automatically.

<img width="803" height="517" alt="image" src="https://github.com/user-attachments/assets/976d9296-3c9d-44ce-9842-9751d7674611" />
<img width="1277" height="635" alt="image" src="https://github.com/user-attachments/assets/4961dcfc-b42e-4944-a3ef-e838cd6cb03b" />


And just like that you have a complete development environment available !

<h3>Source Control in Your Codespace</h3>

Now you have an opportunity to use what you learned about source control earlier,

Go to the left side and press the 3 node icon, and you'll get the source control window:

<img width="382" height="726" alt="image" src="https://github.com/user-attachments/assets/046236c2-b4a6-4e05-b2c9-c7ac9cbcec0c" />

Here you can view previous commits and most importantly commit your changes.

### Exercise: 
- Create a file in your codespace.
- Go back to your source control tab and commit your change to your repository.

Once you create the file and go back you should see something like this:

<img width="380" height="222" alt="image" src="https://github.com/user-attachments/assets/d5f541f4-a446-4c1f-870d-52acd118f7ee" />

This means you're ready to save your changes to your repository.

Write a clear commit message then press `commit`.
Press `sync` afterwards to synchronize your changes to the repository on Github.

---
<h2>After Your First Commit</h2>

 Now that you have a commit under your belt, its a good time to practice creating a branch in your repository.

- Go back to your repository tab and press your main branch dropdown then go to view all branches 

<img width="537" height="457" alt="image" src="https://github.com/user-attachments/assets/3e5083a4-8e4e-44cd-b8dd-c20f936e756f" />

After you get to the all branches view press new branch and you'll see this:

<img width="627" height="367" alt="image" src="https://github.com/user-attachments/assets/dbc201ec-fcaf-47aa-b22b-3bdc014a7f78" />

Remember! Your source branch is the branch that your new branch will be based on, your new branch will have all the same changes and commit history up until the point you created it.

Name your branch something like 'development'.

---

<h2>Your First Pull Request</h2>

A `Pull Request` is a way to review and merge changes into a codebase. It is used very frequently to avoid direct, unreviewed commits.
`Pull Requests` merge two branches in order to integrate changes.

Now comes the collaborative (or not if you don't feel like partnering up) portion of the workshop:

Go to your repository then settings, then press on collaborators.

<img width="1692" height="766" alt="image" src="https://github.com/user-attachments/assets/cf6df69a-8349-4df9-a2f4-89b4e28a86d6" />

Invite someone near you as a collaborator so they can open a pull request on your project!

Now ! Either you or the person you invited to your repository can go back to their `Codespace` and switch your branch to the newly created one by going to the bottom left and pressing main.

<img width="497" height="33" alt="image" src="https://github.com/user-attachments/assets/76b27273-3a7c-4552-aff9-d6d45e68a6fa" />

A pop-up should appear with all the branches, select your new one.

<img width="796" height="386" alt="image" src="https://github.com/user-attachments/assets/314cdc46-610e-459d-9bf1-6041eeb16bfd" />

After you press OK you will now be working from your secondary branch. Create a file or edit one that exists in the repository then go back to your source control window and commit it.

Now comes the actual Pull Request portion!

Go back to your Github repo tab and press `Pull Requests`:

<img width="2201" height="220" alt="image" src="https://github.com/user-attachments/assets/ae08db27-1040-42d4-a0de-289190842e6a" />

From here you can create a new pull request, 

<img width="1577" height="722" alt="image" src="https://github.com/user-attachments/assets/b20e98d8-4cf8-4766-97ae-ba46cda33b8e" />

At the top select `Main` as your base branch and your new branch as your compare branch. Your base branch will be the branch your changes go into and your compare will be where they came from.

<img width="1622" height="811" alt="image" src="https://github.com/user-attachments/assets/82cb4aa3-7186-4576-903c-deb0867dcecb" />

After you've continued on, assign yourself as an assignee and if you worked with someone else, add them as a reviewer! The reviewer will make sure the changes merged are good enough to be introduced into the main branch.

If you worked by yourself just assign yourself as an assignee and create the pull request!

<img width="720" height="633" alt="image" src="https://github.com/user-attachments/assets/4c8387d8-ef7c-4874-8348-40c4ff941a7d" />

Once you've created the pull request it should look like this, then you or your reviewer is ready to merge the changes into main by hitting `Merge Pull Request` ! You can then either delete the source if it's not needed anymore or keep it.

If everything goes right and gets merged you should see this in your window indicating the branches and changes have been merged:
<img width="767" height="131" alt="image" src="https://github.com/user-attachments/assets/9d75da8d-6de1-4c07-b3eb-86115543867e" />

---
<h2>Github Pages</h2>

Github pages are a way to host your own simple websites or documentation for other people to access for free ! This workshops website was made using Github Pages!

The documentation and instructions for how to set up your Github pages are both in [this](https://docs.github.com/en/pages/quickstart) link and below in the resources section.

---

<h2>Github Education Pack</h2>

The Github education pack is an excellent resource provided for free by Github for College Students which many benefits.

The benefits include:

- Free access to pro versions of online programming related courses
- Free development tools
- Free domain name for your website and Microsoft credits for azure server hosting
- and much more !

The link to all the benefits and how to sign up is in the resources section below!

---

<h2>End / Questions / My Email</h2>

# My Email: ONIX.TORRES88@stu-mail.bcc.cuny.edu
Feel free to email me whenever you have any questions!

---
<h2>Resources</h2>

**Visualizing Git Branching:** https://learngitbranching.js.org/

**GitHub education pack apply guide:** https://docs.github.com/en/education/about-github-education/github-education-for-students/apply-to-github-education-as-a-student

**Github Education Pack Benefits Link:** https://education.github.com/pack

**Github Pages Docs:** https://docs.github.com/en/pages

**Github Markdown Docs:** http://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax
