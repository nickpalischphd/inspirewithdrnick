# Inspire with Dr. Nick — Publishing Guide

## Your Files
```
inspire-dr-nick/
├── index.html          ← Your website
├── dr-nick.jpg         ← Your photo
├── posts.json          ← Blog post index (update when adding posts)
├── netlify.toml        ← Netlify settings
├── admin/
│   ├── index.html      ← CMS login page
│   └── config.yml      ← CMS configuration
├── _posts/             ← Blog post markdown files
├── _stories/           ← Reader story files
├── _data/
│   └── settings.json   ← Site settings
└── images/
    └── posts/          ← Upload post images here
```

---

## Step 1 — Create a Free GitHub Account
1. Go to **github.com** and sign up (free)
2. Click **New Repository**
3. Name it: `inspire-dr-nick`
4. Set it to **Public**
5. Click **Create Repository**

---

## Step 2 — Upload Your Files to GitHub
1. On your new repo page, click **uploading an existing file**
2. Drag your entire `inspire-dr-nick` folder contents into the upload area
3. Click **Commit changes**

---

## Step 3 — Deploy on Netlify (Free)
1. Go to **netlify.com** and sign up with your GitHub account
2. Click **Add new site → Import an existing project**
3. Choose **GitHub** and select your `inspire-dr-nick` repo
4. Leave all settings as default
5. Click **Deploy site**
6. Your site goes live in ~60 seconds at a URL like `amazing-name-123.netlify.app`

---

## Step 4 — Enable the CMS Login
1. In Netlify dashboard, go to **Site Settings → Identity**
2. Click **Enable Identity**
3. Under **Registration**, choose **Invite only**
4. Go to **Services → Git Gateway** and click **Enable Git Gateway**
5. Go to **Identity tab → Invite users** and invite your own email
6. Check your email and accept the invite — set your password

---

## Step 5 — Add a Custom Domain (Optional, ~$12/year)
1. Buy a domain at **namecheap.com** (e.g. `inspirewithdrnick.com`)
2. In Netlify: **Domain Settings → Add custom domain**
3. Follow Netlify's instructions to point your domain

---

## How to Write a New Blog Post
1. Go to **yoursite.com/admin**
2. Log in with your email/password
3. Click **Blog Posts → New Blog Post**
4. Fill in: Title, Date, Category, Excerpt, and Body
5. Click **Publish** — it goes live on your site within 60 seconds

---

## How to View Reader Stories
1. Go to **yoursite.com/admin**
2. Click **Reader Stories**
3. Stories submitted via your site form will appear here
4. You can mark them as Read, Featured, or Archived
5. Add private notes only you can see

---

## Adding a New Post Manually (posts.json)
When you add a post through the CMS, Netlify handles everything automatically.
If you ever need to add a post manually, add an entry to `posts.json` following
the same format as the existing entries.

---

## Need Help?
- Netlify Docs: docs.netlify.com
- Netlify CMS Docs: www.netlifycms.org
