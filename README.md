# 💜 Wellness Fitness Schedule & Family Challenge Hub

A lightweight, distraction-free weekly fitness web application paired with a private family challenge workflow on **FitOn**. Designed specifically for easy access on Chromebooks, desktop browsers, and mobile devices.

---

## 📋 Overview

* **Live Schedule Web App (`index.html`):** A single-file responsive dashboard built with **HTML5** and **Tailwind CSS** using the **"Lavender Dream"** aesthetic.
* **Tai Chi Days (Mon / Wed / Fri):** Direct YouTube video integrations featuring low-impact circulation, balance, and core flows.
* **Strength Days (Tue / Thu):** Direct portal links to **FitOn** to access structured, low-impact strength sessions (*Beginner Starter Mix* & *Barre Foundations*).
* **AI Strength Generator:** Built-in interactive JavaScript modal for quick, custom weighted routine generation on demand.
* **Family Fitness Challenge:** A private, multi-person group challenge hosted on the free **FitOn** app platform.

---

## 🗓️ Weekly Schedule Breakdown

| Day | Focus Area | Platform | Session Details |
| :--- | :--- | :--- | :--- |
| **Monday** | Tai Chi Flow | YouTube | *Circulation & Balance Flow* (15 min) |
| **Tuesday** | Low-Impact Strength / HIIT | FitOn Portal | *Beginner Starter Mix* |
| **Wednesday** | Tai Chi Flow | YouTube | *Midweek Challenge Flow* (25 min) |
| **Thursday** | Total Body Barre | FitOn Portal | *Barre Foundations* |
| **Friday** | Low-Impact Tai Chi Flow | YouTube | *14-Day Low Impact Flow* (20 min) |

---

## 🛠️ Technology & File Architecture

* **`index.html`**: The single primary application file hosting all HTML structural elements, Tailwind utility classes, inline SVG iconography, and modal control scripts.
* **Tailwind CSS (CDN)**: Script-based CSS engine configured with a custom extended `lavender` palette (`lavender-50` through `lavender-900`).
* **Unsplash Background Overlay**: Subtle fixed backdrop overlay (`opacity-20`) for a gentle ambient feel.

---

## 📲 FitOn Private Family Challenge Setup Guide

To connect family members to the Tuesday & Thursday routines on FitOn, follow these setup steps inside the FitOn app:

1. **Connect as Friends:**
   * Open FitOn $\rightarrow$ Go to the **Friends** tab.
   * Send invite links or connect via contacts with all participating family members.

2. **Post videos weekly:**
   * Go to **Workouts** $\rightarrow$ **Challenges** $\rightarrow$ **Add Challenge** (or **+** icon).
   * Name the challenge (e.g., *Strength Training Hub*) and add a custom cover icon.

3. **Configure Challenge Settings:**
   * **Private:** `ON` (Restricts access exclusively to invited family members).
   * **Select Workouts:** `YES` (Allows hand-picking specific routines like *Beginner Starter Mix* and *Barre Foundations*).
   * **Time Limit:** `NO` (Permits flexible completion without rigid expiration times).

4. **Invite Participants & Add Videos Continuously:**
   * Tap **Invite** on the challenge dashboard and select your connected family members.
   * You can edit the challenge at any time to add, update, or rotate new FitOn routines into the hub.

---

## 🚀 GitHub Pages Deployment Steps

1. **Repository Setup:**
   * Ensure your main code file is saved as `index.html` in the root folder of your repository.
2. **Commit Changes:**
   * Push or commit the updated `index.html` code to the `main` or `master` branch.
3. **Enable GitHub Pages:**
   * Go to **Settings** $\rightarrow$ **Pages**.
   * Under **Build and deployment** $\rightarrow$ **Source**, select **Deploy from a branch**.
   * Choose branch `main` / `root` and click **Save**.
4. **Refreshing Live Site:**
   * Once the deployment checkmark turns green, perform a hard refresh in your browser (`Ctrl` + `Shift` + `R` or `Ctrl` + `F5`) to clear cached assets.
