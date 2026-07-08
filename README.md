# Class Contributor Gallery 🚀

Welcome to our first open-source project! Follow the steps below to add your personal profile card to our class gallery. You can use your GitHub profile picture OR download/upload your own custom image.

## 🛠️ Project Setup

1. **Fork** this repository to your own GitHub account using the "Fork" button at the top right.
2. **Clone** your forked repository to your computer:
   ```bash
   git clone https://github.com/...
   ```
3. Open the `student-profiles` folder in your favorite text editor (like VS Code).

---

## 📝 How to Add Your Card

1. Open the `index.html` file.
2. Scroll down until you find this line:
   ```html
   <!-- NEXT STUDENT ADDS THEIR CARD BELOW THIS LINE -->
   ```
3. Choose **one** of the image options below, copy the code block, and paste it directly underneath that comment line.

### 🖼️ Option A: Use your GitHub Profile Picture (Easiest)
Use this if you want to pull your image directly from your GitHub profile without downloading anything.
```html
<div class="card" onclick="showMessage('Hi! I am [Your Name]. [Add a fun fact here]!')">
    <img src="https://github.com" alt="[Your Name]'s Avatar" class="profile-img">
    <h3>[Your Name]</h3>
    <p class="role">[Your Role]</p>
    <div class="skills">
        <span>HTML</span> <span>CSS</span> <span>Git</span>
    </div>
</div>
```
*(Remember to replace `YOUR_GITHUB_USERNAME.png` with your actual username, like `octocat.png`)*

### 💾 Option B: Use a Downloaded Local Image
Use this if you want to use a custom image from your computer.
1. Save your image inside the `images/` folder of this project if it's not there already.
2. Name the file clearly using lowercase and hyphens (e.g., `my-profile.jpg`).
3. Paste this code block:
```html
<div class="card" onclick="showMessage('Hi! I am [Your Name]. [Add a fun fact here]!')">
    <img src="images/your-file-name.jpg" alt="[Your Name]'s Profile Picture" class="profile-img">
    <h3>[Your Name]</h3>
    <p class="role">[Your Role]</p>
    <div class="skills">
        <span>HTML</span> <span>CSS</span> <span>Git</span>
    </div>
</div>
```
*(Remember to fix the `src="images/your-file-name.jpg"` path to match your exact file name and extension!)*

---

## 🚀 Submitting Your Changes

Once your card looks good and your image displays correctly in your browser, submit it:

1. Stage your changes (the dot `.` ensures your new image file inside the `images/` folder gets added too!):
   ```bash
   git add .
   ```
2. Commit your changes:
   ```bash
   git commit -m "Added Profile Card for [Your Name]"
   ```
3. Push the changes to your GitHub fork:
   ```bash
   git push origin main
   ```
4. Go back to the original classroom repository on GitHub.
5. Click the **"Compare & pull request"** button that appears.
6. Click **"Create pull request"**.

🎉 **That's it!** Once approved, your profile card will go live on the site.
