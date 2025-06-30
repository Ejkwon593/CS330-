# CS330-Journal

![pic](https://github.com/user-attachments/assets/23a82d92-45f0-4f74-b870-0375e4207ff0)


For my final project, I recreated a 3D scene of a laptop and flashlight placed on a desk, closely modeled after a real photo. The goal was to take a 2D reference image and construct an interactive 3D version using OpenGL and C++. This project allowed me to explore core computer graphics concepts such as 3D modeling, lighting, textures, and camera navigation. It also gave me a chance to demonstrate my ability to apply course concepts in a visually clear, functional way.

One of the biggest things I learned was how to break down real-world objects into primitive shapes. I used boxes and planes for the laptop, and a combination of a cylinder, cone, torus, and box for the flashlight. Working this way helped me approach modeling logically and stay within the polygon limits. I also learned to apply textures using shader functions—this included applying a Windows wallpaper and keyboard image to the laptop, and plastic textures to the flashlight. Through this process, I became more comfortable manipulating UV coordinates and scaling textures appropriately.

When it came to developing the scene, I used modular coding strategies to define transformations, assign shaders, and organize object construction. Each milestone helped me evolve my approach. For example, I learned early on that positioning everything at (0,0,0) wasn’t practical, so I used the camera’s position and orbiting radius to properly visualize all objects from multiple angles. I also added interactivity, enabling the user to move around the scene using WASD and QE keys, mouse pitch/yaw, and a scroll-based speed adjustment.

This project has shown me how computer science, specifically computational graphics, can be used to build simulations and visuals with real-world relevance. These skills will be useful for future work involving 3D design, game development, or interactive environments. It also gave me insight into lighting models, such as the Phong shading technique, which I hadn’t used before. I now understand how ambient, diffuse, and specular light components affect object appearance in a virtual space.

Overall, completing this project boosted my technical confidence and helped me see how code, design, and user input come together in 3D visualization. I look forward to applying what I’ve learned in more advanced graphics work, and possibly exploring frameworks like WebGL or Three.js for web-based projects.
