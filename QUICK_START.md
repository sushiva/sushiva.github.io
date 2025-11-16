# ⚡ QUICK START CUSTOMIZATION CHECKLIST

Use this checklist to quickly personalize your portfolio. Work through each section in order.

## 📝 Step 1: Personal Info (5 minutes)

**File: index.html**

| Line | What to Change | Example |
|------|----------------|---------|
| 26 | Navigation logo name | `<a href="#home">Shiva</a>` → Your name |
| 49 | Hero section name | `Hi, I'm <span class="gradient-text">Shiva</span>` |
| 57 | Professional titles | `Machine Learning Engineer \| Data Science \| AI Systems` |
| 60-63 | Bio paragraph | Write 2-3 sentences about yourself |
| 658 | Footer name | `&copy; 2025 Shiva` → Your name |

✅ **Done? Test it:** Open index.html in browser - does your name appear correctly?

---

## 🔗 Step 2: Links (3 minutes)

**File: index.html**

Find and replace ALL instances of:

```
yourusername → your_actual_username
your.email@example.com → your_real_email@example.com
```

**Specific lines to check:**
- Line 71-83: Hero social links
- Line 605-628: Contact section links  
- Line 660-668: Footer links

✅ **Done? Test it:** Click each link - do they go to YOUR profiles?

---

## 👤 Step 3: Profile Image (2 minutes)

**File: index.html, Line 93-98**

**Option A - Use your photo:**
```html
<img src="profile-photo.jpg" 
     alt="Your Name" 
     style="width: 100%; height: 100%; object-fit: cover; border-radius: var(--radius-xl);">
```

**Option B - Keep placeholder (for now):**
Leave as is, update later.

**To add photo:**
1. Resize photo to 400x400px
2. Save as `profile-photo.jpg` in same folder
3. Replace the placeholder code

✅ **Done?** Your photo appears in hero section (or placeholder looks good)

---

## 📖 Step 4: About Section (5 minutes)

**File: index.html, Lines 106-134**

1. **Update bio (3 paragraphs):**
   - Paragraph 1: Who you are, what you do
   - Paragraph 2: Your focus areas, current work
   - Paragraph 3: Personal touch, interests

2. **Update stats:**
   - Line 124: Number of ML projects (10+ → your number)
   - Line 128: Years of experience (2+ → your years)
   - Line 132: Technologies mastered (5+ → your count)

✅ **Done?** Read your About section - does it sound like you?

---

## 💼 Step 5: Experience Timeline (10 minutes)

**File: index.html, Lines 141-189**

For **each job/education**, create a timeline item:

```html
<div class="timeline-item">
    <div class="timeline-dot"></div>
    <div class="timeline-content">
        <h3>Job Title / Degree</h3>
        <p class="timeline-company">Company / University</p>
        <p class="timeline-date">Start Date - End Date</p>
        <ul class="timeline-description">
            <li>Key achievement 1 with numbers/impact</li>
            <li>Key achievement 2 with numbers/impact</li>
            <li>Key achievement 3 with numbers/impact</li>
        </ul>
    </div>
</div>
```

**Tips:**
- Most recent first (top)
- Include 3-4 bullet points per role
- Use action verbs: "Built", "Deployed", "Achieved"
- Add metrics: "Improved accuracy by 15%"

✅ **Done?** Timeline shows your career progression clearly?

---

## 🎯 Step 6: Skills (7 minutes)

**File: index.html, Lines 207-360**

**For each skill category:**

1. Update skill name
2. Set honest percentage (don't inflate!)
3. Match percentage in TWO places:

```html
<div class="skill-bar">
    <div class="skill-info">
        <span>Python</span>
        <span>95%</span>  <!-- ← Here (what users see) -->
    </div>
    <div class="progress-bar">
        <div class="progress" style="width: 95%"></div>  <!-- ← And here -->
    </div>
</div>
```

**Percentage Guide:**
- 95-100%: Expert, can teach others
- 85-94%: Very proficient, daily use
- 75-84%: Comfortable, regular use
- 65-74%: Working knowledge
- Below 65%: Don't list it

**Categories to customize:**
- Machine Learning & AI (4 skills)
- Programming (4 skills)
- Frameworks & Libraries (4 skills)
- MLOps & Deployment (4 skills)

✅ **Done?** All percentages honest and match in both places?

---

## 🚀 Step 7: Projects (20 minutes - MOST IMPORTANT)

**File: index.html, Lines 377-570**

**For EACH project (aim for 4-6 projects):**

### Template to Copy:

```html
<div class="project-card">
    <div class="project-image">
        <img src="PROJECT_IMAGE.jpg" alt="Project Name">
        <div class="project-overlay">
            <a href="DEMO_LINK" class="project-link">
                <i class="fas fa-external-link-alt"></i>
            </a>
            <a href="GITHUB_LINK" class="project-link">
                <i class="fab fa-github"></i>
            </a>
        </div>
    </div>
    <div class="project-content">
        <div class="project-tags">
            <span class="tag">Tech 1</span>
            <span class="tag">Tech 2</span>
            <span class="tag">Tech 3</span>
        </div>
        <h3>Project Title</h3>
        <p>
            Brief description (2-3 sentences). Focus on: 
            What problem you solved, how you solved it, 
            and the impact/results.
        </p>
        <div class="project-tech">
            <i class="fab fa-python"></i>
            <i class="fas fa-brain"></i>
            <i class="fab fa-docker"></i>
        </div>
        <ul class="project-highlights">
            <li><i class="fas fa-check"></i> Key metric 1 (e.g., "92% accuracy")</li>
            <li><i class="fas fa-check"></i> Key metric 2 (e.g., "<100ms latency")</li>
            <li><i class="fas fa-check"></i> Key feature 3 (e.g., "Real-time API")</li>
        </ul>
    </div>
</div>
```

### Your Projects to Add:

**Project 1: Traffic Prediction System**
- Image: Traffic/urban visualization
- Tags: Deep Learning, Time Series, MLOps
- Metrics: Accuracy %, latency, throughput
- GitHub: Your repo link
- Demo: Deployed app link (if available)

**Project 2: Customer Churn Dashboard**
- Image: Dashboard screenshot
- Tags: Classification, Deployment, Dashboard
- Metrics: ROC-AUC, features, predictions/min
- GitHub: Your repo link
- Demo: Streamlit/dashboard link

**Project 3: Add your third project**
**Project 4: Add your fourth project**

### Project Image Options:

**Option A - Use placeholder:**
```
https://via.placeholder.com/600x400/1a1a2e/00d9ff?text=Your+Project+Name
```

**Option B - Use screenshot:**
1. Take screenshot of your project
2. Crop to 600x400px (use [Photopea](https://www.photopea.com/))
3. Save as `project1.jpg`, `project2.jpg`, etc.
4. Reference: `<img src="project1.jpg" alt="Project Name">`

**Option C - Use Unsplash:**
Search relevant images at [unsplash.com](https://unsplash.com)

✅ **Done?** All projects show your best work with metrics and links?

---

## 📧 Step 8: Contact Info (3 minutes)

**File: index.html, Lines 593-628**

| Line | What to Update |
|------|----------------|
| 605 | Your location (city, state, country) |
| 615 | Your email address |
| 625 | Your LinkedIn URL |
| 635 | Your GitHub URL |

**Contact Form:**
- Works out of the box with basic validation
- To actually receive emails, see README section on Formspree/EmailJS
- For now, it shows a success message (check browser console for form data)

✅ **Done?** All contact info correct?

---

## 🎨 Step 9: Colors (Optional - 5 minutes)

**File: styles.css, Lines 6-14**

**Current scheme:** Cyan/Teal (tech/modern)

**Want different colors?** Update these:

```css
:root {
    --primary-color: #00d9ff;      /* Main accent */
    --secondary-color: #ff6b6b;    /* Secondary */
    --accent-color: #4ecdc4;       /* Highlights */
}
```

**Popular alternatives:**

**Professional Blue:**
```css
--primary-color: #3b82f6;
--accent-color: #60a5fa;
```

**Warm Orange:**
```css
--primary-color: #f97316;
--accent-color: #fb923c;
```

**Modern Purple:**
```css
--primary-color: #8b5cf6;
--accent-color: #a78bfa;
```

**Keep current?** Skip this step!

✅ **Done?** Colors look good to you?

---

## ✅ FINAL CHECKLIST (Before Publishing)

Go through this list with index.html open in browser:

- [ ] **Name** appears in navigation, hero, footer
- [ ] **All links** go to YOUR profiles (not "yourusername")
- [ ] **Email address** is correct everywhere
- [ ] **About section** tells your story authentically
- [ ] **Experience** shows your background (3+ items)
- [ ] **Skills** are honest and relevant (remove ones you don't have)
- [ ] **Projects** showcase your best work (4-6 projects minimum)
- [ ] **Project links** all work (GitHub + demos)
- [ ] **Contact info** is accurate
- [ ] **Mobile view** works (resize browser window to 375px wide)
- [ ] **No "TODO" or placeholder text** remains
- [ ] **All sections** have real content (no lorem ipsum)

---

## 🚀 DEPLOYMENT CHECKLIST

Once customization is done:

- [ ] Test in Chrome
- [ ] Test in Firefox  
- [ ] Test on mobile device
- [ ] Run spell check on all text
- [ ] Compress any images you added
- [ ] Choose deployment platform (GitHub Pages recommended)
- [ ] Deploy!
- [ ] Test live site
- [ ] Share on LinkedIn 🎉

---

## 📊 CUSTOMIZATION TIME ESTIMATE

| Section | Time | Priority |
|---------|------|----------|
| Personal Info | 5 min | ⭐⭐⭐⭐⭐ Critical |
| Links | 3 min | ⭐⭐⭐⭐⭐ Critical |
| Profile Image | 2 min | ⭐⭐⭐⭐ High |
| About | 5 min | ⭐⭐⭐⭐⭐ Critical |
| Experience | 10 min | ⭐⭐⭐⭐⭐ Critical |
| Skills | 7 min | ⭐⭐⭐⭐ High |
| **Projects** | **20 min** | **⭐⭐⭐⭐⭐ Critical** |
| Contact | 3 min | ⭐⭐⭐⭐⭐ Critical |
| Colors | 5 min | ⭐⭐ Optional |
| **TOTAL** | **~60 min** | |

**Minimum viable portfolio:** 45 minutes (skip colors, use placeholder images)
**Polished portfolio:** 90 minutes (custom images, colors, extra polish)

---

## 💡 TIPS FOR SUCCESS

1. **Start with projects** - they're most important
2. **Use metrics everywhere** - "Achieved 92% accuracy", not just "Built a model"
3. **Keep it honest** - don't inflate skills or experience
4. **Mobile first** - test on phone constantly
5. **Get feedback** - show to a friend before publishing
6. **Update regularly** - add new projects as you complete them
7. **Proofread** - typos hurt credibility

---

## 🆘 STUCK? QUICK FIXES

**"I don't have 4-6 projects!"**
→ Include course projects, personal experiments, Kaggle competitions, or recreate tutorials with your own twist

**"My skills aren't at 90%!"**
→ That's fine! 60-70% is good for things you're learning. Focus on what you DO know.

**"I don't have a professional photo!"**
→ Use the icon placeholder for now. Take a good photo later and swap it in.

**"My projects aren't deployed!"**
→ GitHub links are fine! Deploy one project (use Streamlit Cloud - free) if possible.

**"This seems overwhelming!"**
→ Start with the ⭐⭐⭐⭐⭐ Critical items only. Polish later.

---

## ✨ YOU'VE GOT THIS!

Your portfolio doesn't need to be perfect to publish. 

**The goal:** Showcase your ML skills professionally.

**The result:** A portfolio that gets you interviews.

Start customizing now! 🚀

---

**Need the detailed README?** → See `README.md` for full documentation

**Ready to deploy?** → Follow deployment guide in `README.md`
