Roll Length Calculator (SaaS Micro-Tool)
A lightweight, single-file calculation utility designed for the printing, packaging, and manufacturing industries. This application estimates remaining material length based on roll diameter, core size, and material thickness.
Key Selling Points (Technical)
* Zero Dependencies: Built with Vanilla JavaScript. No Node.js backend, React build steps, or complex bundlers required.
* Single-File Architecture: The entire app lives in index.html. Simplifies deployment to literally dragging and dropping the file onto any hosting provider.
* Modern UI: styled with Tailwind CSS (via CDN) and Lucide Icons.
* White-Label Ready: Code is cleanly commented and structured for easy rebranding.
* Offline Capable: Logic runs entirely in the client's browser.
* Persistent State: Uses localStorage to save user presets automatically.
Quick Start
1. Download: Clone the repository or download the ZIP.
2. Run: Double-click index.html to open it in any modern browser.
3. Deploy: Upload index.html to Netlify, Vercel, GitHub Pages, or any shared hosting (cPanel/FTP).
Feature List
* Dynamic Visualization: SVG graphic updates in real-time to explain the math visually.
* Input Validation: Prevents physics errors (e.g., Core Diameter > Roll Diameter).
* Preset Manager: Users can add, edit, and delete custom material presets.
* Responsive Design: Fully functional on Mobile, Tablet, and Desktop.
Code Structure
* CSS: Tailwind CSS handles all styling. Custom animations (fade-ins, wiggles) are defined in the <style> block.
* Logic: All JavaScript functions (calculate, savePreset, etc.) are located in the <script> tag at the bottom of the body.
* Icons: Loaded dynamically via lucide-react (CDN).
License
This software is Proprietary. It is not open source.
Copyright © 2025 [Your Company/Name]. All Rights Reserved.
Unlicensed distribution or modification is strictly prohibited.
Developed for high-conversion utility and ease of integration.