MelloMind - Mental Wellness Companion

MelloMind is a high-fidelity, single-page mental wellness application designed to provide a safe space for emotional reflection and AI-driven support. It features a clean, "Soft UI" aesthetic characterized by high-contrast typography, ample whitespace, and fluid transitions.
Key Features

1. Adaptive Authentication

Toggleable Interface: Seamlessly switch between Login and Signup modes.

Dynamic Identity: User profiles update in real-time across the dashboard sidebar and header based on signup input.

2. AI Counseling Interface

Contextual Conversation: A dedicated chat environment with message bubble tails and timestamping.

Simulated Response: Built-in logic to simulate empathetic AI feedback after user input.

3. Mood Bloom (Energy Tracker)

Visual Logging: A tactile interface for selecting emotional states (Radiant, Peaceful, Restless, Exhausted).

Feedback Loop: Instant confirmation messages that encourage mindfulness through breathing prompts.

4. Reflections (Journaling)

Modal-Driven Composition: A focused writing environment for long-form thoughts.

CRUD Operations: Complete ability to Create, Read, and Delete journal entries within the session.

Chronological Sorting: Newest reflections are automatically prepended to the top of the stack.

🛠 Technical Stack

Frontend: HTML5, CSS3 (Custom animations)

Styling: Tailwind CSS (Utility-first framework)

Icons: Lucide React (Rendered via CDN)

State Management: Centralized JavaScript state object managing:

Authentication status

Active navigation tabs

Message history

Journal entry arrays

📂 File Structure

The application is built using a Single-File Architecture for maximum portability and rapid deployment:

index.html: Contains all structural markup.

<style> block: Handles custom scrollbars, modal backdrops, and active navigation states.

<script> block: Manages DOM manipulation, event listeners, and the application's business logic.

🎨 Design Principles

Typography: Uses 'Plus Jakarta Sans' for a modern, approachable feel.

Color Palette:

Primary: #00BFA5 (Teal) - Represents growth and calm.

Surface: #F8FAFC (Slate) - Minimizes eye strain.

Text: #0F172A (Deep Navy) - Ensures high legibility.

Border Radius: Consistent 40px/32px rounding to create a "friendly" and non-threatening interface.

🛠 Installation & Usage

Open index.html in any modern web browser.

Sign in with the default credentials (or create your own).

Navigate between the "AI Counselor", "Mood Bloom", and "My Journal" tabs using the sidebar.

To add a journal entry, click "Write Entry" in the Journal tab.
