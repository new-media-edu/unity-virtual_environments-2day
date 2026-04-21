# Workshop: Virtual Environments & Gallery Mockups

This workshop is designed for artists who want to utilize 3D software for two primary purposes: mocking up physical gallery installations for spatial planning and developing native virtual environments. The curriculum bypasses the steep learning curve of programming by focusing entirely on a no-code, drag-and-drop workflow within Unity.

Participants will learn to compose complex 3D scenes, manipulate lighting, and organize spatial layouts. While the workshop avoids manual coding, the final session will demonstrate how to implement pre-made scripts and utilize AI-assisted scripting using LLMs to add interactivity, offering a bridge to more advanced technical development.

## Wednesday, April 22: Unity Workshop

### Session 01: 10:00 am – 1:00 pm CET
- **Unity Basics & Interface:**
    - Understanding the Project view, Hierarchy, Scene view, Game view, and Inspector.
    ![Unity Views](images/unity-views.png)
    - **Coordinate System:** Navigating in 3D (X, Y, Z) where **Y is Up**.
    ![Unity XYZ](images/unity-xyz.png)
    - **Manipulation:** Using **W, E, and R** for Translate, Rotate, and Scale.
    ![Basic Controls](images/unity-basic_controls.png)
- Setup & Verification:
    - Ensure Unity 6 or the current version is installed.
    - **On-site ProBuilder Installation:** Install ProBuilder together during the session using the Unity Package Manager.
    - ![ProBuilder Installation](images/pro-builder-install.png)
- **First-Person Navigation:**
    - Install the **Mini First Person Controller** from the Asset Store via Package Manager.
    - Drag and drop the prefab into the scene and **delete** the pre-existing `Main Camera`.
- Gallery Mocking (ProBuilder):
    - Use ProBuilder to create to-scale 3D white cube environments.
    - Practice basic extruding, face editing, and vertex manipulation to build walls and pedestals.
- The Virtual Environment:
    - Navigate the 3D viewport and the Hierarchy.
    - Use drag-and-drop asset placement for 3D models, textures, and images.
- Spatial Audio:
    - Set up the Audio Listener on the player or camera.
    - Configure Audio Sources with 3D Spatial Blend set to 1.0.
    - Adjust Min/Max Distance curves so sound fades realistically as the user walks away from a virtual object.
- No-Code Interactivity:
    - Introduce pre-made Trigger scripts, such as entering a zone to play a video.
    - Demonstrate AI-assisted generation of simple C# scripts for specific artistic behavior.
- Physical-to-Digital Demo:
    - Demonstrate Polycam for mobile photogrammetry.
    - Provide instructions for scanning an object or space during the lunch break.

### Lunch Break: 1:00 pm – 2:00 pm CET
- *Task: Scan a physical object or space to bring into the afternoon session.*

### Session 02: 2:00 pm – 4:00 pm CET
- Importing Reality:
    - Bring lunch break photogrammetry meshes into Unity.
    - Fix scale issues and apply basic shaders to captured textures.
- Atmosphere & Lighting:
    - Manipulate Skyboxes and Directional Lights.
    - Use Point Lights to simulate gallery spotlights.
- Assisted Studio Time: Final hour dedicated to refining individual mockups or environments with 1-on-1 assistance.

