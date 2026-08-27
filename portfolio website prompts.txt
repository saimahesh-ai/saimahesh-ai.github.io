To make your website "10x better" than a standard, plain-text academic site like `ktlabs.us`, we need to instruct the AI agent to use modern web design principles. We will upgrade the CSS to include **Flexbox/Grid layouts, subtle drop shadows, smooth hover transitions, and a responsive, mobile-friendly design.**

We will also add the **circular profile photo** on the home page and create the new **"Writing & Thoughts"** page.

Here is your upgraded, sequential prompt list to feed into your VS Code AI agent (Cursor, Copilot, or Cline). Copy and paste these **one by one**.

---

### Prompt 1: High-End Architecture & Modern Global Styling

**Goal:** Set up the folder structure and a premium, modern CSS file that elevates the site far beyond a basic HTML page.

**Copy and paste this into your VS Code Agent:**

> "I am building a premium, multi-page academic portfolio website. Please set up the workspace by creating an 'assets' folder containing a 'css' folder, an 'img' folder, and a 'style.css' file inside the css folder.
> In the 'style.css' file, create a highly polished, modern, minimalist design. Use the 'Inter' font from Google Fonts (or system UI fonts). Define CSS variables for a color palette: a very light gray/off-white background, dark slate text for high readability, and UNT Green (#00853E) for links and accents.
> Include global styles for:
> 1. A responsive, sticky top navigation bar using Flexbox, with smooth hover transitions on the links.
> 2. Typography: Clean headers (h1, h2, h3) with tight tracking, and readable paragraphs with a 1.6 line height.
> 3. Modern UI elements: Create a `.card` class with a white background, subtle border, rounded corners (8px), and a soft box-shadow (`rgba(0,0,0,0.05)`) that elevates slightly on hover.
> 4. A `.profile-img` class for a circular avatar (width/height ~120px, `object-fit: cover`, subtle shadow).
> 5. A layout constrained to a maximum width of 850px, centered on the screen, with responsive padding for mobile devices."
> 
> 

---

### Prompt 2: The Premium Home Page with Profile Photo

**Goal:** Create an impressive `index.html` featuring a two-column header (Text + Photo) and an elegant timeline for news.

**Copy and paste this into your VS Code Agent:**

> "Now, create the 'index.html' file in the root directory and link it to 'assets/css/style.css'.
> 1. Add a `<nav>` bar at the top with links to: Home (index.html), Research (research.html), Publications (publications.html), Teaching (teaching.html), and Writing (writing.html).
> 2. Create a `<header>` section using a Flexbox layout. On the left side, put my name (Sai Mahesh Mudavat), my title (Ph.D. Candidate), my affiliation (University of North Texas, Smart Electronic Systems Laboratory), and an elegant row of icons/links for Email, GitHub, and Google Scholar. On the right side, add an `<img>` tag using the `.profile-img` class (point it to 'assets/img/profile.jpg', which I will add later).
> 3. Add an 'About Me' section summarizing my focus on Trustworthy Lightweight AI, Computer Vision, and Edge Computing for Smart Agriculture.
> 4. Add a 'Latest News' section styled as a clean vertical timeline. Include 2-3 recent updates (e.g., 'August 2024: Started Ph.D. at UNT').
> 5. Add a minimalist footer. Ensure the design is responsive so the header stacks neatly on mobile."
> 
> 

---

### Prompt 3: The Research Ideas Page (Grid Layout)

**Goal:** Showcase your technical methodologies using modern card-based grids.

**Copy and paste this into your VS Code Agent:**

> "Using the exact same `<nav>` and footer structure from 'index.html', create a new file named 'research.html'.
> On this page, showcase my research ideas using the `.card` classes we defined in CSS. Create three sections:
> 1. **Core Research Interests:** Display these as a responsive grid of clean, pill-shaped tags or small cards: Trustworthy Lightweight AI, Byzantine-Robust Federated Learning, Vision Foundation Models, and Edge-Ready Computer Vision.
> 2. **Current Projects:** Create two distinct `.card` blocks. One for 'Byzantine-Robust Architectures for Edge Deployments' and another for 'Parameter-Free Dynamic Routing Networks'. For each, include a bold title, a short paragraph explaining the scientific problem, and the novel solution.
> 3. **Future Directions (Smart Agriculture):** A beautifully styled blockquote or highlight box detailing my vision for building hyper-localized AI models for intercropping systems and diverse agro-practices."
> 
> 

---

### Prompt 4: The Publications Page (Impact Focus)

**Goal:** Organize your papers with visually distinct "Impact Statements."

**Copy and paste this into your VS Code Agent:**

> "Create a new file named 'publications.html' using the same layout and navigation.
> Create two main sections: 'Peer-Reviewed Conference Proceedings' and 'Preprints / Under Review'.
> Add my papers (LiteViT, FLitViT, DPRS, Tiny VarNet, and E2-WeedNet). For every single entry:
> 1. Wrap the publication inside a clean, bottom-bordered list item or card.
> 2. Bold my name in the author list.
> 3. Below the venue, add a beautifully styled 'Impact Statement' block. Give this block a very light green background (`rgba(0, 133, 62, 0.05)`), a left border using the UNT Green accent color, and slightly smaller text. (Add this specific impact-box style to the CSS file). For example: 'Impact: Compressed a 300M-parameter Vision Transformer to a 3.8 MB model for edge hardware'."
> 
> 

---

### Prompt 5: The Teaching & Service Page

**Goal:** Highlight your academic citizenship with clear, scannable lists.

**Copy and paste this into your VS Code Agent:**

> "Create 'teaching.html' matching the site's exact navigation and layout.
> Create two elegantly spaced sections:
> 1. **Teaching Experience:** List my roles as a Teaching Assistant at UNT for Fundamentals of AI, Data Mining, CS II (C++), and Machine Learning. Use a modern list style to emphasize that I designed open-ended assignments, delivered guest lectures, and built automated grading pipelines.
> 2. **Academic Service:** List my peer review experience for SN Computer Science, ISVLSI, IFIP IoT, and Applied Clinical Informatics. Format these not just as a bulleted list, but as a clean, comma-separated inline text block or a grid, making it look highly professional."
> 
> 

---

### Prompt 6: The Writing & Thoughts Page (NEW)

**Goal:** Add the new page for your essays, updates, and research thoughts.

**Copy and paste this into your VS Code Agent:**

> "Finally, create 'writing.html' using the site's navigation and layout.
> This page will serve as a digital garden or blog for my research thoughts, essays, and updates.
> Create a section titled 'Notes & Thoughts'. Inside it, generate three placeholder entries wrapped in our `.card` class. Each entry should have:
> 1. A date in small, muted text (e.g., 'October 2024').
> 2. A bold, clickable title (e.g., 'Why Edge AI is the Future of Smart Agriculture', 'Thoughts on the limitations of Vision Transformers in the field').
> 3. A 2-sentence excerpt summarizing the thought or update.
> 4. A 'Read more ->' link using the UNT Green accent color.
> Make sure the hover effect on these cards feels smooth and premium."
> 
> 

---

### Final Steps to Make it Live:

1. **Add your Photo:** Find a professional headshot, crop it into a square, name it `profile.jpg`, and drop it into the `assets/img/` folder that the agent created.
2. **Test Locally:** Open `index.html` in your browser. The site should now look incredibly modern, matching the aesthetic of top-tier tech/academic portfolios (think MIT/Stanford researchers) rather than a plain 1990s HTML page.
3. **Deploy:** Upload the entire folder to your `saimaheshmudavat.github.io` repository.