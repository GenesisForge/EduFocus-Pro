# Contributing Guide

Thank you for your interest in contributing to EduFocus Pro! This guide explains how you can help improve the project.

---

## 📋 Table of Contents

- [Ways to Contribute](#ways-to-contribute)
- [Before You Start](#before-you-start)
- [Reporting Bugs](#reporting-bugs)
- [Suggesting Features](#suggesting-features)
- [Contributing Translations](#contributing-translations)
- [Improving Documentation](#improving-documentation)
- [Beta Testing](#beta-testing)
- [Educational Feedback](#educational-feedback)
- [Submission Guidelines](#submission-guidelines)
- [Community Guidelines](#community-guidelines)
- [Recognition](#recognition)
- [Contact](#contact)

---

## 🤝 Ways to Contribute

While EduFocus Pro uses a proprietary license, we welcome community contributions in several ways:

### ✅ We Accept

**Bug Reports**
- Report issues you encounter
- Help us identify and fix problems
- Improve stability and reliability

**Feature Suggestions**
- Propose new features or improvements
- Share ideas for better student experiences
- Suggest workflow enhancements

**Translations**
- Translate EduFocus Pro into your language
- Help students worldwide access the tool
- See our [Translation Guide](TRANSLATION_GUIDE.md)

**Documentation Improvements**
- Fix typos and unclear instructions
- Add examples and clarifications
- Improve README and guides

**Beta Testing**
- Test new features before release
- Provide feedback on usability
- Help catch bugs early

**Educational Feedback**
- Share how you use EduFocus Pro
- Suggest pedagogical improvements
- Recommend features for specific learning needs

**User Support**
- Help other users in community discussions
- Answer questions about features
- Share tips and best practices

### ❌ We Cannot Accept

**Direct Code Contributions**
- The codebase is proprietary
- We cannot merge pull requests
- Code contributions require commercial arrangement

**Forks and Derivatives**
- Public forks are not permitted under our license
- Derivative works require written permission
- See [LICENSE](../legal/LICENSE) for details

**Unauthorized Distribution**
- Modified versions cannot be publicly distributed
- Only official versions from Genesis Forge

---

## 🚀 Before You Start

### Check Existing Issues

Before submitting a bug report or feature request:

1. **Search existing reports** - Someone may have already reported it
2. **Check the FAQ** - See [FAQ.md](../user/FAQ.md) for common questions
3. **Review the roadmap** - See [CHANGELOG.md](../history/CHANGELOG.md) for planned features
4. **Read documentation** - Ensure it's not a known limitation

### Understand Our Priorities

**High Priority:**
- Security vulnerabilities
- Data loss bugs
- Accessibility improvements
- Critical usability issues
- Privacy concerns

**Medium Priority:**
- Feature enhancements
- Performance improvements
- UI/UX refinements
- Additional language support

**Lower Priority:**
- Minor cosmetic changes
- Edge case bugs
- Nice-to-have features

---

## 🐛 Reporting Bugs

### Before Reporting

1. **Update to latest version** - Bug may already be fixed
2. **Clear browser cache** - Rule out caching issues
3. **Disable other extensions** - Check for conflicts
4. **Try incognito mode** - Eliminate extension interference
5. **Check FAQ** - See if it's a known issue

### How to Report

**Email:** edufocusbusiness@gmail.com  
**Subject:** Bug Report - [Brief Description]

### Bug Report Template



# Bug Report and Feature Request Guide

## 🐛 Bug Report Template

### Bug Report: [Brief Description]

**ENVIRONMENT:**
* EduFocus Pro Version: [e.g., 3.5.0]
* Chrome Version: [e.g., 120.0.6099.109]
* Operating System: [e.g., Windows 11, macOS 14]
* Browser Language: [e.g., English, Danish]

**DESCRIPTION:**
[Clear description of the bug]

**STEPS TO REPRODUCE:**
1. [First step]
2. [Second step]
3. [Third step]
...

**EXPECTED BEHAVIOR:**
[What should happen]

**ACTUAL BEHAVIOR:**
[What actually happens]

**SCREENSHOTS/VIDEOS:**
[Attach if applicable]

**FREQUENCY:**
[ ] Always
[ ] Sometimes
[ ] Once
[ ] Cannot reproduce consistently

**SEVERITY:**
[ ] Critical - Cannot use the extension
[ ] High - Major feature broken
[ ] Medium - Feature partially works
[ ] Low - Minor inconvenience

**WORKAROUND:**
[If you found a temporary solution, describe it]

**ADDITIONAL CONTEXT:**
[Any other relevant information]

**CONSOLE ERRORS:**
[Open DevTools > Console, copy any errors]

**CONTACT:**
Name: [Optional]
Email: [For follow-up questions]

### Example Bug Report

**Bug Report:** Timer notifications not appearing

**ENVIRONMENT:**
* EduFocus Pro Version: 1.0.0
* Chrome Version: 120.0.6099.109
* Operating System: Windows 11
* Browser Language: English

**DESCRIPTION:**
When a Pomodoro timer completes, no notification appears.
The timer resets but I don't get alerted.

**STEPS TO REPRODUCE:**
1. Open EduFocus Pro
2. Go to Timer tab
3. Start a Pomodoro timer (I used 1 minute for testing)
4. Wait for timer to complete
5. No notification appears

**EXPECTED BEHAVIOR:**
A Chrome notification should appear saying "Pomodoro complete!
Take a 5-minute break."

**ACTUAL BEHAVIOR:**
Timer completes silently, no notification appears. The timer
resets to 25:00 but there's no alert.

**SCREENSHOTS:**
[Attached: screenshot showing timer at 00:00 with no notification]

**FREQUENCY:**
[X] Always

**SEVERITY:**
[X] High - Major feature broken

**WORKAROUND:**
I keep the extension popup open and watch the timer manually.

**ADDITIONAL CONTEXT:**
* Chrome notifications are enabled in system settings
* Other extensions (like Gmail) can send notifications fine
* Notification permission shows as "Allow" in chrome://settings

**CONSOLE ERRORS:**
Uncaught TypeError: Cannot read property 'create' of undefined
at notifyUser (background.js:45)

**CONTACT:**
Name: John Student
Email: john.student@example.com

### What Happens Next

1. **Acknowledgment** - We'll respond within 48 hours
2. **Investigation** - We'll attempt to reproduce the issue
3. **Questions** - We may ask for additional information
4. **Fix Development** - If confirmed, we'll work on a fix
5. **Testing** - Fix will be tested internally
6. **Release** - Fix included in next update
7. **Notification** - You'll be notified when fixed

---

## 💡 Suggesting Features

### Before Suggesting

**Consider:**
- Does it align with EduFocus Pro's mission?
- Would it benefit most students?
- Is it feasible within privacy constraints?
- Does a similar feature already exist?

**Check:**
- [Roadmap in CHANGELOG](../history/CHANGELOG.md) - Already planned?
- [FAQ](../user/FAQ.md) - Already discussed?
- Existing feature requests - Already suggested?

### How to Suggest

**Email:** edufocusbusiness@gmail.com  
**Subject:** Feature Request - [Brief Description]

### Feature Request Template

**Feature Request:** [Brief Description]

**PROBLEM STATEMENT:**
[What problem does this solve? Why do you need this?]

**PROPOSED SOLUTION:**
[Describe your proposed feature]

**USE CASE:**
[How would you use this feature? Specific example scenario]

**TARGET USERS:**
[ ] All students
[ ] Specific age group: [specify]
[ ] Specific learning style: [specify]
[ ] Accessibility need: [specify]
[ ] Other: [specify]

**PRIORITY:**
[ ] Must-have - Cannot use EduFocus Pro effectively without it
[ ] Important - Would significantly improve experience
[ ] Nice-to-have - Would be a welcome addition

**ALTERNATIVES CONSIDERED:**
[Have you tried workarounds? Other tools that do this?]

**IMPLEMENTATION IDEAS:**
[If you have technical ideas, share them - optional]

**MOCKUPS/EXAMPLES:**
[Screenshots from other apps, sketches, etc. - optional]

**ADDITIONAL CONTEXT:**
[Any other relevant information]

**CONTACT:**
Name: [Optional]
Email: [For follow-up discussion]

### Example Feature Request

**Feature Request:** Study group collaboration features

**PROBLEM STATEMENT:**
Many students study in groups and want to coordinate their
study sessions. Currently, there's no way to share study
materials or sync timers with classmates.

**PROPOSED SOLUTION:**
Add optional collaboration features:
* Share flashcard decks with specific people
* Synchronized group Pomodoro sessions
* Shared to-do lists for group projects
* Optional: Real-time collaborative notes

This should remain completely optional and not compromise
privacy for solo users.

**USE CASE:**
Scenario 1: I'm in a study group of 4 people preparing for
finals. We create flashcards individually and want to share
our decks with each other.

Scenario 2: My study buddy and I want to do Pomodoro sessions
together remotely. We'd like synchronized timers so we take
breaks at the same time.

Scenario 3: Group project with 3 classmates. We need a shared
task list to track who's doing what.

**TARGET USERS:**
[X] All students
[X] Specific learning style: Collaborative learners

**PRIORITY:**
[X] Important - Would significantly improve experience

**ALTERNATIVES CONSIDERED:**
* Currently using Google Docs for shared notes
* Using Discord for timer coordination (manual)
* Sharing flashcard decks via JSON export/import (clunky)

**IMPLEMENTATION IDEAS:**
* Could use unique share codes (no accounts needed)
* Time-limited sharing (24 hours, 7 days, etc.)
* All data still stored locally, just synced peer-to-peer
* Easy opt-out - disable collaboration completely in settings

**PRIVACY CONSIDERATIONS:**
* Must remain optional
* No central servers - peer-to-peer only
* Anonymous sharing with codes
* Clear consent before sharing anything

**MOCKUPS/EXAMPLES:**
[Attached: sketch of share dialog and sync indicator]

**ADDITIONAL CONTEXT:**
I know this adds complexity, but many students would benefit.
Could be a separate "Study Groups" feature that's disabled
by default.

**CONTACT:**
Name: Sarah Teacher
Email: sarah.teacher@university.edu

### What Happens Next

1. **Review** - We'll evaluate feasibility and alignment
2. **Discussion** - We may ask clarifying questions
3. **Decision** - Accept, defer, or decline with explanation
4. **Roadmap** - If accepted, added to future plans
5. **Development** - Prioritized based on impact and resources
6. **Release** - Included in future version
7. **Credit** - You'll be credited for the suggestion

---

## 🌍 Contributing Translations

Translation is one of the most valuable contributions you can make!

**See our dedicated [Translation Guide](TRANSLATION_GUIDE.md) for complete instructions.**

**Quick Overview:**

1. **Express interest** - Email edufocusbusiness@gmail.com
2. **Receive materials** - We'll send translation files
3. **Translate** - Work at your own pace (6-9 hours typical)
4. **Submit** - Send completed translation
5. **Review** - We'll review and provide feedback
6. **Testing** - Test build provided for verification
7. **Release** - Included in next version with credit!

**Current languages needed:**
- French, Spanish, Swedish, Norwegian, Polish
- Dutch, Italian, Portuguese, Russian
- Arabic, Chinese, Japanese, Korean, Hindi
- And many more!

---

## 📖 Improving Documentation

Found a typo? Unclear instruction? Confusing explanation?

### Documentation Areas

**User Documentation:**
- README.md - Project overview
- FAQ.md - Frequently asked questions
- SUPPORT.md - Troubleshooting guide
- TERMS_OF_SERVICE.md - Legal terms

**Developer Documentation:**
- CONTRIBUTING.md - This guide
- TRANSLATION_GUIDE.md - Translation instructions
- CODE_OF_CONDUCT.md - Community standards
- SECURITY.md - Security policy

**Legal Documentation:**
- Privacy policies (multiple languages)
- License terms

### How to Suggest Documentation Improvements

**Email:** edufocusbusiness@gmail.com  
**Subject:** Documentation Improvement - [Document Name]

**Include:**
- Document name and section
- Current text (what's unclear)
- Suggested improvement
- Why it would be better

### Example

**Documentation Improvement - FAQ.md**
**SECTION:** "How do I backup my data?"
**CURRENT TEXT:**
"Go to settings and click export."
**ISSUE:**
Too brief, doesn't explain where to find settings or what
format the export is.
**SUGGESTED TEXT:**
"To backup your data:

1. Click the EduFocus Pro icon in your Chrome toolbar
2. Navigate to the Settings tab (gear icon)
3. Scroll to 'Data Management' section
4. Click 'Export All Data'
5. Choose where to save the JSON file
6. Your notes, flashcards, quizzes, and settings will be saved"

**WHY THIS IS BETTER:**
* Step-by-step instructions
* Specifies what's included in export
* Mentions file format (JSON)
* More accessible to non-technical users

---

## 🧪 Beta Testing

Help us test new features before they're released!

### What Beta Testers Do

**Responsibilities:**
- Install and test beta builds
- Use new features in real study scenarios
- Report bugs and usability issues
- Provide feedback on feature design
- Suggest improvements

**Time Commitment:**
- 2-4 hours per beta cycle
- 4-6 beta cycles per year
- Flexible testing schedule
- Test at your own pace

### Beta Testing Process

1. **Receive beta build** - Via email with installation instructions
2. **Install and test** - Use for 1-2 weeks
3. **Submit feedback** - Email observations and issues
4. **Follow-up** - Answer any clarifying questions
5. **Final release** - See your feedback incorporated!

### How to Join

**Email:** edufocusbusiness@gmail.com  
**Subject:** Beta Testing Program

**Include:**
- Why you're interested in beta testing
- Your typical EduFocus Pro usage (daily, weekly, etc.)
- Your technical comfort level (beginner, intermediate, advanced)
- Time availability (hours per month)

### Beta Tester Benefits

- Early access to new features
- Direct influence on development
- Credit in release notes
- "Beta Tester" recognition
- Behind-the-scenes insights

---

## 🎓 Educational Feedback

Are you a teacher, educational professional, or learning specialist?

### We Value Your Expertise

**Share insights on:**
- Pedagogical best practices
- Learning theory applications
- Accessibility for diverse learners
- Age-appropriate features
- Classroom use cases
- Educational effectiveness

### Types of Feedback

**Feature Effectiveness:**
"The spaced repetition algorithm should increase intervals 
more gradually for younger students (ages 12-14)."

**Accessibility:**
"Students with ADHD would benefit from a 'focus mode' that 
hides all tabs except the timer."

**Age Appropriateness:**
"The motivational messages are great for high school students 
but might feel condescending to university students."

**Classroom Integration:**
"Teachers need a way to suggest specific flashcard decks 
without violating student privacy."

**Learning Theory:**
"Adding retrieval practice prompts after note-taking sessions 
would align with cognitive science research."

### How to Share

**Email:** edufocusbusiness@gmail.com  
**Subject:** Educational Feedback

**Include:**
- Your role (teacher, counselor, specialist, etc.)
- Age group/grade level you work with
- Your observations or suggestions
- Research or theory supporting your feedback (if applicable)

---

## 📝 Submission Guidelines

### Email Etiquette

**Subject Lines:**
- Be specific: "Bug: Timer notifications" not "Problem"
- Use correct prefix: "Bug Report -", "Feature Request -", "Translation -"
- Keep it brief but descriptive

**Email Body:**
- Use the templates provided
- Be concise but thorough
- Include all requested information
- Be respectful and professional
- Proofread before sending

**Attachments:**
- Screenshots: PNG or JPG format
- Videos: MP4 format, under 10MB
- Files: Clearly named (e.g., "flashcard-bug-screenshot.png")
- Translations: Follow naming conventions

### Response Times

**What to expect:**

| Type | Response Time |
|------|---------------|
| Security vulnerabilities | 24 hours |
| Critical bugs | 48 hours |
| Bug reports | 3-5 business days |
| Feature requests | 5-7 business days |
| Translations | 3-5 business days |
| Documentation | 7-10 business days |
| General inquiries | 7-10 business days |

**We will:**
- Acknowledge receipt of your submission
- Ask clarifying questions if needed
- Provide updates on status
- Notify you when resolved/implemented
- Credit you appropriately

---

## 🤝 Community Guidelines

All contributors must follow our [Code of Conduct](CODE_OF_CONDUCT.md).

### Expected Behavior

**Be Respectful:**
- Treat everyone with respect and kindness
- Value diverse perspectives
- Assume good intentions
- Disagree professionally

**Be Constructive:**
- Focus on solutions, not just problems
- Provide actionable feedback
- Support other contributors
- Share knowledge generously

**Be Patient:**
- Remember we're all volunteers or working with limited resources
- Understand that not all suggestions can be implemented
- Be gracious when feedback is declined
- Recognize that development takes time

**Be Clear:**
- Communicate clearly and concisely
- Provide context and examples
- Ask questions when unsure
- Follow up when needed

### Unacceptable Behavior

- Harassment or discrimination
- Disrespectful or unprofessional conduct
- Spam or self-promotion
- Demanding immediate responses
- Threats or intimidation
- Sharing others' private information

**Violations may result in:**
- Warning
- Temporary ban from contributing
- Permanent ban from community

---

## 🏆 Recognition

We deeply appreciate all contributions!

### How We Recognize Contributors

**Bug Reports:**
- Credit in release notes
- "Reported by [Name]" in changelog
- Our sincere thanks

**Feature Suggestions:**
- Credit in release notes when implemented
- "Suggested by [Name]" in feature announcement
- Early access to the feature

**Translations:**
- Prominent credit in extension (Settings → About)
- Listed in README acknowledgments
- "Translated by [Name]" in language selector
- Featured in release announcements

**Documentation:**
- Credit in commit messages
- Listed in contributors section
- Thanks in improved documentation

**Beta Testers:**
- "Beta Tester" badge in credits
- Listed in release notes
- Special thanks for feedback incorporated

**Educational Experts:**
- Credit in pedagogical feature implementations
- Acknowledgment in documentation
- Special thanks for professional insights

### Hall of Fame

Outstanding contributors will be featured in:
- README.md acknowledgments section
- Extension "About" page
- Social media highlights
- Newsletter mentions (when available)

---

## ❓ Frequently Asked Questions

### Can I contribute code?

Unfortunately, no. EduFocus Pro uses a proprietary license and we cannot accept direct code contributions. However, you can contribute in many other valuable ways listed in this guide.

### Will my feature request definitely be implemented?

We carefully consider all suggestions, but cannot guarantee implementation. Decisions depend on:
- Alignment with project goals
- Technical feasibility
- Resource availability
- Impact on privacy and security
- Benefit to majority of users

### How long until my bug is fixed?

It depends on severity:
- Critical bugs: As soon as possible (hours to days)
- High priority: Within 1-2 weeks
- Medium priority: Within 1-2 months
- Low priority: When resources permit

### Can I be anonymous?

Yes! You can contribute under a pseudonym or remain completely anonymous if you prefer. Just let us know your preference.

### Do I need technical skills?

Not at all! We welcome contributions from:
- Students sharing their experiences
- Teachers providing pedagogical feedback
- Anyone reporting bugs they encounter
- Native speakers offering translations
- People improving documentation

### Can I contribute if I'm under 18?

Yes! Students of all ages can contribute feedback, bug reports, feature suggestions, and translations. We especially value input from our target users (students).

### What if I disagree with a decision?

You can:
- Respectfully explain your perspective
- Provide additional context or use cases
- Suggest alternative approaches
- Accept the decision gracefully

We always consider feedback, but final decisions rest with Genesis Forge.

### Can educational institutions contribute?

Absolutely! We highly value feedback from:
- Teachers using EduFocus Pro in classrooms
- School administrators deploying at scale
- Educational technology specialists
- Learning support staff
- Accessibility coordinators

---

## 📞 Contact

### General Contributing Questions

**Email:** edufocusbusiness@gmail.com  
**Subject:** Contributing Question

### Specific Contributions

- **Bug Reports:** Subject: "Bug Report - [Description]"
- **Feature Requests:** Subject: "Feature Request - [Description]"
- **Translations:** Subject: "Translation: [Language]"
- **Beta Testing:** Subject: "Beta Testing Program"
- **Documentation:** Subject: "Documentation Improvement - [Document]"
- **Educational Feedback:** Subject: "Educational Feedback"

### Need Help?

If you're unsure how to contribute or have questions about the process, just reach out! We're happy to guide you.

---

## 🙏 Thank You

Every contribution, no matter how small, helps make EduFocus Pro better for students worldwide.

Your bug reports improve stability.  
Your feature suggestions drive innovation.  
Your translations expand accessibility.  
Your feedback shapes development.  
Your testing ensures quality.

**Thank you for being part of the EduFocus Pro community!**

---

**Last Updated:** October 2025  
**Version:** 1.0.0

Copyright © 2025 Genesis Forge. All Rights Reserved.  
EduFocus Pro - Privacy-First Education Technology
