# CS 330 Final Project – 3D Scene and Design Decisions

This repository includes the final submission for the SNHU CS 330 course: a complete 3D scene built using OpenGL, along with the associated Design Decisions documentation.

## 🧱 Project Overview

The 3D scene represents a small furnished room, including textured and lit models like a couch, a coffee table, a lamp, and a bookshelf. The scene incorporates textures, a camera system, manually placed lighting, and a shader-based Phong lighting model. These elements demonstrate an understanding of computational graphics pipelines and modular scene rendering.

---

## 🔧 Design Reflection

### 🧠 How do I approach designing software?

My approach to software design begins with understanding the requirements, then breaking the project into manageable modules or systems. For this 3D scene, I utilized `SceneManager`, `ShaderManager`, and mesh-loading systems to isolate responsibilities. This modular approach helped me isolate bugs and scale complexity safely.

### 🛠️ What new design skills has your work on the project helped you to craft?

This project improved my understanding of **scene composition**, **light-material interaction**, and **shader parameterization**. I also learned how to balance performance with visual realism, especially when optimizing fragment shaders and adjusting light properties to simulate soft lighting.

### 🧩 What design process did you follow for your project work?

I followed an iterative design process: first prototyping basic geometry and then layering on textures, lighting, and camera movement. I refined each element step-by-step, always testing before adding new features. This allowed me to maintain functionality while enhancing visual quality.

### 🔁 How could tactics from your design approach be applied in future work?

This modular and test-driven design approach is ideal for larger software projects. I now appreciate the importance of writing reusable rendering functions, designing scalable scene systems, and using shader uniforms for clean parameter control — all of which can be adapted to simulation tools, games, and visual interfaces.

### 🖼️ Screenshot of 3D Scene

![Living Room Scene](https://github.com/rypeguero/OpenGL/blob/main/Living%20Room%203D%20Scene.png?raw=true)

---

## 💻 Development Reflection

### ⚙️ How do I approach developing programs?

I begin by identifying the core functional components and building them one at a time. For the 3D scene, I prioritized clean integration of the rendering loop, asset loading, shader binding, and texture management before working on aesthetic features.

### 🆕 What new development strategies did you use while working on your 3D scene?

This was my first time writing and debugging GLSL shaders, working with material structs, and implementing per-fragment lighting. I also implemented UV scaling and texture binding, which gave me hands-on experience with OpenGL's state machine model.

### 🔄 How did iteration factor into your development?

Iteration was key: I first built a scene using only colors and diffuse light, then added ambient and specular components to improve realism. Each step built upon the last, letting me verify stability before adding complexity.

### 🧬 How has your approach to developing code evolved?

Over the milestones, I shifted from hardcoded color settings to parameterized, shader-based lighting and material control. My code became more modular and reusable, especially in how I managed textures and lighting in the `ShaderManager`.

---

## 🎯 Future Applications

### 🎓 How can computer science help me reach my goals?

Computer science equips me with technical tools and logical thinking to tackle real-world problems — from visual simulation to cybersecurity. This course showed me how programming and math power 3D experiences, and I now feel confident applying this to fields like VR, training systems, or game engines.

### 👨‍💻 How do computational graphics and visualizations apply to my future education or career?

I now understand how lighting, textures, and geometry are processed in real-time applications. These skills are essential for any software involving UI/UX, 3D engines, or simulations. Professionally, I can leverage this to visualize secure environments, build interactive models, or prototype realistic spaces for education or research.

---

📁 **Included Files**
- `3D_Scene_Final.zip` – Visual Studio solution, shaders, textures, and EXE
- `Design_Decisions.pdf` – Design document outlining project choices
