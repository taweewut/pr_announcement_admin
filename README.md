# 📢 PR Announcement Admin (Mockup)

This is a web-based mockup for managing **Public Relation Audio Announcements** in Thai and English, including:

- ✅ Text input for both languages
- ✅ Audio playback with completion tracking
- ✅ Reset functionality with confirmation
- ✅ Submit button enabled only after both messages are played
- ✅ GitHub-integrated update workflow

---

## 🔧 Local Development Workflow

### 1. Open project folder in Terminal:

```bash
cd /Users/taweewut/MyPythonProject/GoogleCloud/frontend/pr_announcement-admin
```

### 2. Check which files have changed:

```bash
git status
```

### 3. Stage all changes:

```bash
git add .
```

### 4. Commit changes with message:

```bash
git commit -m "Describe your changes here"
```

### 5. Push to GitHub:

```bash
git push
```

🔍 You can check remote with:

```bash
git remote -v
```

---

## 🗃️ GitHub Repository

Main repo: [https://github.com/taweewut/pr_announcement_admin](https://github.com/taweewut/pr_announcement_admin)

---

## 🌐 Live Preview (if using GitHub Pages)

You can configure GitHub Pages under your repo's Settings → Pages.

---

## 📌 Notes

- Reset only clears values temporarily (text reappears on reload).
- The page uses native HTML5 `<audio>` for playback.
- Submit is only allowed after full playback of both audio files.
