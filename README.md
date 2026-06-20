# 🌟 Free 360° Panoramic Viewer for Virtual Tours PRO (In HTML)

![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)
![Status: Active](https://img.shields.io/badge/Status-Active-success.svg)

An advanced, free, and open-source tool for creating **interactive 360° Virtual Tours**. It runs 100% in the browser (no database or server required), packaged into a **single HTML file**. 

Ideal for real estate agents, photographers, architects, or anyone looking to showcase spaces in 360 degrees professionally without recurring costs from third-party platforms.

<img width="1150" height="680" alt="Free 360 panoramic viewer for virtual tours in html" src="https://github.com/user-attachments/assets/31f4bd41-8f11-4297-b0dc-23afaa44155d" />

## ✨ Key Features

* **🚀 Zero Installation:** Download the HTML file and open it in any modern browser. All image processing is done locally.
* **🔗 Advanced Transitions:** Connect rooms using arrows. Includes a **custom landing view fix** system (you decide where the camera looks when entering a new room) or use "spatial magic" that automatically preserves the North viewing angle.
* **🗺️ Interactive Floor Plan / Minimap:** Upload a 2D plan, add radar dots showing where the user is looking, and facilitate global navigation.
* **ℹ️ Information Points:** Add text hotspots over objects or important details.
* **🎨 Brand Customization:** Upload your own logo, add global titles, room descriptions, and adjust element colors to match your corporate identity.
* **💾 Multiple Export Formats:**
  1. **Single HTML File:** Export a clean, single-file tour ready to send via WhatsApp or email.
  2. **Editable Project:** Export Admin. Complete Tour. All in 1 file - For Administrator (With Sidebar for editing)

## 🚀 Demo and Direct Use

You can use the tool directly from your browser without downloading anything thanks to GitHub Pages:

👉 **[View and use 360° Tour Builder Pro online](https://pausegui.github.io/free-360-panoramic-viewer-virtual-tour-html/)**

## 🛠️ How to Use (Local)

1. Clone this repository or download the version in your preferred language: `index.html` (English language) or `index_es.html` (Spanish language).
2. Open it by double-clicking (it will open in Chrome, Firefox, Safari, or Edge).
3. Update the Visual Identity (e.g., add logo, colors).
4. You can upload a floor plan showing the property layout.
5. **Drag and drop your 360° photos** (2:1 equirectangular format) into the window. The system will optimize them automatically.
6. Use the right-hand menu to add your logo, upload a floor plan, and start connecting rooms with arrows.
7. Click **Save** when you are finished.

## 💻 Technologies Used

This tool is *Client-Side* and was built using fantastic community tools:
* [Pannellum](https://pannellum.org/): WebGL-based 360 panoramic rendering engine.
* [Tailwind CSS](https://tailwindcss.com/): CSS framework for a modern and fluid UI.
* [JSZip](https://stuk.github.io/jszip/): Library to create .zip files directly from the browser.

## 💡 How to Publish Your Tour (For End Users)

The player exported by this tool is a static HTML file. You can download it to your computer and work locally or, once configured, save it as HTML to send to a client.

If you want it online, you can host it for free using:
* **GitHub Pages** or **Vercel**
* Your own shared hosting (cPanel, Plesk) by uploading the exported `.zip` file.
* Any cloud service (AWS S3, Firebase Hosting, Netlify).

☕ **Found this tool useful?** [If you'd like, you can buy me a coffee to support the project.](https://paypal.me/pausegui?locale.x=es_ES&country.x=ES)

## 📄 License and Attribution
This project is distributed under the **MIT License**. You are free to use, modify, and distribute it for free.

**🤝 Request for Commercial Use:**
If you use this tool professionally or commercially (e.g., to generate virtual tours you sell to clients, or if you integrate it into your company's software), **I ask that you include a link to this GitHub repository** as a gesture of thanks.

You can do this in several ways:
* Adding a link on your website.
* Leaving the authorship HTML comment in the exported tours.
* Mentioning the tool on your social media or blog.

Open-source software grows through mutual support!

## 💻 Technologies and Acknowledgments (Credits)

This project would not be possible without the following incredible open-source tools. All credit goes to their respective authors:

* **[Pannellum](https://pannellum.org/)**: Copyright (c) Matthew Petroff. MIT License. The main engine for panoramic image rendering.
* **[JSZip](https://stuk.github.io/jszip/)**: Copyright (c) Stuart Knightley. MIT License. Used for compression and packaging of exported tours.
* **[Tailwind CSS](https://tailwindcss.com/)**: Copyright (c) Tailwind Labs, Inc. MIT License. Used for the graphical interface.

## Credits

This project was developed by **Pau Segui** in collaboration with **[OVACEN](https://ovacen.com/en/ "Digital newspaper")**. 

* Based on the following [Reference article](https://ovacen.com/en/create-panoramic-images-ai-free-virtual-tours/).
