# My wireframes

> [home](./README.md)

# App Wireframes: AI Literacy for All (ALFA)

## App Name: ALFA – AI Literacy for All

### Core Functionalities Addressed:

1. Student onboarding & language selection
2. Interactive AI lessons (offline-capable)
3. Hands-on AI tool practice (prompt engineering, content generation)
4. Local career pathway discovery
5. Progress tracking & assessments
6. Teacher dashboard for classroom management

---

## Screen 1: Language & Onboarding

**Screen Title:** Karibu! Welcome to ALFA

**Visual Description:**
- Full-screen illustration of Kenyan students learning together
- Two large buttons at center
- Simple, friendly interface with warm colors (orange, green, white)

**Content:**

```
┌─────────────────────────────────────────┐
│                                         │
│                    🌍                   │
│                                         │
│            KARIBU! WELCOME              │
│                                         │
│     Choose your preferred language      │
│                                         │
│    ┌─────────────────────────────┐     │
│    │         🇰🇪  KISWAHILI        │     │
│    └─────────────────────────────┘     │
│                                         │
│    ┌─────────────────────────────┐     │
│    │         🇬🇧  ENGLISH          │     │
│    └─────────────────────────────┘     │
│                                         │
│    ┌─────────────────────────────┐     │
│    │      🔄  OFFLINE MODE         │     │
│    │   Download lessons for later │     │
│    └─────────────────────────────┘     │
│                                         │
│         Already have an account?        │
│               Sign In                   │
└─────────────────────────────────────────┘
```

**Functionality:**
- User selects Kiswahili or English
- Option to download lessons for offline access
- New user sign-up or existing user login

---

## Screen 2: Student Dashboard (Home)

**Screen Title:** Mwenyewe / My Learning

**Visual Description:**
- Bottom navigation bar (Home, Lessons, Tools, Profile)
- Welcome message with student name
- Progress circle showing overall completion
- Module cards with lesson thumbnails
- "Continue where you left off" section

**Content:**

```
┌─────────────────────────────────────────┐
│  👋 Habari, Achieng!        🔔  🏆  ⚙️  │
├─────────────────────────────────────────┤
│                                         │
│   Your Progress                         │
│   ┌─────────────────────────────────┐   │
│   │                                  │   │
│   │         🎯 42% Complete          │   │
│   │    ████████░░░░░░░░░░░░░░░░░    │   │
│   │                                  │   │
│   └─────────────────────────────────┘   │
│                                         │
│   Continue Learning                     │
│   ┌─────────────────────────────────┐   │
│   │ 📱 Module 3: What is AI?         │   │
│   │ 4 minutes remaining • 80% done  │   │
│   │         [RESUME]                 │   │
│   └─────────────────────────────────┘   │
│                                         │
│   Available Modules                     │
│   ┌──────┐ ┌──────┐ ┌──────┐          │
│   │🤖    │ │💬    │ │📊    │          │
│   │What  │ │Prompt│ │Data  │          │
│   │is AI?│ │Eng.  │ │Lit.  │          │
│   │🔒    │ │🔓    │ │🔒    │          │
│   └──────┘ └──────┘ └──────┘          │
│                                         │
│   ┌──────┐ ┌──────┐ ┌──────┐          │
│   │🎨    │ │⚖️    │ │💼    │          │
│   │Gen   │ │AI    │ │AI    │          │
│   │Content│ │Ethics│ │Careers│          │
│   │🔒    │ │🔒    │ │🔓    │          │
│   └──────┘ └──────┘ └──────┘          │
└─────────────────────────────────────────┘
│  🏠      📚      🛠️      👤            │
└─────────────────────────────────────────┘
```

**Functionality:**
- Shows overall progress
- Quick resume of last lesson
- Module grid (locked/unlocked based on progression)
- Bottom navigation to key sections

---

## Screen 3: Interactive Lesson (AI Tool Practice)

**Screen Title:** Module 3: What is Generative AI?

**Visual Description:**
- Split screen: lesson content on top, interactive AI tool at bottom
- Example prompt box with suggested prompts
- AI response area (simulated for offline mode, real API when online)
- "Try it yourself" sandbox mode

**Content:**

```
┌─────────────────────────────────────────┐
│  ← Back  Module 3 of 12  ●●●○○  (60%)   │
├─────────────────────────────────────────┤
│                                         │
│   📖 What is Generative AI?             │
│                                         │
│   Generative AI creates new content—    │
│   text, images, music, code—based on    │
│   patterns it learned from existing     │
│   data. It's like having a smart        │
│   assistant who never gets tired.       │
│                                         │
├─────────────────────────────────────────┤
│   ✨ TRY IT YOURSELF                     │
│                                         │
│   ┌─────────────────────────────────┐   │
│   │ 💬 Write a prompt for the AI:    │   │
│   │                                 │   │
│   │ "Write a short product          │   │
│   │  description for handmade        │   │
│   │  beaded earrings in 2 sentences" │   │
│   │                                 │   │
│   └─────────────────────────────────┘   │
│                                         │
│         [🔊 SPEAK]  [✨ GENERATE]       │
│                                         │
│   ┌─────────────────────────────────┐   │
│   │ 🤖 AI RESPONSE:                  │   │
│   │                                 │   │
│   │ "Beautiful handmade beaded      │   │
│   │ earrings crafted by Kenyan      │   │
│   │ artisans. Each pair is unique—  │   │
│   │ perfect for adding color to     │   │
│   │ any outfit."                    │   │
│   │                                 │   │
│   └─────────────────────────────────┘   │
│                                         │
│   ✅ Did the AI understand the task?    │
│      [YES] [NO] [SHOW ME HOW TO IMPROVE]│
│                                         │
│                 [NEXT LESSON →]         │
└─────────────────────────────────────────┘
```

**Functionality:**
- Lesson content with audio read-aloud option
- Interactive AI sandbox for hands-on practice
- Speech-to-text for low-literacy users
- Self-assessment question after each tool use
- Works offline with simulated AI responses

---

## Screen 4: Career Pathways Discovery

**Screen Title:** Fursa Zako / Your Opportunities

**Visual Description:**
- Based on student's interests, location, and skills
- AI-generated career matches
- Each card shows: job title, local relevance, required skills, nearby training
- "I'm interested" button to save and learn more

**Content:**

```
┌─────────────────────────────────────────┐
│  ← Back         Fursa Zako              │
├─────────────────────────────────────────┤
│                                         │
│   Based on your interests (Farming,     │
│   Technology, Business) and location    │
│   (Kisumu), here are AI-augmented       │
│   careers near you:                     │
│                                         │
│   ┌─────────────────────────────────┐   │
│   │ 🌾 AI-PRECISION FARMING ASSISTANT│   │
│   │ 📍 Kisumu & surrounding counties │   │
│   │ 🔧 Skills: Data entry, sensors,  │   │
│   │    mobile apps                    │   │
│   │ 🏫 Training: Jitume Hub Kisumu   │   │
│   │ 📈 Demand: HIGH (40+ openings)   │   │
│   │         [👍 I'M INTERESTED]       │   │
│   └─────────────────────────────────┘   │
│                                         │
│   ┌─────────────────────────────────┐   │
│   │ 🤖 AI CONTENT CREATOR            │   │
│   │ 📍 Remote / Anywhere in Kenya    │   │
│   │ 🔧 Skills: Prompt engineering,   │   │
│   │    image generation, translation │   │
│   │ 🏫 Training: Online (free)       │   │
│   │ 📈 Demand: GROWING               │   │
│   │         [👍 I'M INTERESTED]       │   │
│   └─────────────────────────────────┘   │
│                                         │
│   ┌─────────────────────────────────┐   │
│   │ 🛍️ JUA KALI AI BUSINESS ASSISTANT│   │
│   │ 📍 Available in all 47 counties  │   │
│   │ 🔧 Skills: Mobile apps, market   │   │
│   │    pricing, customer service     │   │
│   │ 🏫 Training: On-app + Jitume Hub │   │
│   │ 📈 Demand: 17M potential clients │   │
│   │         [👍 I'M INTERESTED]       │   │
│   └─────────────────────────────────┘   │
│                                         │
│   [💾 SAVE ALL TO MY PATH] [🔄 REFRESH] │
└─────────────────────────────────────────┘
```

**Functionality:**
- AI matches careers to student profile
- Shows local opportunities (county-specific)
- Links directly to training programs
- Save careers to personalized learning path
- Refreshes as student completes more modules

---

## Screen 5: Assessment & Badges

**Screen Title:** Cheo Chako / Your Badges

**Visual Description:**
- Grid of earned and locked badges
- Quiz/assessment interface
- Progress bar to next level
- Share achievements button

**Content:**

```
┌─────────────────────────────────────────┐
│  ← Back         Cheo Chako              │
├─────────────────────────────────────────┤
│                                         │
│   Level 2: AI Explorer                   │
│   ████████░░░░░░░░░░░░░░░░░ 42%         │
│   Next badge: 3 more lessons            │
│                                         │
│   🏆 EARNED BADGES                      │
│   ┌──────┐ ┌──────┐ ┌──────┐          │
│   │🤖    │ │💬    │ │📱    │          │
│   │AI    │ │Prompt│ │First │          │
│   │Aware │ │Novice│ │Login │          │
│   └──────┘ └──────┘ └──────┘          │
│                                         │
│   🔒 LOCKED BADGES                      │
│   ┌──────┐ ┌──────┐ ┌──────┐          │
│   │🎨    │ │⚖️    │ │💼    │          │
│   │Gen   │ │AI    │ │Career│          │
│   │Pro   │ │Ethics│ │Ready │          │
│   └──────┘ └──────┘ └──────┘          │
│                                         │
│   📝 QUIZ: Module 3 Assessment          │
│                                         │
│   Question 4 of 10:                     │
│   "What is prompt engineering?"         │
│                                         │
│   ○ A) Building computer hardware       │
│   ○ B) Writing effective instructions  │
│   │      for AI                        │
│   ○ C) Fixing electrical wiring         │
│   ○ D) Designing websites               │
│                                         │
│         [BACK]  [NEXT →]                │
│                                         │
│   ┌─────────────────────────────────┐   │
│   │  📤 Share your progress         │   │
│   │  [SHARE TO WHATSAPP] [SAVE AS PDF]│ │
│   └─────────────────────────────────┘   │
└─────────────────────────────────────────┘
```

**Functionality:**
- Gamified progress tracking
- Quiz assessments after each module
- Earn badges and level up
- Share achievements on WhatsApp (social proof, motivation)
- Export progress as PDF for job applications

---

## Screen 6: Teacher Dashboard (Classroom Management)

**Screen Title:** Darasa / Classroom

**Visual Description:**
- Teacher login required
- Class roster with student names and progress
- Bulk download of offline lessons
- At-a-glance class performance metrics
- Assignment creation tool

**Content:**

```
┌─────────────────────────────────────────┐
│  👩‍🏫 Mrs. Otieno, Kisumu Primary  │ 🔔  │
├─────────────────────────────────────────┤
│                                         │
│   📊 CLASS OVERVIEW                     │
│                                         │
│   Total Students: 42                    │
│   Average Progress: 38%                 │
│   Offline Access Enabled: Yes (32GB)    │
│                                         │
│   Students Needing Support:             │
│   ┌─────────────────────────────────┐   │
│   │ ⚠️ 12 students below 25%        │   │
│   │    [SEND REMINDER] [VIEW LIST]  │   │
│   └─────────────────────────────────┘   │
│                                         │
│   👨‍🎓 CLASS ROSTER                      │
│                                         │
│   ┌───────────────────────────────────┐ │
│   │ Achieng O.  ████████░░░░ 42%  📱 │ │
│   ├───────────────────────────────────┤ │
│   │ James M.    ██████████░░ 52%  📱 │ │
│   ├───────────────────────────────────┤ │
│   │ Fatima S.   ████░░░░░░░░ 20%  📱 │ │
│   ├───────────────────────────────────┤ │
│   │ Brian K.    ████████████ 62%  📱 │ │
│   └───────────────────────────────────┘ │
│                                         │
│   [VIEW FULL ROSTER →]                  │
│                                         │
│   📥 OFFLINE MANAGEMENT                 │
│   ┌─────────────────────────────────┐   │
│   │ Download all modules for class  │   │
│   │ (2.4 GB)  [DOWNLOAD NOW]        │   │
│   │ Last updated: Today, 8:00 AM    │   │
│   └─────────────────────────────────┘   │
│                                         │
│   📝 ASSIGNMENT                         │
│   ┌─────────────────────────────────┐   │
│   │ "Write a prompt to generate a   │   │
│   │  business name for a Jua Kali   │   │
│   │  salon in your area"            │   │
│   │ Due: Friday                    │   │
│   │         [ASSIGN TO CLASS]       │   │
│   └─────────────────────────────────┘   │
└─────────────────────────────────────────┘
```

**Functionality:**
- At-a-glance class performance
- Identify struggling students
- Bulk download offline lessons for school without internet
- Assign homework and track submissions
- Send reminders via SMS (integrated)

---

## App Navigation Summary

| Screen | Purpose | Key User |
|--------|---------|----------|
| 1. Onboarding | Language selection, offline setup | Student |
| 2. Dashboard | Home, progress, module access | Student |
| 3. Interactive Lesson | Learn AI concepts + practice tools | Student |
| 4. Career Pathways | Discover local AI-augmented jobs | Student |
| 5. Assessments & Badges | Quiz, track progress, earn rewards | Student |
| 6. Teacher Dashboard | Manage class, offline downloads | Teacher |

---

## Technical Requirements Summary

| Requirement | Specification |
|-------------|---------------|
| Offline-first | All lessons downloadable for schools without internet |
| Low bandwidth | Under 50MB per module |
| Basic phone support | SMS/USSD fallback for feature phones |
| Language support | Swahili and English (Sheng coming) |
| Device compatibility | Android 8+, basic smartphones, tablets |
| Teacher tools | Bulk download, class roster, SMS reminders |

---

Would you like me to:
1. Create visual mockups/designs for these wireframes?
2. Add more screens (e.g., parent dashboard, admin panel)?
3. Develop technical specifications for development?
4. Create a user flow diagram connecting all screens?
