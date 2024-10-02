# Text-to-Image Generation for Personalized Story Illustration
### Curator: Neudachina Eva
### Students: Sedov Sergey, Kiselev Maksim

This project focuses on generating sequential illustrations for user-provided stories primarly using the Stable Diffusion model.
Apparently, we are going to use the recently introduced Guide-and-Rescale guider, which substantially improves editing capabilities of DDIM inversion. 
We plan that LLM will decompose the story into key actions, and for each action, a consistently styled image will be generated.
Most likely, we are going to gradually edit each image, separating the initial story into the first "scene setup" step and following "action editing" steps.

Key Features:
Story Decomposition: Break stories into actions with an LLM.
Consistent Image Generation: Gradually generate stylistically aligned images for each action.
Character Continuity: How could we support the consistency of characters across the image sequence? That's the reason to use Diffusion Guidance methods.
