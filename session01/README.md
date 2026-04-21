# Session 01: Unity Workshop — Morning

Date: Wednesday, April 22
Time: 10:00 – 13:00

## Session Focus

This session introduces a no-code Unity workflow for artists. We begin with absolute basics of the Unity interface and navigation, followed by spatial composition, basic modeling in ProBuilder, scene setup, introductory spatial audio, and interactive scripts. The session concludes with a photogrammetry demo.

## Schedule & Agenda

### Session 1: 10:00 – 13:00

- **Unity Basics & Interface**
	- **The Big Five:** Understanding the Project view, Scene Hierarchy, Scene view, Game view, and the Inspector.
		- ![Unity Views](../images/unity-views.png)
		- *Further Reading:* [Explore the Unity Editor](https://learn.unity.com/tutorial/explore-the-unity-editor-1?version=2021.3)
	- **Coordinate System (X, Y, Z):** Unity is a 3D environment.
		- **Y is Up**, X is horizontal, and Z is depth.
		- ![Unity XYZ](../images/unity-xyz.png)
	- **Navigation & Manipulation:**
		- Moving in the Scene view: Use **WASD** and right-click to fly around.
		- Transforming objects:
			- **W:** Translate (Move)
			- **E:** Rotate
			- **R:** Scale
		- ![Basic Controls](../images/unity-basic_controls.png)
	- **Object Creation:** Creating primitive objects (Cubes, Spheres, Planes) and using the Move/Rotate/Scale tools.

- **Setup & Verification**
	- Ensure Unity 6 or the current version is installed.
	- **Install ProBuilder together on-site:**
		- Open your project and go to `Window` > `Package Manager`.
		- Select `Unity Registry` from the dropdown at the top.
		- Search for **ProBuilder** and click **Install**.
		- ![ProBuilder Installation](../images/pro-builder-install.png)

- **First-Person Navigation (The Drag-and-Drop Way)**
	- **Installation:** 
		- Go to the Asset Store and "Add to My Assets" the [Mini First Person Controller](https://assetstore.unity.com/packages/tools/input-management/mini-first-person-controller-174710).
		- In Unity, open `Window` > `Package Manager`, select **My Assets**, and install it.
	- **Setup:** 
		- Drag the `First Person Controller` prefab into your Scene.
		- **Important:** Delete the pre-existing `Main Camera` from your Hierarchy.
	- **Customization:** Select the controller in the Hierarchy and use the Inspector to adjust the **Height** if needed.

- **Gallery Mocking with ProBuilder**
	- Create to-scale 3D white cube environments.
	- Practice extruding, face editing, and vertex manipulation.
	- Build core structures such as walls and pedestals.

- **Building the Virtual Environment**
	- Place assets with drag-and-drop workflows.
	- Import and position 3D models, textures, and images.

- **Spatial Audio Basics**
	- Add and position an Audio Listener on player or camera.
	- Configure Audio Sources with 3D Spatial Blend set to 1.0.
	- Tune Min/Max Distance so audio fades naturally with distance.

- **No-Code Interactivity**
	- Introduce pre-made Trigger scripts, such as entering a zone to play a video.
	- Demonstrate AI-assisted generation of simple C# scripts for specific artistic behavior.

- **Physical-to-Digital Demo (The "Lunch Break" Assignment)**
	- Mobile photogrammetry demo with Polycam.
	- Instructions for scanning an object or space during the break.

## Session Checklist

- Unity installed and opening correctly.
- ProBuilder installed and visible in Unity.
- Mini First Person Controller installed and working.
- One simple interactive behavior implemented.
- Polycam or an alternative scanning app installed on mobile.

## Polycam Scanning Instructions & Alternatives

**Polycam (iOS/Android):**
- When you open Polycam, you may see a pop-up encouraging you to subscribe. You do **not** need to pay—Polycam allows up to 10 free scans.
- Scanning involves slowly rotating around your object, keeping your phone steady.
- When processing is complete, you can send yourself an email link to download the 3D model (choose the GLTF format for Unity compatibility).

**Free Alternatives to Polycam:**
- [3D Scanner App (iOS)](https://apps.apple.com/us/app/3d-scanner-app/id1419913995)
- [KIRI Engine (iOS/Android)](https://www.kiriengine.app/)
- [Scaniverse (iOS)](https://scaniverse.com/)
- [Trnio (iOS)](https://www.trnio.com/)
