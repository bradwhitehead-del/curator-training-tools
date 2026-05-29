# Curator Training Tools

A simple training hub for the curator team — short screen-capture videos and reference documents, all in one easy-to-browse web page.

## 🌐 Live site
👉 **https://bradwhitehead-del.github.io/curator-training-tools/**

---

## How to add a new video

1. Drop your `.mp4` file into the **`videos/`** folder
2. Open `index.html` and find the comment that says `ADD YOUR VIDEO CARDS BELOW`
3. Copy the sample card block and update three things:
   - `videos/your-file.mp4` → your file name
   - `"Your Title"` → the video title
   - `"Your description."` → a one-sentence description
4. Commit and push — the site updates automatically

## How to add a new document

1. Drop your file (PDF, Word, etc.) into the **`docs/`** folder
2. Open `index.html` and find `ADD YOUR DOC CARDS BELOW`
3. Copy the sample card block and update the filename, title, and description
4. Commit and push

---

## Folder structure

```
curator-training-tools/
├── index.html       ← the web page
├── videos/          ← put .mp4 screen recordings here
└── docs/            ← put PDFs / Word docs here
```
