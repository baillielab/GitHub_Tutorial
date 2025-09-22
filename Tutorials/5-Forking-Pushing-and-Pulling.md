## 5 - Forking, Pushing, and Pulling a Repository (Practice Task)

If you want to practice making changes and pushing them without affecting the main tutorial repository, you should **fork it to your own GitHub account**.

This is really good practice when making edits to stable, developed code - you can make edits and test things out without affecting anything until you're ready to integrate the changes!

### 5.1 - Fork the Repository

1. Go to the repository page: [https://github.com/baillielab/GitHub_Tutorial](https://github.com/baillielab/GitHub_Tutorial)  
2. Click the **Fork** button in the top-right corner.  
3. Give the repo a slightly different name (e.g. GitHub_Tutorial_Fork) or it will overwrite your clone of the main one!
4. GitHub will create a copy of the repository under your account.  

Now you have your own version of the repository that you can freely edit and push changes to.


![Forking a Repo](https://github.com/baillielab/GitHub_Tutorial/raw/main/Images/forking.png)
![Forking a Repo 2](https://github.com/baillielab/GitHub_Tutorial/raw/main/Images/forking2.png)

### 5.2 - Clone Your Fork

1. Copy the URL of your forked repository.  
2. Open **GitHub Desktop → File → Clone Repository → URL**.  
3. Paste the URL and select your local path (your `GitHub` folder).  
4. Click **Clone**.  

You now have a local copy of your fork.

### 5.3 - Practice Task: Add a File

1. Using a text editor, create a file named with the date and your initials (e.g., `YYMMDD_KC_practice.txt`).
2. Save this in the `Push_test/` folder of your **local fork**.  
3. Open GitHub Desktop — you’ll see your new file listed under **Changes**.  
4. Enter a **summary message** describing your change (e.g., “Add practice file”) and click **Commit to main**.

![Committing the Changes](https://github.com/baillielab/GitHub_Tutorial/raw/main/Images/commiting.png)

### 5.4 - Push Changes to Your Fork

1. Click **Push origin** in GitHub Desktop to upload your changes to your fork on GitHub.  
2. Visit your fork on GitHub — you should see the new file online.

![Pushing](https://github.com/baillielab/GitHub_Tutorial/raw/main/Images/confirm_push.png)

### 5.5 - Create a Pull Request

If you want to suggest your change to the original repository, you can create a **pull request (PR)**. This is how contributions are shared in collaborative projects.

1. Go to your fork on GitHub (e.g., `https://github.com/your-username/GitHub_Tutorial_Fork`).  
2. At the top, you should see a banner:  
   > “This branch is X commits ahead of baillielab:main.”  
3. Click **Contribute → Open pull request**.  
4. Review your changes and add a short description (e.g., “Added a practice file for tutorial”).  
5. Click **Create pull request**.  

![Pull Requests 1](https://github.com/baillielab/GitHub_Tutorial/raw/main/Images/PR1.png)
![Pull Requests 2](https://github.com/baillielab/GitHub_Tutorial/raw/main/Images/PR2.png)

Your pull request will now appear in the original repository (`baillielab/GitHub_Tutorial`) under the **Pull requests** tab.  
- Project maintainers can review your changes, leave comments, and either accept (merge) or reject them.  
- This process keeps the main project safe while still allowing collaboration.  

---

### 5.6 - Pulling Changes

Once your pull request has been accepted, the **main repository** will now include your changes (and possibly changes from other people too). This means your clone of the main repository is now **out of sync** — they don’t automatically know about the new changes.  

To keep your work up to date, you need to **pull the latest changes**.

1. Go to GitHub desktop and select the main repo (GitHub_Tutorial) from the 'current repository' drop down list
2. Click the 'Fetch Origin' button along the top. This will test your local copy against the online repository and identify any changes that aren't synced yet.
3. If there are any changes, the option to 'Pull Origin' plus the number of changes will appear - click this
4. These changes will now be integrated into your local copy.

![Fetch Origin](https://github.com/baillielab/GitHub_Tutorial/raw/main/Images/fetch_origin.png)
![Pull Origin](https://github.com/baillielab/GitHub_Tutorial/raw/main/Images/pull_origin.png)

---

### 5.7 - History

Next to the **Changes** tab in GitHub Desktop is the **History** tab.  

This shows you:  
- A list of all the commits that have been made to the repository.  
- Who made each change, and when.  
- The specific files and lines of code that were added, removed, or edited.  

![History](https://github.com/baillielab/GitHub_Tutorial/raw/main/Images/history.png)

The history is a powerful feature because it allows you to:  
- **Understand progress** — see how the project has evolved over time.  
- **Trace issues** — if something breaks, you can look back to see which commit introduced the problem.  
- **Revert to an earlier commit** — if you make a mistake, you can roll back to a previous version and recover a working state.  

*Tip: Don’t worry about breaking things — Git remembers everything. Even if you make a mistake, you can always go back in history!*

---

### 5.8 - What About Your Fork?

At this point, you’ve used your fork to practice making changes and submitting a pull request.  
Now that we are all working directly from the **main repository**, your fork will soon be **“behind”** the main project — it won’t automatically have the new updates that get added.

---

#### What should you do?

- **Option 1 (Recommended):**  
  You can simply stop using your fork (even delete it!) and continue working with the main repository instead.  
  This keeps things simple and ensures you’re always up to date.  

- **Option 2 (Optional / Advanced):**  
  If you want to keep your fork in sync, GitHub allows you to update it with changes from the main repository.  
  This is useful if you want to practice more pull requests in the future.  
  For this tutorial, you don’t need to do this — but it’s good to know the option exists.

---

For now, the easiest approach is:  
**Keep your fork as a record of your practice, but use the main repository for all future work.**

---

### 5.9 - The Most Important Note: Always Pull Frequently

If there are multiple people working on the repository, or if you’re using it across different computers, it’s **essential** to pull changes regularly.

Why?  
- Changes made by others aren’t automatically downloaded to your computer — you need to fetch them yourself.  
- If you don’t pull often, you could end up:  
  - Making conflicting changes to the same files.  
  - Re-doing work that someone else has already completed.  
  - Creating extra problems that have to be fixed later.  

**Golden rule:** *Always pull before you start working, and pull again before you push your own changes.*  
This habit will save time, prevent conflicts, and keep everyone working smoothly together.

---

### After this section you should be able to:

- Fork a repository to your own GitHub account.  
- Clone your fork locally using GitHub Desktop.  
- Make a change (e.g. adding a file), commit it, and push it to your fork.  
- Create a pull request to suggest your changes to the main repository.  
- Pull updates from the main repository to keep your local copy in sync.  
- Use the **History** tab in GitHub Desktop to review past commits and revert if needed.  
- Decide what to do with your fork once the main repository has moved ahead.  
- Remember the golden rule of collaboration: **always pull before you start working, and pull again before you push.**
