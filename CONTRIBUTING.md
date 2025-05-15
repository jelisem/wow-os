# 🌱 Contributing to the WoW OS
Thanks for helping grow this shared library!  
Here’s how to contribute a new example using our simple, structured format.

---

## 🛠️ Step 1: Pick the Right Template

Choose a template folder based on the type of content you’re adding:

- Structured Interaction → `structured-interaction-template-COPY ME`
- Problem → `problem-template-COPY ME`
- Goal → `goal-template-COPY ME`

Duplicate the folder and rename it using the content’s `id`  
(e.g., `zero-to-five-check`, `unspoken-misalignment`).

---

## ✍️ Step 2: Fill in the Files

### 1. `index.yaml`

Open `index.yaml` and update:
- `id`: use lowercase-kebab-case (e.g. `priority-vote`)
- `name`: human-readable name
- `category`: keep the existing one unless you’ve discussed adding a new category
- `description`: 1–2 sentence plain-language summary
- `files:`: make sure `structured-interaction-details.md` (or equivalent) is listed
- You can leave `tags`, `alias`, `references`, and `origin` empty for now

### 2. `[category]-details.md`

Open the Markdown file and follow the format provided in the template:
- For **structured interactions**, include time, participants, materials, and step-by-step instructions
- For **problems/goals**, include sections like “Sounds Like,” “Looks Like,” and “What Success Looks Like”

---

## 📎 Step 3 (Optional): Add Supporting Files

If you have diagrams, PDFs, prompt cards, or other helpful materials, add them to the same folder.  
Then update the `files:` section in `index.yaml` to include them.

---

## 🔁 Step 4: Share Your Contribution

- If you’re working in a shared folder: let us know it’s ready to review.
- If you’re using GitHub: open a Pull Request.
- Not sure? Reach out in the community channel and we’ll help.

---

## 🧪 Need Help?

If you’re unsure about:
- How to format something
- Where your content fits
- Whether something is “good enough”

Just ask. We’d rather see a rough draft than miss a good idea.
