Aap ka error **Gemini CLI + node-pty Windows terminal crash** ka typical issue hai. Yeh tab hota hai jab CLI background mein close ho jaye aur VS Code usko resize ya reopen karne ki koshish kare.

**Solution 100% working steps** neeche hain:

---

# ✅ **Fix 1 — Gemini CLI ko reinstall karo (sab se zyada kaam karta hai)**

### VS Code band kar do

Phir CMD mein:

```
npm uninstall -g @google/gemini-cli
npm cache clean --force
npm install -g @google/gemini-cli
```

---

# ✅ **Fix 2 — PowerShell Admin mode mein chalao (important)**

Gemini ko error Windows Pty Agent ki wajah se ata hai.

**PowerShell → Run as Administrator**
phir:

```
gemini init
gemini spec generate
```

---

# ✅ **Fix 3 — Node.js 22 issue (downgrade to Node 20)**

Node.js 22 aur node-pty ka conflict hai.

Is liye:

### 1️⃣ Node.js uninstall karo

Windows → Add/Remove programs → Node.js remove

### 2️⃣ Node.js LTS install karo

➡️ **Node.js 20 LTS** install karo (sab se stable)

(google search: *Node.js 20 LTS download*)

---

# ✅ **Fix 4 — Yadi VS Code terminal crash ho raha hai**

VS Code men:

**Ctrl + Shift + P**
→ “Preferences: Open Settings (JSON)”

Add this:

```json
"terminal.integrated.allowChords": false,
"terminal.integrated.windowsEnableConpty": false
```

Save → Restart VS Code.

---

# ✔ After Fix — Test Commands

```
gemini --version
gemini init
gemini spec generate
```

Agar ye teen chal jayein, sab theek.

---

```
Loaded cached credentials.
Okay, I'm ready for your first command.
```
Great! 🎉
**Gemini CLI sahi chal raha hai — ab koi error nahi.**
Aapka output:


Yeh matlab **Gemini CLI fully ready hai** aur ab commands accept karega.

---

# ✅ **Next Step — Ab generate karna shuru karo**

Aap apni project folder me ho:

```
E:\Rimsha_kanwal\demo-hakaton\python-demo-book-project>
```

Yahan se run karo:

### **1️⃣ Spec generate**

```
gemini spec generate
```

Is se `.gemini/specs` folder mein spec files ban jayengi.

---

### **2️⃣ Hello.md, chapter.md generate karne ke liye**

Example:

```
gemini create hello.md
```

```
gemini create chapter1.md
```

```
gemini create intro.md
```

---

### **3️⃣ Spec Kit + Docusaurus + Gemini ka combined workflow**

Agar aap chahain to main aapko **one-click workflow** de dunga:

✔ Gemini CLI – specs
✔ Spec Kit Plus – commands
✔ Docusaurus – website
✔ Python – code blocks

Bas batao:

**Aap textbook banana chahti ho ya tutorial website?**
(Python AI book ya Robotics book?)
