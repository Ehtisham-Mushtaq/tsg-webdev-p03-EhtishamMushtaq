# **Project 03: Multi-Page Blog Website — The Sky Gen**

## 1. Project Title & Overview

**Project 03: Multi-Page Blog Website — The Sky Gen** is a modern, fully responsive, three-page website developed using semantic HTML5 and CSS3. The project consists of a Home page, a Blog page, and a Contact page, all connected through a consistent navigation system and shared visual design.

The website uses a **single, unified `styles.css` stylesheet** to manage typography, colors, layouts, responsive breakpoints, interactive states, and reusable design components. Shared styling is centralized to maintain consistency across all pages and avoid unnecessary duplication.

The project demonstrates essential frontend development practices, including semantic markup, responsive web design, reusable CSS, Flexbox and Grid layouts, accessible form controls, and multi-page navigation.

## 2. Metadata & Submission Links

| Detail | Information |
|---|---|
| **Student Name** | Ehtisham Mushtaq |
| **Project Title** | Project 03: Multi-Page Blog Website — The Sky Gen |
| **Project Directory / Folder Name** | `tsg-webdev-p03-ehtishammushtaq` |
| **Live Website (Vercel)** | [Visit the Live Website](https://tsg-webdev-p03-ehtishammushtaq.vercel.app/) |
| **Public GitHub Repository** | [View the Source Repository](https://github.com/Ehtisham-Mushtaq/tsg-webdev-p03-EhtishamMushtaq.git) |
| **Deployment Platform** | Vercel |
| **Primary Branch** | `main` |

## 3. Page Architecture Breakdown

### 3.1 Home Page — `index.html`

The Home page introduces the BrightBlog publication through a modern editorial layout and provides access to the website's main sections.

Key features include:

- **Shared header and navigation:** Consistent branding, navigation links, and an active-page indicator.
- **Split-screen hero section:** A prominent headline with gradient text, an update badge, introductory content, and primary and secondary call-to-action buttons.
- **Featured visual area:** A large image presentation with rounded corners, layered visual elements, and supporting text.
- **About the Publication section:** An introduction to the publication's purpose and editorial approach.
- **Three-column benefits grid:** Dedicated feature cards highlighting quality content, creative ideas, and continuous learning.
- **Featured content call-to-action:** A prominent link directing visitors to the article collection.
- **Shared footer:** Consistent branding and navigation links.

### 3.2 Blog Page — `blog.html`

The Blog page presents the publication's articles through a structured, responsive card layout while maintaining the same header, navigation, and footer used throughout the website.

Key features include:

- An editorial introduction with a prominent heading and supporting description.
- **Exactly four structured blog post cards**, each containing an image, category badge, publication date, article title, descriptive preview, and reading link.
- A responsive CSS Grid layout that adapts to different viewport widths.
- Interactive hover effects, animated arrow links, and subtle card elevation.
- A concluding call-to-action section inviting visitors to suggest future topics.

The article cards demonstrate a consistent content structure suitable for extending the publication with individual article pages in the future.

### 3.3 Contact Page — `contact.html`

The Contact page provides a premium dual-column layout containing publication information and a styled contact form.

Key features include:

- The same shared header, navigation, active-page indicator, and footer.
- A prominent contact introduction with gradient typography.
- **Contact information cards** for email, publication location, and social media.
- Interactive link styling with animated underline effects.
- A dedicated form card with full-name, email, subject, and message fields.
- Floating-style input labels, custom focus borders, and subtle focus-glow effects.
- A full-width submit button with hover animation.
- Responsive behavior that stacks the information and form sections on smaller screens.

The contact form provides a styled frontend interface with native HTML validation. Actual message delivery requires integration with a backend or form-handling service.

## 4. Technical Features & Evaluation Testing Verification

### 4.1 Technology Stack

| Technology | Purpose |
|---|---|
| **HTML5** | Semantic page structure, navigation, article content, and contact form markup. |
| **CSS3** | Visual styling, typography, gradients, transitions, hover effects, and responsive layouts. |
| **Flexbox** | Navigation alignment, component arrangement, button groups, and flexible content layouts. |
| **CSS Grid** | Responsive article cards, feature grids, and multi-column page sections. |
| **Google Fonts** | Plus Jakarta Sans typography for a consistent, modern editorial design. |
| **Git** | Local version control and change history. |
| **GitHub** | Remote source-code hosting and repository access. |
| **Vercel** | Cloud hosting and production website deployment. |

### 4.2 Implementation Highlights

- **Unified styling:** All three HTML pages reference a single shared `styles.css` file.
- **Consistent navigation:** Shared navigation and footer components provide a uniform experience across the website.
- **Active-page indication:** The current page is visually distinguished in the navigation system.
- **Responsive layouts:** Dedicated media queries adapt layouts for desktop, tablet, and mobile viewports.
- **Modern visual design:** Gradient typography, refined spacing, rounded cards, subtle shadows, and smooth transitions create a consistent visual identity.
- **Accessible interactions:** Semantic elements, descriptive image alternatives, form labels, and visible keyboard-focus styles support usability.
- **Asset and path organization:** Page links and shared stylesheet references follow consistent naming and path conventions.
- **Cloud deployment:** The project is available through a public Vercel URL, with its source code hosted in a public GitHub repository.

### 4.3 Evaluation Testing & Verification

The deployed Home, Blog, and Contact pages should be checked through their intended URLs, with particular attention to navigation, asset loading, and responsive behavior.

The responsive implementation includes dedicated mobile breakpoints and overflow safeguards. Final mobile acceptance testing should verify that no horizontal scrolling occurs at narrow phone widths, including 320px, 375px, and 390px, as well as tablet and desktop sizes.

The following checks form part of the final evaluation criteria:

- All three pages load through their intended URLs.
- The navigation links and logo return visitors to the correct destinations.
- The shared stylesheet loads correctly across all pages.
- Images and external font resources load as expected.
- Blog cards and contact sections adapt to smaller screens.
- Form labels, required fields, and keyboard-focus states behave correctly.
- No unintended horizontal overflow occurs at the tested mobile viewport widths.
- The repository and live website links are accessible to evaluators.

**Responsive QA sign-off:** The website's responsive styling and primary page-navigation paths should be verified against the deployed version before final submission. The project is intended to provide a mobile-friendly experience without horizontal scrolling, with all internal navigation paths resolving to their correct destinations.

## Project Sign-Off

**Submitted by:** Ehtisham Mushtaq

**Project:** Project 03 — Multi-Page Blog Website

**Organization:** The Sky Gen

This project demonstrates the implementation of a responsive, multi-page frontend website using semantic HTML5, CSS3, Flexbox, and CSS Grid, supported by Git-based version control, public source-code hosting, and cloud deployment through Vercel.