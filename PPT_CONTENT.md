# HandsFreeWeb - AI PPT Builder Prompt

> Generate an 8-slide professional hackathon pitch presentation for a project called "HandsFreeWeb". Use modern, clean design with gradient backgrounds. Make it visually appealing with icons/emojis.

---

## SLIDE 1: Title Slide

**Title:** HandsFreeWeb

**Subtitle:** Hands-Free Web Browsing Using Head Tracking & On-Device AI

**Bottom text:** HackJNU 4.0 | Idea Submission 

TEAM NAME: Byte Masters

TEAM MEMBERS: 
Priyanshu Harshbodhi (8605992962, priyanshuqpwp@gmail.com) - Team leader
Anushttha Shrivastava (8303113245, anushttha04@gmail.com)

**Design:** Dark gradient background (dark blue to purple), large centered title, futuristic tech feel

---

## SLIDE 2: The Problem

**Title:** The Problem We're Solving

**Content (5 bullet points with icons):**

- ♿ **Accessibility Gap** - Millions with mobility impairments (ALS, cerebral palsy, RSI) struggle to use traditional mouse and keyboard

- 💰 **Expensive Solutions** - Eye-gaze tracking systems cost $10,000+ and require specialized hardware

- 🔒 **Privacy Risks** - Existing assistive tools send sensitive data to cloud servers

- 🌐 **Limited Browser Support** - Most assistive technologies don't integrate well with web browsers

- 📚 **Information Overload** - Users must click through countless links just to preview content

**Design:** Red/orange accent color for problem emphasis, icons on left side

---

## SLIDE 3: Our Proposed Solution

**Title:** Introducing HandsFreeWeb

**Tagline:** "Browse the web without touching anything"

**Two-column layout:**

**Left Column - Head Tracking Control:**
- Move cursor by turning head left/right/up/down
- Click by opening mouth (calibrated per user)
- Hover-to-click with visual progress indicator
- Auto-scroll zones at screen edges
- Browser back/forward via edge zones

**Right Column - AI-Powered Previews:**
- Hover over any link to get instant summary
- Uses Chrome's built-in Gemini Nano (100% local)
- Supports YouTube video summarization
- Extracts key points from articles
- Zero cloud dependency - complete privacy

**Design:** Green header (solution = positive), split layout, icons for each feature

---

## SLIDE 4: Key Features

**Title:** Key Features

**Grid layout (2 rows × 3 columns) with feature cards:**

| 👄 Mouth-Click | 🎯 Magnetic Snap | 📺 YouTube Support |
|----------------|------------------|-------------------|
| Open mouth to click, calibrated to your face | 45px auto-targeting of buttons & links | Caption extraction & video summaries |

| ⚡ Streaming AI | 📷 Any Webcam | 🔒 100% Private |
|-----------------|---------------|-----------------|
| Real-time character-by-character responses | Works with standard laptop cameras | All processing happens locally on device |

**Design:** Light colored cards on darker background, rounded corners, centered icons above text

---

## SLIDE 5: Technology Stack

**Title:** Proposed Technology Stack

**Three columns:**

**🎥 Computer Vision:**
- Human.js - 468-point facial landmark detection
- One-Euro Filter - Smooth, jitter-free cursor movement
- WebGL - GPU-accelerated face processing

**🤖 AI Integration:**
- Chrome Summarizer API - Key-point extraction
- Chrome Prompt API - Custom prompting for videos
- Gemini Nano - On-device language model

**🌐 Browser Platform:**
- Chrome Extension (Manifest V3)
- Side Panel API for settings UI
- Readability.js for content extraction

**Bottom highlight:** "Lightweight extension (~2MB) | Works offline after initial model download"

**Design:** Purple/indigo header, three equal columns, tech-focused icons

---

## SLIDE 6: How It Will Work

**Title:** System Architecture

**Three horizontal pipeline diagrams:**

**🎯 Head Tracking Pipeline:**
```
Webcam → Face Detection → 468 Landmarks → Head Pose → Signal Filter → Screen Coordinates → Action
```

**🤖 AI Summary Pipeline:**
```
Link Hover (600ms) → Fetch Page → Extract Content → Chrome AI API → Gemini Nano → Display Summary
```

**📺 YouTube Pipeline:**
```
Detect Video → Intercept Captions → Parse Text → Combine with Description → Generate Summary
```

**Design:** Flowchart style with arrows, each pipeline in different color (blue, green, orange)

---

## SLIDE 7: Innovation & Impact

**Title:** Why GazeFlow Matters

**Two-column layout:**

**Left - Innovation:**
- ✓ First to combine head tracking + on-device AI in browser
- ✓ Cost: $0 vs $10,000+ alternatives
- ✓ No specialized hardware needed
- ✓ Complete privacy - zero cloud dependency
- ✓ No network latency - instant responses
- ✓ Works with any standard webcam

**Right - Target Users:**
- ♿ People with mobility impairments (paralysis, ALS)
- 🤕 RSI sufferers and prevention
- 🩹 Temporary disabilities (broken arm, surgery recovery)
- 📝 Hands-free browsing while note-taking
- 🎓 Researchers and students exploring content

**Design:** Orange/gold header, checkmarks and bullets, warm inspiring colors

---

## SLIDE 8: Future Scope & Vision

**Title:** Future Roadmap

**Content (4 key points):**

- **Phase 1:** Core head tracking + basic AI summaries (Hackathon MVP)

- **Phase 2:** Voice commands integration for complete hands-free control

- **Phase 3:** Multi-language support for AI summaries (10+ languages)

- **Phase 4:** Mobile browser extension for Android/iOS accessibility

**Vision Statement:**
"Democratizing web accessibility - making the internet usable for everyone, regardless of physical ability"

**Call to Action:**
"Let's build a more inclusive web together"

**Design:** Gradient background (blue to purple), roadmap timeline visual, inspirational tone

---

## Design Guidelines for AI PPT Builder:

1. **Color Scheme:** Modern dark theme with gradient accents (blue, purple, orange highlights)
2. **Typography:** Clean sans-serif fonts, large headings, readable body text
3. **Icons:** Use emojis or simple line icons for visual interest
4. **Layout:** Generous whitespace, no cluttered slides
5. **Style:** Professional tech startup pitch aesthetic
6. **Consistency:** Same header style across slides 2-8
