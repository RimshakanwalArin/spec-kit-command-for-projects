 **advanced SpacKit Plus commands** hain jo **project planning aur management** ke liye hain. 

---

## 🏗️ **Project Setup Commands**

### 1️⃣ `/sp.constitution`
**Kab use karein**: Jab project ki **basic rules aur structure** define karni ho
**Kya karta hai**: Project ke overall goals, coding standards, aur guidelines set karta hai
**Example**:
```bash
/sp.constitution "Ek e-commerce website banani hai React aur Node.js mein"
```
**Matlab**: "Project ka **constitution/kanoon** bana do - kaise kaam hoga, kya rules honge"

**Use case**: 
- Project shuru karte waqt sabse pehle
- Team ko batana ke kaise code likhna hai
- Standards set karne ke liye

---

### 2️⃣ `/sp.specify` ya `/sp.specifications`
**Kab use karein**: Jab project ki **detailed requirements** likhni ho
**Kya karta hai**: Feature by feature specification banaata hai
**Example**:
```bash
/sp.specify "Login system with email verification"
```
**Matlab**: "Ye feature **detail mein** kaise kaam karega, ye likh do"

**Use case**:
- Har feature ke liye detailed plan
- Developer ko samajhane ke liye exact kya banana hai
- Client ko dikhane ke liye requirements document

**Real example**:
```bash
/sp.specify "User dashboard with profile editing, order history, and wishlist"
```
**Output milega**: 
- User profile: Name, email, phone edit kar sakte hain
- Order history: Last 10 orders display honge
- Wishlist: 50 items tak save kar sakte hain

---

### 3️⃣ `/sp.clarify`
**Kab use karein**: Jab koi cheez **confusing** ho ya clear nahi ho
**Kya karta hai**: Unclear requirements ko clear karta hai
**Example**:
```bash
/sp.clarify "Payment gateway integration mein konsi APIs use karni hain?"
```
**Matlab**: "Ye cheez **confusing** hai, isko clear kar do"

**Use case**:
- Jab specification samajh na aaye
- Jab do options mein confusion ho
- Technical terms ko simple karna ho

---

### 4️⃣ `/sp.plan`
**Kab use karein**: Jab **step-by-step plan** banana ho
**Kya karta hai**: Poore project ka roadmap aur timeline banaata hai
**Example**:
```bash
/sp.plan "Build complete e-commerce website in 3 months"
```
**Matlab**: "Pura project **planning** kar ke do - kya kab hoga"

**Output milega**:
- Week 1-2: Database design
- Week 3-4: Backend APIs
- Week 5-6: Frontend components
- Week 7-8: Integration & Testing

---

### 5️⃣ `/sp.tasks`
**Kab use karein**: Jab **chhote chhote tasks** mein todna ho kaam ko
**Kya karta hai**: Bade kaam ko small actionable tasks mein convert karta hai
**Example**:
```bash
/sp.tasks "Create user authentication system"
```
**Matlab**: "Is bade kaam ko **chhote tasks** mein tod do"

**Output example**:
```
Task 1: Design database schema for users
Task 2: Create signup API endpoint
Task 3: Create login API endpoint
Task 4: Add JWT token generation
Task 5: Create password reset functionality
Task 6: Write unit tests
```

---

### 6️⃣ `/sp.implement` ya `/sp.implementations`
**Kab use karein**: Jab actual **code likhna** shuru karna ho
**Kya karta hai**: Specifications ke hisaab se actual code generate karta hai
**Example**:
```bash
/sp.implement "User login API from specifications"
```
**Matlab**: "Ab jo plan banaya tha, uska **actual code** likh do"

**Use case**:
- Jab planning complete ho
- Ready to code ho
- Specifications clear ho chuki hain

---

## 🎯 **Typical Workflow (Ek Real Project)**

Maan lo aap **Food Delivery App** bana rahe hain:

### **Step 1: Constitution** 
```bash
/sp.constitution "Food delivery app - React Native mobile app + Node.js backend"
```
**Output**: Tech stack, coding standards, project structure

---

### **Step 2: Specifications**
```bash
/sp.specify "Restaurant listing with search and filters"
```
**Output**: 
- Search by name, cuisine, location
- Filters: price range, ratings, delivery time
- Display: restaurant cards with image, name, rating, delivery fee

---

### **Step 3: Clarify** (agar confusion ho)
```bash
/sp.clarify "Real-time tracking kaise implement karein?"
```
**Output**: WebSocket vs Polling comparison, best approach

---

### **Step 4: Plan**
```bash
/sp.plan "Complete restaurant module in 2 weeks"
```
**Output**: Day-wise breakdown of tasks

---

### **Step 5: Tasks**
```bash
/sp.tasks "Restaurant listing page"
```
**Output**: 
- Task 1: Create restaurant API
- Task 2: Design UI components
- Task 3: Implement search functionality
- Task 4: Add filters
- Task 5: Connect with backend

---

### **Step 6: Implement**
```bash
/sp.implement "Restaurant search API"
```
**Output**: Actual working code

---

## 📊 **Quick Comparison**

| Command | Kab Use Karein | Output Kya Milega |
|---------|----------------|-------------------|
| `constitution` | Project start | Overall rules & structure |
| `specify` | Feature planning | Detailed requirements |
| `clarify` | Confusion ho | Clear explanation |
| `plan` | Timeline chahiye | Step-by-step roadmap |
| `tasks` | Work divide karni | Small actionable tasks |
| `implement` | Code likhna | Actual working code |

---

## 💡 **Pro Tips**

1. **Order matter karta hai**: Constitution → Specify → Plan → Tasks → Implement
2. **Clarify** kisi bhi step mein use kar sakte hain
3. Har command ke baad output **save kar lein** for reference
4. Specifications clear hone ke baad hi implement karein

---
