# **Workshop: Virtual Environments & Gallery Mockups**

This workshop is designed for artists who want to utilize 3D software for two primary purposes: **mocking up physical gallery installations** for spatial planning and **developing native virtual environments**. The curriculum bypasses the steep learning curve of programming by focusing entirely on a **no-code, drag-and-drop workflow** within Unity.

Participants will learn to compose complex 3D scenes, manipulate lighting, and organize spatial layouts. While the workshop avoids manual coding, the final session will demonstrate how to implement **pre-made scripts** and utilize **AI-assisted scripting** (using LLMs) to add interactivity, offering a bridge to more advanced technical development.

## **Wednesday, April 22: Unity Workshop – Day 1**
**10:00 am – 1:00 pm CET**

* **Setup & Verification:** Ensure Unity 6 (or current version) and **ProBuilder** are installed. 
* **Gallery Mocking (ProBuilder):** * Using ProBuilder to create to-scale 3D "white cube" environments.
    * Basic extruding, face editing, and vertex manipulation to build walls and pedestals.
* **The Virtual Environment:** * Navigating the 3D viewport and the Hierarchy.
    * Drag-and-drop asset placement (bringing in 3D models, textures, and images).
* **Spatial Audio:** * Setting up the **Audio Listener** (the "ears") on the player/camera.
    * Configuring **Audio Sources** with 3D Spatial Blend set to **1.0**.
    * Adjusting **Min/Max Distance** curves so sound realistically fades as the user walks away from a virtual object.
* **The Physical-to-Digital Demo:** * Demonstration of **Polycam** for mobile photogrammetry.
    * Instructions for the "Circular Scan" (for objects) vs. "Room Scan" (for spaces).

## **Overnight Assignment**
**The Physical-to-Digital Bridge**

* **Software:** Download **Polycam** (Free version).
* **Task:** Identify a physical object or a corner of a room at the Akademie.
* **Capture:** Perform a scan to generate a 3D mesh.
* **Export:** Upload the scan and export it as a **.obj** or **.glb** file to be used in the next session.

## **Thursday, April 23: Unity Workshop – Day 2**
**10:00 am – 1:00 pm CET**

* **Importing Reality:** * Bringing the overnight photogrammetry meshes into Unity.
    * Fixing scale issues and applying basic shaders to captured textures.
* **Atmosphere & Lighting:** * Manipulating **Skyboxes** and **Directional Lights**.
    * Using "Point Lights" to simulate gallery spotlights.
* **No-Code Interactivity:** * Introduction to pre-made **"Trigger" scripts** (e.g., *Walk into a zone to play a video*).
    * **AI for Unity:** A demo on how to use AI tools to generate simple C# scripts for specific artistic needs (e.g., *Make this object rotate slowly* or *Change color when clicked*).
* **Assisted Studio Time:** Final hour dedicated to refining individual mockups or environments with 1-on-1 assistance.

### **Technical Guide for Participants**
* **Unity Version:** Unity 6 (LTS).
* **ProBuilder:** Found in *Window > Package Manager > Unity Registry*.
* **Polycam:** Available on iOS/Android. The free tier allows for a limited number of "captures" and exports, which is sufficient for this exercise.
* **Asset Prep:** Remind participants to bring any JPG/PNG images or MP4 videos they might want to "hang" in their virtual gallery.# unity-virtual_environments-2day
