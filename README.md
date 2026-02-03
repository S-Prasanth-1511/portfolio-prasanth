# Prasanth S - Portfolio Website

This is the official portfolio website for Prasanth S, a final-year IT student and aspiring Software Engineer. The site is built with HTML5, Tailwind CSS, and vanilla JavaScript, designed to be lightweight, responsive, and deployable on Netlify's Free Tier.

## Project Structure

```
portfolio_prasanth/
│
├── index.html          # Main entry point
│
├── assets/
│   ├── images/         # Project screenshots and profile picture
│   │   ├── profile.jpg
│   │   ├── expense_tracker.jpg
│   │   ├── inventory_system.jpg
│   │   ├── e_notes.jpg
│   │   ├── deepfake_image.jpg
│   │   ├── ehr_system.jpg
│   │   └── eeg_aad.jpg
│
├── resume/
│   └── Prasanth_Resume.pdf
│
└── README.md           # This file
```

## Deployment Instructions (Netlify)

1.  **Fetch Images:** Run `python fetch_images.py` to download real project images from the internet.
2.  **Prepare Assets:** Ensure `profile.jpg` is in `assets/images/` and your resume PDF is in `resume/`.
2.  **Drag and Drop:**
    *   Log in to Netlify.
    *   Go to the "Sites" tab.
    *   Drag the entire `portfolio_prasanth` folder onto the drop zone.
3.  **Live:** Your site will be deployed instantly.

## Technologies Used
*   **HTML5**
*   **Tailwind CSS** (via CDN)
*   **Font Awesome** (via CDN)
*   **Vanilla JavaScript**