# CS330

This project is a 3D scene built in OpenGL where I recreated a desk setup using a pencil, a book, a chapstick tube, and a roll of tape. Everything was built using basic shapes like cylinders, cones, a box, a plane, and a torus. The focus was not on making a perfect model, but on building something recognizable and correctly laid out using simple pieces.

When I started designing the scene, I broke everything down into basic shapes and focused on one object at a time. I found that it worked better to get something on the screen quickly and then adjust it instead of trying to plan everything out perfectly from the beginning. A lot of the design work came down to figuring out how objects relate to each other in 3D space, especially with scale, rotation, and position.

One of the biggest things I took away from this project was how much small adjustments matter. There were multiple times where something looked slightly off, and it ended up being a small issue with scale or rotation. The pencil was a good example of this. I originally had the scaling wrong, which made it look more square than round, and I didn’t notice it until I had another object in the scene to compare it to. After fixing that, the overall scene looked much better.

The way I handled the book was another small design decision that made a difference. Instead of putting the texture directly on the box, I added a thin plane on top so the book cover image would only show on the top and not repeat on the sides. That kept it looking cleaner and closer to the original photo.

From a development standpoint, I kept things consistent by using the same structure for each object and reusing functions for transformations, colors, and textures. I also made sure to test changes one at a time instead of adjusting everything at once. That made it easier to figure out what was actually causing an issue when something didn’t look right.

Iteration was a big part of this project. Most of the work was not writing new code, but going back and adjusting values until things looked correct. That process helped me get more comfortable working in 3D space and understanding how everything fits together.

This project also made me think more about how more complex models are created. Using primitives worked well here, but it made me curious about how more detailed or curved objects are built in real-world applications. Lighting was another area that took some trial and error, especially getting it to look balanced without being too bright.

Even though I do not plan to go directly into graphics, the skills from this project still apply. It helped with problem-solving, attention to detail, and understanding how systems respond visually to changes. I can see this being useful in other areas like UI work or anything involving visual feedback in applications.
