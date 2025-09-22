# GitHub Tutorial

## 1 - Initial Setup

Before you can start working with GitHub, you’ll need to create an account, install the tools, and set up a workspace on your computer.

---

### 1.1 - Create a GitHub Account

1. Go to the [GitHub website](https://github.com/).
2. Click **Sign Up** and follow the instructions to create an account.
3. Use a strong, secure password and enable **two-factor authentication (2FA)** for added security.  
4. It’s generally recommended to use a **personal email address** instead of a work email. That way, if you change jobs, you’ll still have access to your account.

---

### 1.2 - Install GitHub Desktop

GitHub Desktop is a beginner-friendly application that makes it easier to work with Git repositories without using the command line.

1. Download GitHub Desktop from [here](https://desktop.github.com/).
2. Install the application and log in with your GitHub username and password.
3. Once logged in, you can connect GitHub Desktop to your repositories online and sync changes between your computer and GitHub.

*Tip: Advanced users may also want to install [Git](https://git-scm.com/downloads) directly to use command-line tools, but GitHub Desktop is perfect for getting started.*

---

### 1.3 - Set Up a GitHub Folder

To stay organized, it’s a good idea to create a dedicated folder on your computer for your projects:

1. Create a folder named **GitHub** (or simply **Git**) in a location that’s easy to find, such as:
   - **Documents/GitHub**
   - **Desktop/GitHub**
2. This folder will act as the main location where you’ll store all your cloned or created repositories.
3. When you clone a repository from GitHub, save it inside this folder so everything stays organized.

---

At this stage, you should have:
- A GitHub account  
- GitHub Desktop installed and logged in  
- A GitHub folder ready for your projects  

---

## 2 - Introduction to Repositories

A **repository** (often shortened to **repo**) is where an individual project lives on GitHub.  
Repositories store all the files, folders, and version history for a project.  

You can:
- Create and manage your own repositories.  
- View other people’s repositories.  
- Contribute to shared repositories — enabling transparent, collaborative working.  

---

### 2.1 - Public vs Private Repositories

- **Public Repositories**  
  Anyone can view the contents of a public repo, even without a GitHub account.  
  - Example: [genomicc-workflows](https://github.com/baillielab/genomicc-workflows) is a public repository — accessible to everyone.  

- **Private Repositories**  
  Only people who are explicitly invited can see and access private repos.  
  - Example: [baillielab-notes](https://github.com/baillielab/baillielab-notes) is private — if you’re not registered as a member of the Baillie Lab GitHub organisation, you won’t be able to access it.  

---

### 2.2 - The Baillie Lab Organisation

The [Baillie Lab GitHub organisation](https://github.com/baillielab) contains a mix of public and private repositories.  
- Public repositories are visible to everyone.  
- Private repositories require membership.  

If you’ve just created your GitHub account, you’ll still be able to see the public repositories, but not the private ones.  

---

### 2.3 - Best Practices: Choosing Public vs Private

When deciding whether a repository should be **public** or **private**, keep the following in mind:

- **Start Private, Stay Private (if sensitive data is involved).**  
  If a repository ever contains identifiable, confidential, or unpublished data, it should **remain private permanently**.  

- **Be cautious about “flipping” from private to public.**  
  Making a private repo public will expose the *entire commit history* — including old files and previous versions.  
  Even if you later delete sensitive files, they may still be visible in the history.  

- **If you plan to make a repo public later:**  
  - Start the repo as public from the beginning (but only if you’re certain no sensitive data will be added).  
  - Or, keep the repo private until it’s “ready,” then create a **fresh public repo** and copy across only the files that are safe to share.  

- **Rule of thumb:**  
  If you’re unsure whether data might ever need to remain private, **keep the repository private**. You can always publish safe outputs separately.  

---

**Action Required**  
Please make a note of your **GitHub username** and send it to us so we can add you as a member of the Baillie Lab organisation.

--- 

## 3 - Exploring a Repository on GitHub

Before cloning a repository to your computer, it’s helpful to look at it on the **GitHub website**. This gives you an overview of its structure, files, and activity.

---

### 3.1 - Open the Repository

Go to the Baillie Lab GitHub Tutorial repository:  
[https://github.com/baillielab/GitHub_Tutorial](https://github.com/baillielab/GitHub_Tutorial)

---

### 3.2 - Navigating the Repository

Once on the repository page, take note of:

- **Repository name** – shows at the top (e.g., `GitHub_Tutorial`).  
- **README.md** – displays automatically below the file list; usually contains instructions, project overview, or important notes.  
- **File list** – shows the project’s folders and files. You can click on a file to view its contents.  
- **Branches** – check the branch dropdown near the top-left to see if there are multiple versions.  
- **Commit history** – click on the **Commits** link to see all changes made to the repo, who made them, and when.

*Tip: The GitHub website is a good place to explore a repo without making any changes. You can also preview files, review changes, and copy code snippets.*

---

### 3.3 - Understanding Key Sections

- **Code Tab** – default view showing files and folders.  
- **Issues Tab** – a place for reporting bugs or requesting features.  
- **Pull Requests Tab** – shows proposed changes that contributors want to merge.  
- **Actions, Projects, Wiki, Security, Insights** – optional sections that may exist depending on the repository setup.  

---

After exploring the repository on GitHub, you should:
- Be familiar with the repository structure.  
- Know where to find files, the README, commit history, and branches.  
- Understand the main sections of the repository website before cloning it locally.
