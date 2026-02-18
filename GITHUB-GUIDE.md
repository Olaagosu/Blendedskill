# 🚀 How to Put Your Course Website on GitHub (Beginner Guide)
## For: Agentic AI Workflows with Make & n8n — AgentFlow Academy

---

## What is GitHub and Why Are We Using It?

Think of GitHub as a **free cloud folder** for your website files. Once your files are on GitHub, you can:
- Share them with a developer to add features
- Publish them live to the internet for **free** using GitHub Pages
- Keep a history of every change you make (so you can undo mistakes)
- Eventually connect it to a proper domain name (like agentflowacademy.com)

---

## What You Have Right Now

You have 2 files from Claude:
- `index.html` — Your course homepage (the sales/landing page)
- `course.html` — The student portal (the inside of the course)

These 2 files link to each other. Put them in the **same folder** on your computer.

---

## Step 1 — Create a Free GitHub Account

1. Go to **github.com**
2. Click **Sign up**
3. Choose a username (e.g. `agentflowacademy`)
4. Use your email, create a password
5. Verify your email — done!

---

## Step 2 — Create Your Repository (Your "Project Folder")

A repository is just a container for your files on GitHub.

1. Once logged in, click the **green "New"** button (top left)
2. Fill in:
   - **Repository name:** `agentflow-academy` *(use dashes, no spaces)*
   - **Description:** Agentic AI Workflows course website
   - Set to **Public** *(required for free GitHub Pages hosting)*
   - ✅ Tick **"Add a README file"**
3. Click **"Create repository"**

---

## Step 3 — Upload Your 2 Files

1. Inside your new repository, click **"Add file"** → **"Upload files"**
2. Drag and drop your `index.html` and `course.html` files onto the page
3. Scroll down to **"Commit changes"**
4. In the message box type: `Add course homepage and student portal`
5. Click **"Commit changes"** (green button)

✅ Your files are now safely stored on GitHub!

---

## Step 4 — Publish Live with GitHub Pages (Free!)

GitHub Pages turns your files into a **real live website** anyone can visit.

1. In your repository, click **Settings** (top menu)
2. Scroll down the left sidebar to **Pages**
3. Under **"Branch"**, click the dropdown that says `None`
4. Select **main** → click **Save**
5. Wait 1–2 minutes

**GitHub will give you a URL like:**
```
https://yourusername.github.io/agentflow-academy/
```

📣 **That's your live website!** Share that URL and people can visit it.

> 💡 The homepage (`index.html`) loads automatically. The course page is at:
> `https://yourusername.github.io/agentflow-academy/course.html`

---

## Step 5 — Update Your Files Later (When You Make Changes)

When Claude helps you update the files:
1. Go to your repository on GitHub
2. Click on the file you want to update (e.g. `index.html`)
3. Click the **pencil icon** ✏️ (top right of the file)
4. **Delete all the old content**, paste in your new content
5. Click **"Commit changes"**

Your live website updates in about 60 seconds!

---

## Step 6 — Connect a Real Domain Name (Optional, Later)

Once you're ready to have `agentflowacademy.com` instead of the GitHub URL:

1. Buy a domain from **Namecheap** or **GoDaddy** (~$12/year)
2. In GitHub → Settings → Pages → Custom Domain, type your domain
3. Follow the DNS instructions GitHub shows you (copy-paste into your domain registrar)
4. Done — usually takes 24 hours to go live

---

## Troubleshooting

| Problem | Fix |
|---------|-----|
| Website shows old version | Wait 2 minutes and hard refresh (Ctrl+Shift+R) |
| Page not found (404 error) | Make sure your file is named `index.html` exactly |
| Links between pages broken | Make sure both files are in the **same folder** (root) |
| GitHub Pages not working | Check Settings → Pages — must be set to `main` branch |

---

## Your File Structure Should Look Like This

```
agentflow-academy/           ← Your GitHub repository
├── index.html               ← Homepage (sales page)
├── course.html              ← Student portal (course inside)
└── README.md                ← Auto-created by GitHub
```

---

## Next Steps After You're Live

1. **Connect Stripe** — You'll need a developer (or use Stripe's no-code payment links as a bridge) to make the payment button actually charge cards
2. **Add real video** — Loom, Vimeo, or YouTube embeds can go into the video player area in `course.html`
3. **Manage students** — Tools like **Memberstack** or **Outseta** can add real login/access control on top of GitHub Pages with no coding

---

## Asking Claude for Help

When you want Claude to update something, always say:
> *"Here is my current [index.html / course.html]. Please update it to [describe change]."*

Then paste the file content. Claude will give you back the updated file.

---

*Built with AgentFlow Academy · github.com/agentflowacademy*
