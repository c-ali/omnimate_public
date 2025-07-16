# OmniMate

> An AI-Powered assistant for 2D art and animation. Increase your productivity without giving up control!



## ✨ Overview

This project is part of an ongoing initiative to augment traditional 2D art and animation workflows with artificial intelligence. Our mission is to give artists intuitive and powerful tools that enhance creativity and automate repetitive tasks, without giving up the fine-grained control that is needed to maintain professional-grade production quality.

In a constructive dialogue with multiple artists, we identified multiple parts of modern 2D animation workflows which require low creative input, but are very time consuming at the same time. We aim to partially automate such tasks, prompting input from the artist when needed.

It is our goal to move beyond the simple integration of already existing AI models and techniques (e.g. mask generation, upscaling), as done by [Photoshop AI](https://www.adobe.com/de/products/photoshop/ai.html) or [ToonBoom Ember](https://www.toonboom.com/ember). We want to combine and train new models in a way that is taylored to perfectly integrate in existing 2D animation workflows.

In our first milestone, we integrated the [MangaNinja](https://johanan528.github.io/MangaNinjia/model) model into a fully functional **Photoshop plugin**, enabling AI-assisted coloring inside a professional-grade environment.

This is a **closed-source** project which is currently in active development.

## 🚀 Key Features

- **MangaNinja integration** — integration of a state-of-the-art reference-based line-art coloration model.
- **Photoshop-native plugin** — built into Photoshop for seamless integration into professional workflows.
- **Designed for artists** — prioritizes control, quality, and compatibility with existing pipelines.

## 🛠 Tech Stack

- **Photoshop UXP Plugin** (TypeScript + HTML/CSS)
- **MangaNinja AI Model** (inference through Python backend)
- **Electron Bridge** for communication between frontend and backend
- **Node.js + Python** server for model hosting and plugin communication


## 🚧 Roadmap:

We're working toward:
- [ ] Multiple coloring suggestions the user can chose from 
- [ ] Automatic segmentation of the semantic components of the image, intregration in the coloring assistant
- [ ] AI-powered coloring assistant with layer awarenes
- [ ] AI-powered line-cleanup assitant
- [ ] Keyframe interpolation and automatic in-betweening

Stay tuned!


## 📇 Authors

This tool is developped in collaboration by [c-ali](https://github.com/c-ali) and [glbrs](https://github.com/glbrs).

📫 Contact: [christian.hxamg@gmail.com]  

## 🔒 Closed Source Notice

This project is not publicly available as open-source software at this time. If you're interested in collaboration, licensing, or technical details, feel free to reach out directly.
