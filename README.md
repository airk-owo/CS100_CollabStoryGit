# Collaborative Story Writing with Git

Welcome to the **Collaborative Story Writing** activity! In this repository, you'll work together with your group to create a unique and creative story using Git. This activity is designed to help you learn about team collaboration and how to resolve merge conflicts—all while having fun!

---

## 📚 **Objective**

- **Collaborate** with your group to write a creative story.
- **Practice** using Git commands for team collaboration.
- **Experience** and **resolve** merge conflicts.
- **Enhance** communication and coordination skills.

---
## **Getting Started**
### 1. 👥 **Form Your Group**
- **Group Size:** 4-5 students. 
- **Action:** Sit together or connect virtually to facilitate communication. Pick a group coordinator.



### 2. 🛠️ **Setup a Shared Repository**

- **Fork the Repository**: The group coordinator clicks **Fork** on this repository to create a copy under their GitHub account.
- **Add Collaborators**: Go to **Settings > Manage access** in the forked repository, click **Invite a collaborator**, and add other group members.
- **Accept Invitation**: Each collaborator accepts the invitation via email or GitHub notifications.
- **Clone the Repository**: All group members clone the forked repository to their local machines.

### 3. 📝 **Plan Your 5-Line Story**

- **Discuss with your group:** Theme of the story, characters, setting, and plot ideas.
- **Decide** which member will contribute which line to the shared repository.

**Remember**: You'll all be editing the **same file** at the **same time**.

### 4.✍️ **Contribute Your Line to the Story**

- **Edit the file**: open story.txt file in your local repository and add your line at the end of the file. Save your changes.
- **Stage the Changes**: add the file to the staging area
     ```bash
     git add story.txt
     ```

- **Commit the Changes**: commit your contribution with a meaningful message:
     ```bash
     git commit -m "Added my line to the story"
     ```

- **Push to the Shared Repository**: push your changes to the remote repository:
     ```bash
     git push origin main
     ```

**Note**: If you encounter an error when pushing, it may mean the repository has new changes. In that case, pull the latest changes, resolve any conflicts, and try pushing again.

