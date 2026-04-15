# Coherence Audio Website & User Manual

This repository contains the source code for the official website and documentation of **Coherence Audio** - the Windows native multi-track audio recorder for USB microphones.

The site is built using **Jekyll** and hosted on **GitHub Pages**. It features a modern, cinematic scroll-snapping landing page and a fully responsive, dark-mode user manual that matches the aesthetic of the Windows 11 app.

## Repository Structure
* `/` (Root) - Contains the landing page (`index.html`) and configuration files.
* `/_layouts/` - Contains the HTML templates for the base site, the cinematic homepage, and the documentation grid layout.
* `/manual/` - Contains all the Markdown (`.md`) files that make up the User Manual.
* `/images/` - Contains the screenshots, logos, and background images used across the site.

## Running Locally (Docker)
To test the website locally without installing Ruby dependencies on your machine, you can use Docker.

1. Ensure Docker Desktop is running.
2. Open your terminal in the repository root.
3. Run the following command:
   ```bash
   docker compose up
   ```
4. Open your browser and navigate to `http://localhost:4000`.
