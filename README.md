# 🐕 React 3D Dog Scroll Experience

An interactive 3D web experience built using React and Three.js where a 3D dog model responds to scroll and hover interactions with smooth animations, matcap transitions, and shader customization.

---

## ✨ Features

- 🎯 Scroll-based 3D animation using GSAP + ScrollTrigger
- 🎨 Dynamic matcap texture transitions (shader-based)
- 🧠 Custom shader manipulation using `onBeforeCompile`
- 🐶 Animated GLTF 3D model with skeletal animation
- 🖱️ Hover-based interactions triggering visual changes
- 🌌 Fullscreen immersive canvas experience
- ⚡ Optimized with React Three Fiber hooks

---

## 🧱 Tech Stack

### Frontend

- React (Component-based UI)

### 3D & Rendering

- Three.js
- React Three Fiber (`@react-three/fiber`)
- Drei (`@react-three/drei`)

### Animation

- GSAP
- ScrollTrigger
- @gsap/react

---

## 📚 Concepts Used

### 🎮 Three.js / WebGL

- Scene, Camera, Renderer
- Mesh & Materials (Matcap Material)
- Texture Mapping
- Normal Maps
- GLTF Model Loading
- Lighting (Directional Light)
- Tone Mapping & Color Space

### ⚛️ React Three Fiber

- `Canvas` for rendering
- `useThree` for renderer control
- `useGLTF` for loading models
- `useTexture` for textures
- `useAnimations` for model animation
- Declarative 3D scene building

### 🎨 Shader Customization

- `onBeforeCompile`
- Custom uniforms
- Fragment shader manipulation
- Texture blending with `mix()`
- Smooth transitions using `smoothstep()`

### 🎞️ GSAP Animation

- Timeline-based animation
- ScrollTrigger integration
- Smooth scrubbing animations
- Property interpolation

### 🧩 Advanced Interaction

- DOM + 3D interaction sync
- Hover-triggered shader updates
- Dynamic material swapping

---

## 🧠 What I Learned

- How to integrate Three.js with React using React Three Fiber
- Creating and modifying shaders without writing full GLSL from scratch
- Syncing scroll-based animations with 3D objects
- Handling real-time texture transitions
- Managing performance in WebGL scenes
- Combining DOM interactions with 3D rendering

---
