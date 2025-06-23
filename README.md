# CS330-Journal
![Screenshot 2025-06-22 194312](https://github.com/user-attachments/assets/742e63ea-b3da-47a7-8e08-6ef056b0fa70)


This project was created as the final assignment for CS-330, showcasing the development of a fully interactive 3D scene using C++ and OpenGL. The objective was to replicate a real-world 2D image in a 3D space using basic geometric shapes and best practices in computer graphics. The final scene features a desk setup that includes a laptop and a flashlight. These objects were modeled using primitive shapes such as boxes, cylinders, cones, toruses, and planes to maintain low-polygon structure while preserving recognizable forms.

Textures were applied to enhance realism and detail. For instance, a royalty-free Windows wallpaper image was used on the laptop screen, while a keyboard layout image was projected onto the keyboard. These textures were correctly UV-mapped and rendered using OpenGL shaders. Lighting was implemented with two sources: a white point light and a colored directional light. These light sources included all components of the Phong shading model—ambient, diffuse, and specular—to create realistic lighting and shading effects in the scene.

The camera system was programmed to support full navigation of the 3D world. Users can move through the scene using the WASD keys for horizontal motion, Q and E keys for vertical movement, and the mouse for pitch and yaw to look around. Scrolling the mouse wheel adjusts movement speed. A keyboard shortcut also allows switching between orthographic and perspective projections, helping users toggle between a flat and depth-based visual experience.

The code is modular and organized into custom functions such as SetTransformations, SetShaderTexture, and DefineObjectMaterials. These functions help isolate logic related to object placement, texture application, and material setup, making the program easier to understand, debug, and expand. The project is accompanied by a compiled executable, texture folder, and a written design document that explains the development process and technical decisions. This project reflects my ability to create structured, interactive, and visually coherent 3D environments using industry-relevant technologies.

