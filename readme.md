Act as an expert frontend web developer. I want you to build a complete, single-page "Smart Word & Character Counter" designed for writers, students, and SEO professionals. 

Please provide the complete code in a single `index.html` file. Use standard HTML5, Vanilla JavaScript for the logic, and Tailwind CSS (via CDN) for clean, modern styling.

### 1. Core Requirements & Tech Stack
*   **Zero Dependencies:** Do not use React, Vue, or any external APIs. All logic must be handled via Vanilla JS string manipulation.
*   **Single File:** Combine all HTML, CSS, and JS into one file.
*   **Responsive Layout:** It must look excellent on desktop (split view or sidebar for stats) and mobile (stacked).

### 2. Functional Requirements
*   **The Editor:** A large, prominent `<textarea>` in the center of the page. It should have placeholder text like "Type or paste your text here...".
*   **Real-Time Reactivity:** All statistics must update instantly as the user types or pastes text using the `input` event listener.
*   **The Statistics Board:** Display the following metrics cleanly:
    *   Words
    *   Characters (with spaces)
    *   Characters (without spaces)
    *   Sentences
    *   Paragraphs
    *   Estimated Reading Time (based on 225 words per minute)
*   **Quick Actions:** Provide a row of small, elegant buttons above or below the text area for:
    *   "Copy to Clipboard"
    *   "Clear Text"
    *   "UPPERCASE"
    *   "lowercase"
    *   "Title Case"

### 3. UI/UX Guidelines
*   **Theme:** Minimalist, distraction-free, and professional. Use a soft off-white background with a stark white container for the text area. The font must be highly legible (e.g., Inter, Roboto, or standard sans-serif).
*   **Sticky Stats:** On desktop, the statistics board should stick to the side so the user can always see their word count even if they scroll down a long essay. On mobile, keep the core stats sticky at the top of the screen.

### 4. Monetization (Ad Placeholders)
This site will be monetized with display ads targeting a highly engaged audience.
*   **Desktop Ad Placement:** Place a vertical ad placeholder `<div>` (e.g., 300x600 dimensions) in a right-hand sidebar or adjacent to the statistics board.
*   **Mobile Ad Placement:** Place a responsive banner ad placeholder `<div>` directly below the quick action buttons, and another one at the very bottom of the page.
*   Style these placeholders with a dashed border, a light gray background, and centered text that says "Advertisement Space (Auto-Refreshing)".

Please output the complete HTML code.