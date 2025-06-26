# ARChimEd - MolSym (Augmented Reality for Chimie and Education – Molecular Symmetry)

<div style="display: flex; align-items: flex-start;">
  <img src="https://github.com/user-attachments/assets/92bbee64-f221-4a7f-b24a-5d6c4a380d9d" alt="ARChimEd logo" width="200" style="margin-right: 20px;">
  <div style="text-align: justify;">
    <strong>ARChimEd - MolSym</strong> is a cutting-edge mixed-reality educational application developed for the Meta Quest platform. It enables students, educators, and researchers to interactively explore <strong>molecular symmetry</strong> in three dimensions. Through immersive visuals, AI guidance, and gamified modules, users can deepen their understanding of symmetry operations and point groups.
  </div>
</div>

<br><br>

> 📖 For detailed instructions and advanced usage of **ARChimEd - MolSym**, please refer to the [Wiki](../../wiki).

---

## 🚀 Features

* 3D visualization of molecules and their symmetry elements (axes, planes, center)
* Real-time manipulation and interaction using hands
* AI-powered avatar interaction and symmetry analysis
* Three learning modules: **Learning**, **Training**, **Testing**
* Clean, intuitive, and engaging UI designed for mixed reality


[![See the presentation on YouTube](https://img.youtube.com/vi/_RAdmGZ5mdU/0.jpg)](https://www.youtube.com/watch?v=_RAdmGZ5mdU)


---

## 📦 Installation

### 1. Via Meta Quest App Lab (when available)

* Go to the [Meta Quest Store](https://www.meta.com/experiences/) or search for "ARCHIMED - MolSym"
* Click **Get** to install the app directly on your headset

### 2. Via SideQuest (manual installation)

**Prerequisites**:

* Meta Quest headset + USB-C cable  
* Developer mode enabled on your Quest account  
* SideQuest app installed on your PC/Mac/Linux  

**Steps**:

1. Download the latest APK from the [Releases](https://github.com/username/ARCHIMED-MolSym/releases) section  
2. Connect your Meta Quest to your computer  
3. Open SideQuest and make sure your headset is detected  
4. Drag and drop the APK onto the SideQuest window or use the **Install APK** button  
5. Once installed, find the app in **Unknown Sources** in your headset  

## 🤖 AI Avatar (Gaber) – Setup and Rationale

ARChimEd – MolSym integrates an AI-powered virtual avatar to assist users in understanding concepts of molecular symmetry. The avatar, named Gaber in honor of the Persian alchemist <a href="https://en.wikipedia.org/wiki/Jabir_ibn_Hayyan" target="_blank">Jābir ibn Ḥayyān</a>, is designed to behave like a virtual chemistry professor. Gaber can answer your questions in real-time and guide you through the learning modules — but only if you choose to activate him.

> ✳️ Important: The AI avatar is optional. You can use ARChimEd – MolSym fully without activating Gaber. He is available only when you want help or a deeper explanation.

🧠 Why OpenAI API?

We chose to integrate OpenAI's API instead of running a local large language model (LLM) like LLaMA for several reasons:
* Cost Efficiency: Running a local LLM requires a powerful GPU-equipped computer, which is costly to purchase and maintain.
* Energy Consumption: LLMs are energy-intensive. Using the OpenAI API avoids unnecessary electricity costs.
* Ease of Use: The OpenAI API provides excellent performance, multi-language support (including French), and is easy to integrate.

This solution provides a high-quality conversational experience at a significantly lower cost — both in terms of hardware and energy.

---

## 🎓 Modules Overview

### 📘 Learning Module

An interactive 3D course introducing the core concepts of molecular symmetry. Explore real molecular models and visualize the effects of symmetry operations such as rotations, reflections, and inversions.

### 🧪 Training Module

Select from a curated library of 100+ molecules spanning all major point groups. Practice identifying symmetry elements by interacting with the molecule. Feedback and hints help guide learning.

### 🧠 Testing Module

Evaluate your understanding by attempting to identify the symmetry elements and point group of unknown molecules. Scores and achievements foster motivation and gamify the experience.

---

## 🧪 License

This project is free for academic and educational uses.  

---

**© ARChimED Project – Université d'Artois – 2025**
