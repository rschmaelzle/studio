---
title: "Project: AR Model Viewer"
date: 2024-03-20
summary: "Implementing Google's <model-viewer> component for AR-ready assets."
tags: ["Code", "AR", "Google"]
---

This project tests the implementation of the **Google Model Viewer** component. 

Unlike the A-Frame scenes in the Gallery, this tool is designed for inspecting specific objects (artifacts, products, scientific models). If you open this on a mobile phone, you can place the astronaut in your real-world living room.

### Live Demo

<iframe 
    src="https://rschmaelzle.github.io/studio/apps/ar-viewer.html" 
    width="100%" 
    height="500px" 
    frameborder="0"
    allow="camera; microphone; xr-spatial-tracking">
</iframe>

[View Full Screen](https://rschmaelzle.github.io/studio/apps/ar-viewer.html)

---

### How it works
It uses the `webxr` standard to detect if the device supports Augmented Reality.