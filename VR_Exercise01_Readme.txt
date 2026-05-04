VR Exercise 01 - Depth Perception
readme.txt
TASK 1 - Depth Perception in 2D
1: Banana - Known Size
Added a banana model between the two spheres. A banana is an everyday object with a size everyone knows. Placing it next to the spheres gives the viewer a reference point to judge how far each sphere is.
    - Depth Cue: Familiar / Known Size

2: Pillars - Relative Size & Linear Perspective
Added a row of pillars between the spheres that get taller as they get closer to the camera. Objects that are the same real size but appear smaller are understood by the brain to be farther away. The pillars guide the eye into depth like a road perspective.
    - Depth Cue: Relative Size + Linear Perspective

3: Directional Light + Shadows - Shadow Cue
Added a directional light angled at the scene. Enabled cast shadows and receive shadows on all objects including the ground plane. Shadows on the ground anchor the spheres to a surface and show the viewer where each object sits in 3D space. Without shadows, objects look like they are floating with no clear distance information.
    - Depth Cue: Shading + Cast Shadow

4: Skybox - Environmental Context
Changed the camera background from solid black to the default Unity skybox. A visible sky and horizon line gives the brain a sense of space and environment which helps judge depth and distance.
    - Depth Cue: Environmental Context / Aerial Perspective

5: Fog - Atmospheric Perspective
Enabled fog in Window > Rendering > Lighting > Environment. Set to Linear mode with Start: 5 and End: 50. Objects farther from the viewer appear hazier and less sharp. The blue sphere looks slightly more faded than the red one which signals to the brain that it is farther away.
    - Depth Cue: Atmospheric / Aerial Perspective








TASK 2 - Depth Perception in 3D
Couldn't prepare the 3D over the VR due to hardware connectivity issue.
