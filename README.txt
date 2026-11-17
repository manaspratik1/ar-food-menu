MY FIRST 3D VIEWER

WHAT YOU NEED
- Visual Studio Code
- The Live Server extension in VS Code
- An internet connection (the starter loads the sample 3D model and viewer library online)

STEPS
1. Extract this folder if you downloaded the ZIP.
2. Open Visual Studio Code.
3. Choose File > Open Folder and select the ar_3d_starter folder.
4. Install the extension named "Live Server" by Ritwick Dey.
5. In VS Code, right-click index.html and choose "Open with Live Server".
6. Your browser should open a local address similar to http://127.0.0.1:5500/index.html.
7. Drag the model to rotate it. Scroll or pinch to zoom.

NOTE
- Keep the internet connection on. The sample Astronaut.glb and model-viewer library are loaded from public URLs.
- To use your own model later, put your .glb file in this folder and replace the model-viewer src URL in index.html with a relative path, for example: src="models/your-model.glb".
- This starter only displays a 3D model. AR and the question-answer interface can be added after this works.
