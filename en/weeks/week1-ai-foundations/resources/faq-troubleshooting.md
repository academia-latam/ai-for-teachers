# Week 1 FAQ & Troubleshooting Guide

**Common Questions and Solutions for Getting Started with AI Tools**

---

## 🔧 Technical Issues

### Q: ChatGPT says "I'm at capacity right now" or won't load. What do I do?

**A:** This happens when ChatGPT has too many users. Try these solutions:

1. **Wait 10-15 minutes and refresh** - Traffic often clears quickly
2. **Use ChatGPT during off-peak hours** - Early morning or late evening in your timezone
3. **Try an alternative AI tool:**
   - **Claude:** [https://claude.ai](https://claude.ai) (free, works very similarly)
   - **Google Gemini:** [https://gemini.google.com](https://gemini.google.com) (free, integrates with Google Workspace)
4. **Consider ChatGPT Plus** ($20/month) - Guarantees access even during peak times (optional, not required for this course)

---

### Q: My school/district blocks ChatGPT. What can I do?

**A:** Several options:

**Option 1: Use an approved alternative**
Check with your tech coordinator if your district has approved:
- Microsoft Copilot (often available through Office 365 Education)
- Google Gemini (may be available through Google Workspace)
- Education-specific tools like MagicSchool AI, Brisk Teaching, or Eduaide

**Option 2: Use on personal device/network**
- Access ChatGPT on your phone or home computer using personal internet
- Complete coursework outside of school network
- Create materials at home, then use them at school

**Option 3: Advocate for access**
- Share this course's UNESCO alignment and ethical framework with administrators
- Explain that AI literacy is an essential professional competency
- Propose a pilot program with appropriate safeguards

**Note:** Many districts are updating policies to allow teacher use of AI tools for planning and professional purposes (but not with student data). Ask about current policy!

---

### Q: I created a ChatGPT account, but it's asking for my phone number. Do I have to provide it?

**A:** Yes, ChatGPT requires phone verification to prevent abuse. This is standard for most AI tools.

**Privacy concerns?**
- OpenAI's privacy policy states phone numbers are used only for verification, not marketing
- You can use a Google Voice number if you prefer not to share your primary number
- Alternative: Use Claude.ai (anthropic.com), which may have different verification requirements

---

### Q: ChatGPT stopped responding mid-answer. What happened?

**A:** This usually means:

1. **Connection issue** - Refresh the page and try again
2. **Response too long** - ChatGPT hit its output limit. Prompt: "Continue where you left off" or "Finish the response"
3. **Content filter triggered** - Rarely, if the topic is flagged as potentially sensitive. Rephrase your prompt.

**Prevention tip:** For very long outputs (like a full unit plan), ask ChatGPT to generate it in sections:
```
Create a 5-day unit plan on fractions. Start with Day 1 only. I'll ask you for Day 2 next.
```

---

### Q: How do I save my ChatGPT conversations?

**A:**

**Option 1: ChatGPT saves automatically**
- All conversations appear in your sidebar (left side of screen)
- Click on a conversation to return to it
- Rename conversations by clicking the pencil icon

**Option 2: Export manually**
- Copy and paste the conversation into a Google Doc or Word file
- Use a browser extension like "ChatGPT to Markdown" for easier exporting
- Screenshot important outputs

**Option 3: Share link (ChatGPT Plus only)**
- Click the share icon to create a link to your conversation

**Pro tip:** For important prompts/outputs (like assignments), always copy into a separate document—don't rely solely on ChatGPT's conversation history.

---

## 🤔 Using AI Effectively

### Q: ChatGPT gave me a wrong answer. How do I know when it's making things up?

**A:** Great question! LLMs can "hallucinate" (generate plausible-sounding but false information). Here's how to catch it:

**Red flags for hallucinations:**
- ⚠️ Very specific claims without sources (dates, names, statistics)
- ⚠️ Unusual or surprising "facts" you haven't heard before
- ⚠️ Inconsistencies within the response
- ⚠️ Topics outside the AI's training data (very recent events, obscure subjects)

**How to verify:**
- ✅ Cross-reference factual claims with reliable sources (textbooks, .edu/.gov websites, encyclopedias)
- ✅ Google specific facts, especially dates, definitions, and formulas
- ✅ Ask ChatGPT to explain its reasoning: "How do you know that?"
- ✅ If generating content for subjects you don't know well (e.g., you teach ELA but need a science example), have a colleague review

**High-risk areas for errors:**
- Scientific formulas and processes
- Historical dates and events
- Math problems (ChatGPT can make calculation errors)
- Current events (training data cuts off in 2023 for most models)

**Lower-risk uses:**
- Generating discussion questions
- Brainstorming ideas
- Formatting and organizing information
- Creating templates

**Golden rule:** For anything students will learn as "fact," verify before teaching.

---

### Q: My prompt didn't work. The output was terrible. What did I do wrong?

**A:** Prompts are a skill! If output quality was poor, try:

**1. Add more specificity**
- Instead of: "Create a lesson about math"
- Try: "Create a 45-minute lesson plan for 4th graders on adding fractions with unlike denominators, including a hands-on activity"

**2. Give context about students**
- Add: "My students are mixed abilities, with several ELL learners who benefit from visual supports"

**3. Specify format/components**
- Add: "Include: hook, direct instruction, guided practice, independent practice, exit ticket"

**4. Provide examples**
- "Here's the style I like: [paste example]. Create 5 more like this."

**5. Iterate with follow-up prompts**
- First output not great? Ask: "Can you make this more engaging?" or "Can you simplify the vocabulary for struggling readers?"

**See:** [Sample Prompts Library](./sample-prompts.md) for templates.

---

### Q: How long should my prompts be?

**A:** There's no perfect length, but as a guideline:

**Too short (ineffective):**
```
Create a lesson plan about science.
```
*(Missing: grade, topic, format, student context)*

**Just right:**
```
Create a 50-minute lesson plan for 5th grade students on the scientific method. Include a hook, direct instruction, a hands-on experiment, and an exit ticket. My students love experiments but struggle with writing lab reports.
```
*(~30-40 words, includes essentials)*

**Can be longer if needed:**
```
Create a 50-minute lesson plan for 5th grade students on the scientific method. Include:
- Engaging hook that connects to their daily lives
- Direct instruction on the 6 steps of the scientific method
- A simple hands-on experiment (materials limited to classroom basics like paper, water, tape)
- Guided practice where students write a hypothesis
- Exit ticket assessing understanding of the steps

Context: My students are in a Title I urban school, mixed abilities, many ELL students. They love hands-on activities but find abstract concepts challenging. This is their first introduction to the scientific method, so keep explanations simple and use lots of examples.
```
*(~100 words, very detailed—great for complex requests)*

**Rule of thumb:** Include enough detail that a human colleague could fulfill your request. If a colleague would need to ask clarifying questions, so will the AI.

---

### Q: Can I use the same prompt more than once?

**A:** Yes! In fact, running the same prompt multiple times can be useful:

**Why you might do this:**
- Generate multiple versions and pick the best elements from each
- See range of possibilities
- Compare how different AI tools (ChatGPT vs. Claude vs. Gemini) respond

**Note:** You'll usually get slightly different responses each time because LLMs incorporate some randomness (called "temperature") to avoid repetitive outputs.

**Pro tip:** If you find a prompt that works really well, save it! Create a personal "prompt library" document for reuse.

---

## 📖 Course & Assignment Questions

### Q: Do I need to use ChatGPT specifically, or can I use other AI tools?

**A:** **You can use any of these three tools:**
- ChatGPT (OpenAI) - Most popular, free version available
- Claude (Anthropic) - Excellent for detailed, structured content
- Google Gemini - Integrates with Google Workspace

**All three are covered in this course.** Choose based on:
- What's accessible on your school network
- Personal preference
- Specific task (Week 2 will compare strengths/weaknesses)

**For Week 1 assignment:** Use whichever tool you prefer. Just note which one you used in your reflection.

---

### Q: I completed the async content but couldn't attend the live workshop. Will I still pass?

**A:** Yes! Live workshops are highly recommended but not mandatory.

**What to do:**
- Watch the workshop recording (posted within 24 hours)
- Complete all async content (videos, readings, activities)
- Submit the assignment
- You can still earn full credit

**Attendance requirement:** Attend (or watch recordings of) at least **4 of 6 live workshops** for certification.

---

### Q: The assignment says to "actually use" my AI-generated content in teaching. What if I'm not teaching this week?

**A:** Options:

**Option 1: Create for future use**
- Generate something you'll use when you return to teaching
- Note in your reflection: "I created this for [upcoming unit] and will use it on [date]"
- Reflect on the creation process and your predictions for how it will work

**Option 2: Try it with a non-classroom audience**
- Use with a tutoring student
- Try with your own children
- Ask a colleague or family member to be a "test student"

**Option 3: Hypothetical reflection (less ideal)**
- Create the resource and reflect on how you *think* it would work
- Be honest that you didn't actually use it yet
- May result in slightly lower score on "implementation" reflection questions

**Best practice:** Most teachers can find *some* use for AI this week—even if just sending a parent email or creating materials for next week!

---

### Q: Can I work with a colleague who's also taking the course?

**A:** Yes, with limits:

**Allowed collaboration:**
- ✅ Discussing prompt strategies
- ✅ Sharing general tips and troubleshooting
- ✅ Comparing how different prompts worked
- ✅ Giving each other feedback

**NOT allowed:**
- ❌ Submitting identical or nearly identical work
- ❌ Copying each other's prompts or reflections
- ❌ Having someone else complete your assignment

**Rule:** Your final submission must be your own unique work. If you brainstorm together, create different final products.

---

### Q: What if I'm really struggling with technology and can't figure out ChatGPT?

**A:** We're here to help! Resources:

**1. Check video tutorials**
- Week 1 includes step-by-step video demos
- Rewatch as many times as needed

**2. Use the discussion forum**
- Post your question—instructors and peers will help
- Often someone else has had the same issue

**3. Attend office hours**
- [Schedule TBD] - Get one-on-one help

**4. Email tech support**
- support@academiaconsulting.com
- We can do a screen-share session to troubleshoot

**5. Ask a tech-savvy colleague or family member**
- Sometimes a 10-minute tutorial from someone you know helps!

**Remember:** This course assumes NO prior AI experience. If you can use Google, you can learn this. Don't give up!

---

## 🛡️ Privacy & Ethics Questions

### Q: Is it safe to use ChatGPT with student information?

**A:** **No, not the free public version.**

**Free ChatGPT:** Do NOT input:
- ❌ Student names
- ❌ Student IDs
- ❌ Identifiable student work (with names attached)
- ❌ Specific student IEPs or health information
- ❌ Photos of students

**What IS safe to input:**
- ✅ Generic student descriptions ("I have a student who struggles with reading")
- ✅ Anonymized student work (use fake names like "Student A")
- ✅ General class context ("My 4th graders are mixed abilities, 40% ELL")

**If your district has ChatGPT Enterprise or a FERPA-compliant tool:** Check your district's data privacy policy—these versions may allow some student data.

**Golden rule:** Treat free ChatGPT like a public website. Don't put anything there you wouldn't post on Facebook.

---

### Q: Do I need to tell students if I used AI to create materials?

**A:** Best practice is **transparency**, but the level depends on context:

**Recommended:**
- Tell students (age-appropriately) that you sometimes use AI tools to help create materials
- Model ethical AI use by being open about it
- For older students (middle/high school), explain that you review and edit AI content before using it

**Example script for students:**
> "I used ChatGPT to help me create these discussion questions, but I reviewed every one to make sure they were appropriate for our class and aligned with what we've been learning."

**Not required but builds trust:**
- Explaining your process helps students understand appropriate AI use
- Positions you as a role model for ethical technology use

**Less critical to mention:**
- AI-assisted administrative tasks (parent emails, substitute plans) where students aren't the audience

**Week 5 covers teaching students about AI ethics in depth!**

---

### Q: If I use AI-generated content in my classroom, do I need to cite it?

**A:** For classroom use, **no formal citation needed**, but:

**Internal classroom materials (handouts, slides, worksheets):**
- No citation required
- Optional: Add a note like "Questions generated with AI assistance"

**Published or shared materials (presentations at conferences, blog posts, published lessons):**
- Follow the venue's guidelines on AI citation
- Example citation: "Lesson plan created with assistance from ChatGPT (OpenAI, 2024)"

**Student assignments:**
- Different rules apply (students generally should NOT use AI unless you explicitly allow it)
- Week 3 covers academic integrity policies in depth

---

## 🎓 Learning & Growth Questions

### Q: I feel overwhelmed. Is this normal?

**A:** **Absolutely normal!** You're learning a completely new skill set. Tips for managing overwhelm:

**1. Start small**
- Don't try to AI-ify your entire teaching practice at once
- Pick ONE task this week to try with AI
- Build confidence gradually

**2. Remember the course is scaffolded**
- Week 1 is foundations—you're not expected to be an expert yet
- Each week builds on the last
- By Week 6, this will feel much more natural

**3. Focus on "Use It Monday"**
- The goal is practical application, not perfection
- One good classroom resource this week = success

**4. Connect with peers**
- Discussion forum is full of teachers feeling the same way
- Share struggles and solutions

**5. Take breaks**
- Don't binge all content at once
- Spread learning over the week

**6. Ask for help**
- No question is too basic
- Instructors and peers want you to succeed

**Growth mindset reminder:** Everyone starts as a beginner. The teachers who succeed with AI aren't necessarily "tech people"—they're people who experiment, make mistakes, and keep trying.

---

### Q: I'm excited about AI, but some of my colleagues are very skeptical. How do I talk to them?

**A:** Great question! Tips for productive conversations:

**1. Acknowledge concerns as valid**
- Don't dismiss fears about student cheating, job loss, or inaccuracy
- "I hear you—those are important concerns. This course addresses them head-on."

**2. Share your learning**
- "I'm taking a course that focuses on ethical, human-centered AI use. Want to hear what I'm learning?"
- Show them your Week 1 assignment—concrete example is more persuasive than abstract arguments

**3. Emphasize teacher agency**
- "AI is a tool I control, not something replacing my judgment. I review everything before using it."

**4. Focus on time savings**
- "I used AI to create differentiated reading passages in 5 minutes. That used to take me 30 minutes. Now I have more time for students."

**5. Invite them to experiment**
- "Want to try creating one thing together? I can show you how."

**6. Don't push**
- Some colleagues need time to come around
- Your successful use of AI will speak louder than any argument

**Remember:** Leading by example is more effective than convincing through debate.

---

## ❓ Still Have Questions?

**Discussion Forum:** [Link] - Post questions, get answers from instructors and peers

**Email Instructors:** instructors@academiaconsulting.com (24-48 hour response time)

**Office Hours:** [Schedule TBD]

**Tech Support:** support@academiaconsulting.com

---

**Don't let a technical issue or question stop your progress! Reach out—we're here to help you succeed.**
