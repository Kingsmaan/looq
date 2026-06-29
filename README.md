<h1 align="center">Looq 👁️✨</h1>

<p align="center">
  <strong>A high-performance, real-time facial recognition and analysis tool.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Vite-B73BFE?style=for-the-badge&logo=vite&logoColor=FFD62E" alt="Vite" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
</p>

> **Looq** is a powerful web application that leverages advanced computer vision to capture, register, and recognize human faces in real-time. Beyond seamless identity verification, Looq instantly analyzes facial features to determine age, gender, and current emotional state, delivering highly accurate results directly in the browser.

---

## ✨ Key Features

* **Real-Time Facial Recognition:** Captures a user's face, registers their identity with a name, and instantly auto-detects them in future sessions with near-perfect accuracy.
* **Live Demographic Analysis:** Instantly estimates the **age** and **gender** of any detected face on the camera feed.
* **Emotion & Mood Detection:** Analyzes facial expressions to determine the user's current mood (e.g., happy, sad, surprised, neutral) in real-time.
* **Modern, Responsive UI:** Built with an intuitive, dark-themed interface that adapts flawlessly to both desktop and mobile screens.
* **Browser-Based:** Runs efficiently directly in the web browser using device webcams with zero external hardware required.

---

## 🛠 Tech Stack

Looq is built on a modern, lightning-fast frontend architecture:

* **Framework:** React 18
* **Build Tool:** Vite
* **Styling:** Tailwind CSS
* **Components:** shadcn/ui & Radix Primitives
* **Routing:** React Router DOM
* **Computer Vision / AI:** (Insert your specific AI library here, e.g., *face-api.js*, *TensorFlow.js*, or your backend Python/OpenCV API)

---

## ⚙️ How It Works

1. **Registration:** A user stands in front of the camera, and the system captures their unique facial landmarks, associating them with a provided name.
2. **Analysis:** The underlying machine learning models process the video feed frame-by-frame to extract demographic data (age, gender) and emotional cues.
3. **Detection:** When the registered user re-enters the frame, the system cross-references the live feed against stored profiles, displaying their name alongside live analytics instantly.

---

## 🚀 Quick Start

### Prerequisites

Ensure you have **Node.js** (v18 or higher) and **npm** installed on your machine.

### Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Kingsmaan/looq.git](https://github.com/Kingsmaan/looq.git)




# Welcome to your Lovable project

## Project info

**URL**: https://lovable.dev/projects/REPLACE_WITH_PROJECT_ID

## How can I edit this code?

There are several ways of editing your application.

**Use Lovable**

Simply visit the [Lovable Project](https://lovable.dev/projects/REPLACE_WITH_PROJECT_ID) and start prompting.

Changes made via Lovable will be committed automatically to this repo.

**Use your preferred IDE**

If you want to work locally using your own IDE, you can clone this repo and push changes. Pushed changes will also be reflected in Lovable.

The only requirement is having Node.js & npm installed - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)

Follow these steps:

```sh
# Step 1: Clone the repository using the project's Git URL.
git clone <YOUR_GIT_URL>

# Step 2: Navigate to the project directory.
cd <YOUR_PROJECT_NAME>

# Step 3: Install the necessary dependencies.
npm i`

# Step 4: Start the development server with auto-reloading and an instant preview.
npm run dev
```

**Edit a file directly in GitHub**

- Navigate to the desired file(s).
- Click the "Edit" button (pencil icon) at the top right of the file view.
- Make your changes and commit the changes.

**Use GitHub Codespaces**

- Navigate to the main page of your repository.
- Click on the "Code" button (green button) near the top right.
- Select the "Codespaces" tab.
- Click on "New codespace" to launch a new Codespace environment.
- Edit files directly within the Codespace and commit and push your changes once you're done.

## What technologies are used for this project?

This project is built with:

- Vite
- TypeScript
- React
- shadcn-ui
- Tailwind CSS

## How can I deploy this project?

Simply open [Lovable](https://lovable.dev/projects/REPLACE_WITH_PROJECT_ID) and click on Share -> Publish.

## Can I connect a custom domain to my Lovable project?

Yes, you can!

To connect a domain, navigate to Project > Settings > Domains and click Connect Domain.

Read more here: [Setting up a custom domain](https://docs.lovable.dev/features/custom-domain#custom-domain)
