# Particle-System-Demonstration
Link to a video from CS475 - Parallel Programming - Demonstration of a Particle System on a GPU

The video is located here : https://media.oregonstate.edu/media/t/1_gaxpa0y9

Or you may download it above.

The final project for the class.  We were provided a template of the Visualization window and controls.  

My part was to add the dynamic color change to the particles, record performance for a number of different particles.
I also was required to add an additional spherical bummper to the existing 1 in the template.  I decided to add three more
and see the results.

I ran this on a laptop with a discrete video card so I also edited the code to look up the discrete video card and use that
instead of the on-board card.  I also added some logic so that if the number of platforms available in a system was only 1 meaning that
I had disabled the discrete GPU, the application would still function fine without the need to recompile.
