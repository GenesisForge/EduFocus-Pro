

# Changelog

All notable changes to EduFocus Pro will be documented in this file.

---

## [Unreleased]

## Possible Planned Features

### Study & Learning
- **Progress tracking per subject with visual graphs**
- **Learning style assessment tool**
- **Study technique guides** (Feynman, SQ3R, etc.)
- **Break activity suggestions based on study duration**

### Notes & Content
- **LaTeX/Math equation support** for STEM subjects
- **Diagram drawing tool** (flowcharts, mind maps)
- **Code snippet highlighting** for programming students
- **Table creation and editing**
- **Image insertion** (from device only)
- **Note templates library** (meeting notes, lab reports, book summaries)
- **Auto-organization by subject/date**
- **Full-text search across all notes**
- **Note version history**

### Flashcards & Quizzes
- **Image-based flashcards**
- **Custom difficulty ratings**
- **Smart shuffle algorithms**
- **Timed practice mode**
- **Quiz generation from notes** (keyword extraction)

### Accessibility & Customization
- **Color blindness modes**
- **Custom keyboard shortcuts**
- **High contrast themes**
- **Font style options** (serif, sans-serif, monospace)
- **Left-handed mode**
- **Adjustable button sizes**
- **Simplified interface mode**
- **Customizable UI colors**

### Productivity & Organization
- **Habit tracker**
- **Grade calculator**
- **Assignment priority sorting**

### Tools & Utilities (new tab, so it doesnt get overfloded)
- **GPA calculator**
- **Typing speed test**
- **Memory games** (pattern matching, sequence recall)

### Import/Export
- **PDF note export**
- **Markdown export**
- **CSV export for statistics**
- **Print-friendly formatting**
- **Import from other study apps** (standardized formats)
- **Download specific** (download stuff like: notes, settiings, etc.)

### Gamification (Privacy-Friendly)
- **Study streaks visualization**
- **Personal bests tracker**
- **Virtual study pet** (grows with study time)

---

## [3.5.3]

### Fixed
- 🐛 **Fixed scroll position not being remembered when closing and reopening the popup**
  - Scroll position now correctly saves and restores across all tabs (Timers, Focus, Notes, Quiz, Flashcards, Tools, Resources)
  - Users can now continue exactly where they left off

### Improved
- ⚡ **Optimized scroll restoration performance - now near-instant instead of 1-second delay**
  - Smart retry logic ensures scroll position is restored even when dynamic content is still loading
  - Progressive retry delays (0ms → 50ms → 100ms → 150ms) provide smooth user experience
  - Most scroll restorations happen immediately on first attempt

### Technical Details
- Identified .tab-content as the primary scrolling container (not body or #mainContainer)
- Implemented efficient scroll event listener with 150ms debouncing to prevent excessive saves
- Added intelligent scroll restoration with automatic retries for dynamic content scenarios
- Scroll position persists in chrome.storage.local alongside other app state

---

## [3.5.2]

### Added
- **Initial privacy policy implementation**
- **Multi-language support framework**

### Fixed
- **Minor UI adjustments for better readability**

---

## [3.5.1]

### Fixed
- **Bug fixes and performance improvements**

---

## [3.5.0] - Our biggest update till date.

### Added
- **Multi-language support:** Danish, German, and Ukrainian translations
- **Translation system:** Complete localization infrastructure
- **Language selector:** Easy switching between supported languages
- **Accessibility improvements:** Enhanced keyboard navigation
- **OpenDyslexic font option:** Better support for dyslexic users
- **Reading guide overlay:** Customizable reading assistance
- **Line spacing adjustment:** Improved text readability options
- **High contrast themes:** Better visibility for visually impaired users
- **Export/Import functionality:** Backup and restore all user data
- **Study streaks tracking:** Daily study goal monitoring
- **Achievement milestones:** Motivational progress markers
- **Enhanced statistics:** Comprehensive study analytics
- **Improved error messages:** User-friendly error handling
- **Tooltip system:** Contextual help throughout the interface

### Changed
- **UI redesign:** Modernized interface with improved usability
- **Performance optimization:** Faster loading and smoother animations
- **Storage efficiency:** Reduced data footprint by 30%
- **Timer accuracy:** Improved precision for Pomodoro sessions
- **Search functionality:** Faster and more accurate note search
- **Settings organization:** Better categorization of preferences
- **Font size range:** Expanded from 12px-20px to 12px-24px

### Fixed
- **Timer notification bug:** Notifications now appear reliably
- **Data persistence issue:** All data saves correctly on browser restart
- **Flashcard shuffle:** Random order now truly random
- **Quiz grading accuracy:** Correct scoring for all question types
- **Export formatting:** JSON exports now properly formatted
- **Memory leak:** Fixed memory usage in long study sessions
- **Text overflow:** Adjusted layout to prevent text cutoff
- **Dark mode contrast:** Improved readability in dark mode

### Security
- **Content Security Policy:** Strengthened CSP directives
- **Input sanitization:** Enhanced protection against XSS
- **Storage encryption:** Improved data security at rest

### Documentation
- **Complete README overhaul:** Comprehensive project documentation
- **Translation Guide:** Detailed instructions for translators
- **Contributing Guide:** Clear contribution guidelines
- **Code of Conduct:** Community standards established
- **Security Policy:** Vulnerability reporting process defined
- **FAQ document:** Common questions answered
- **Support guide:** Troubleshooting resources

---

## [3.4.0] 

### Added
- **Quiz builder:** Create custom quizzes with multiple question types
- **Quiz statistics:** Track performance and identify weak areas
- **Study mode:** Review quizzes with detailed explanations
- **Auto-save for quizzes:** Never lose your quiz progress
- **Quiz export/import:** Share quizzes or backup quiz data
- **Timed quiz mode:** Practice under time pressure
- **Quiz categories:** Organize quizzes by subject

### Changed
- **Flashcard algorithm:** Improved spaced repetition scheduling
- **UI responsiveness:** Better adaptation to different window sizes
- **Data structure:** Optimized for faster data retrieval

### Fixed
- **Flashcard mastery calculation:** Accurate progress tracking
- **Note search performance:** Faster search on large note collections
- **Statistics display bug:** Charts now render correctly

---

## [3.3.0] 

### Added
- **Flashcard system:** Create and study flashcard decks
- **Spaced repetition:** Intelligent card scheduling for better retention
- **Flashcard statistics:** Track mastery and study progress
- **Deck organization:** Categorize flashcards by subject
- **Import/Export decks:** Share flashcards with others
- **Card shuffle mode:** Randomized study sessions
- **Mastery levels:** Visual progress indicators for each card

### Changed
- **Storage structure:** Reorganized for flashcard support
- **Navigation:** Added flashcard tab to main interface
- **Statistics page:** Integrated flashcard analytics

### Fixed
- **Note deletion confirmation:** Added safety prompt
- **Timer reset bug:** Timer now resets correctly after completion
- **Dark mode inconsistencies:** Unified color scheme

---

## [3.2.0] 

### Added
- **To-Do list:** Task management with deadlines and priorities
- **Daily goals:** Set and track study objectives
- **Task categories:** Organize by subject or project
- **Completion tracking:** Mark tasks as complete
- **Overdue notifications:** Reminders for pending tasks
- **Task statistics:** Productivity analytics

### Changed
- **UI navigation:** Improved tab switching
- **Settings layout:** Better organization of options
- **Performance:** Reduced initial load time by 20%

### Fixed
- **Note tag display:** Tags now show correctly in all views
- **Statistics calculation:** Fixed weekly study time aggregation
- **Export bug:** All notes now include in export

---

## [3.1.0]

### Added
- **Advanced note search:** Full-text search across all notes
- **Note tags:** Organize notes with custom tags
- **Note filtering:** Filter by tags and subjects
- **Rich text formatting:** Bold, italic, lists in notes
- **Note templates:** Quick start templates for common note types
- **Auto-save:** Notes save automatically as you type
- **Character count:** Track note length

### Changed
- **Note editor:** Improved text editing experience
- **Note list view:** Better visual organization
- **Search speed:** Optimized search algorithm

### Fixed
- **Long note performance:** Smooth scrolling for lengthy notes
- **Copy/paste formatting:** Preserves formatting correctly
- **Note deletion:** Confirmation prompt prevents accidental deletion

---

## [3.0.0]

### Added
- **Statistics dashboard:** Comprehensive study analytics
- **Weekly reports:** Study time breakdown by day
- **Monthly summaries:** Long-term progress tracking
- **Session history:** View past study sessions
- **Charts and graphs:** Visual representation of study data
- **Data export:** Download statistics as JSON
- **Dark mode:** Reduce eye strain during night study sessions

### Changed
- **Complete UI overhaul:** Modern, clean interface design
- **Chrome Manifest V3:** Updated to latest extension standard
- **Storage optimization:** More efficient data management
- **Timer precision:** Microsecond accuracy for timers

### Fixed
- **Timer drift:** Fixed timing accuracy over long sessions
- **Notification reliability:** Consistent notification delivery
- **Data corruption:** Enhanced data integrity checks

### Deprecated
- **Manifest V2 support:** Migrated fully to Manifest V3

---

## [2.5.0]

### Added
- **Break reminders:** Automatic prompts during Pomodoro breaks
- **Custom break lengths:** Configurable break durations
- **Session goals:** Set target study time for the day
- **Audio notifications:** Optional sound alerts
- **Focus mode:** Minimize distractions during study

### Changed
- **Timer interface:** Simplified controls
- **Settings menu:** Reorganized for clarity

### Fixed
- **Timer pause bug:** Pause/resume now works reliably
- **Notification timing:** Accurate notification delivery

---

## [2.0.0]

### Added
- **Note-taking system:** Create and manage study notes
- **Note organization:** Basic categorization by subject
- **Note search:** Find notes by title
- **Multiple timer types:** Pomodoro, countdown, stopwatch
- **Timer presets:** Quick-start common timer durations
- **Persistent storage:** Notes and settings saved automatically

### Changed
- **Extension architecture:** Rebuilt for better performance
- **User interface:** Tabbed interface for features

### Fixed
- **Storage limits:** Optimized data structure for more notes
- **Timer accuracy:** Improved timing precision

---

## [1.5.0] 

### Added
- **Pomodoro timer:** Traditional 25-minute study sessions
- **Study session tracking:** Count completed sessions
- **Basic notifications:** Alerts when timer completes
- **Settings page:** Customize timer defaults

### Changed
- **Timer display:** Larger, more readable numbers
- **Button layout:** Improved usability

### Fixed
- **Background timer:** Timer continues when popup closed
- **Session count:** Accurate tracking of completions

---

## [1.0.0] 

### Added
- **Basic countdown timer:** Simple study timer functionality
- **Start/Stop/Reset controls:** Essential timer operations
- **Browser action popup:** Quick access from toolbar
- **Local storage:** Save timer state

### Initial Release
- First public release of EduFocus Pro
- Core timer functionality
- Privacy-first approach: zero data collection
- Free for all users

---

## Release Schedule

**Major versions (x.0.0):** Every 6-8 months
- Significant new features
- Possible breaking changes
- Major UI updates

**Minor versions (3.x.0):** Every 2-3 months
- New features
- Enhancements
- Non-breaking changes

**Patch versions (3.5.x):** As needed
- Bug fixes
- Security updates
- Performance improvements

---

## Deprecation Policy

**Notice Period:** 90 days minimum before feature removal

**Support Period:** One major version after deprecation

**Migration Path:** Always provided for deprecated features

---

## Beta Program

Interested in testing new features early?

**Email:** edufocusbusiness@gmail.com  
**Subject:** Beta Testing Program

Beta testers receive:
- Early access to new features
- Opportunity to provide feedback
- Credit in release notes
- Direct communication with development team

---

## Reporting Issues

Found a bug? Have a feature request?

**Email:** edufocusbusiness@gmail.com  
**Subject:** Bug Report - [Brief Description]

or

**Subject:** Feature Request - [Brief Description]

Please include:
- EduFocus Pro version
- Chrome version
- Operating system
- Steps to reproduce (for bugs)
- Expected vs actual behavior

---

## Contributing to Changelog

For translators and contributors: When features are added that affect your translation, you'll be notified to update the relevant strings.

---

**Last Updated:** January 2025  
**Current Version:** 3.5.3

Copyright © 2025 Genesis Forge. All Rights Reserved.  
EduFocus Pro - Privacy-First Education Technology

---

## Links

- [README](../../README.md) - Project overview
- [Contributing Guide](../developer/CONTRIBUTING.md) - How to contribute
- [Security Policy](../developer/SECURITY.md) - Report vulnerabilities
- [Support](../user/SUPPORT.md) - Get help