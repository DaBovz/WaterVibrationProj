# WaterVibrationProj
Using a speaker and different hertz, I will observe how different hertz played by the speaker will effect the ripples in the water.

7/5/25
Current setup is a speaker is oriented upward and attached to a long cylinder right on top of it. The cylinder has a dip on the top that allows for a thin layer of water to be placed on the top. The cylinder and speaker is also held upright by a rectangular box. By connecting a computer to the speaker, I play different hertz and see the ripples on the top. 

Equations used:
λ = v/f (v is speed of the surface of the water in m/s, f is the frequency in hertz)
v = Sqrt(g*h) (g is gravity in m/s^2, h is the depth of the water in m)

7/13/25
Setup has changed so that instead of the original rectangular box I used to hold the setup up, I used a smaller cube-shaped box to hold the speaker upright. Also, there is no longer a cylinder attached to the top of the speaker. Instead, I placed a 90mm petri dish directly on the speaker. However, the results slightly differ from the previous setup as the frequency at which the ripples get chaotic seem to be lower. This is likely due to how much energy and vibrations is actually coming from the speaker to the water.

7/15/25
Setup change: I stacked multiple thin sponges on top of each other and placed them right on top of the cone of the speaker. Then, I placed the petri dish right on top of the tower of sponges. Now, results seem that the waves get chaotic at around 45hz range and the best frequency to see consistent ripples seems to be 35hz.

7/16/25
Improved the stack of thin sponges by carving the bottom 3 layers to have a smaller diameter so it fits the cone shape of the speaker. Also, I lowered the amplitude of the noise to prevent greater chaotic ripples. I am aiming to look for a solution so that the stack of sponges doesn't shift at all when the sound is played. Either some sort of more-frictiony material on the parts where the sponge and speaker touch or something else completely different from the sponge tower. 

7/21/25 

Made a Lego stand/structure to hold the speaker up straight and level. Continued using the sponge base to hold the petri dish above the speaker. Also used a flashlight level with the water to help view the ripples.

Science stuff:

Chaotic ripples/patterns in the water isn't as straight forward as the sound being too high frequency.

It depends on the energy buildup in the water. When there is too much energy in the system, the system will become unstable and chaotic. The energy depends on a multitude of factors:

- Frequency: Controls how rapidly energy is delivered to the water

- Amplitude/Volume: Changes the amount of energy per wave

- Time the sound is played: The longer the sound is being played, the more energy will accumulate in the water system.


All can be altered with the python script but I'm planning on choosing just one to be the independent variable while keeping the others controlled. However, time is the trickiest as even low frequencies will eventually become chaotic if given enough time. I think that the best course of action would be to keep a controlled amplitude, make the independent variable the frequency, and also only record up to frequencies where the ripples show some stability that can be recorded before it becomes chaotic.

Additional Notes:
Ohms in speakers means the electrical resistance which controls how much current flows through the speaker in this case. So overall, lower Ohms means more current and higher Ohms means less current. Furthermore, more current means more energy/current which in this case means louder volume. So lower Ohms means higher volume and vice versa in our case.

I created another possible experiment that is similar to the current one but instead of sound, it is slightly simpler. However, it still has similar concepts of water ripples and fluid dynamics. Possible issues of this idea is that the change of height may not have a significant enough impact on the wavelength of the ripples. Although it has a more direct impact on the amplitude of the waves, measuring the change in amplitude would be very difficult. Check 7-21-25Diagram.pdf

7/22/25

I think that to have the most ideal and efficient method of conveying the sound vibrations into the water, there should be a different way of attaching the petri dish to the speaker than using the current sponge setup. Some possible ideas include gluing a metal sheet on top of the speaker and then attaching the petri dish to the plate. Another possibly simpler idea would be attaching the petri dish directly to the speaker using some putty substance such as blu tack.
Furthermore, it could be a combination of those two where the thin metal sheet is glued to the speaker and then the petri dish is attached to the sheet using the putty substance.

Shutter speed:

When recording/taking photos of the ripples in the water, the shutter speed of the camera and in our case the Iphone's shutter speed will likely impact the picture. I do think that if I do record with slow-mo it may be able to produce better results.  

Tested 60hz with an amplitude of 0.5. (Not exactly sure what units the amplitude is in simple audio/the python script)
Update: When I tried to film using slow-mo on my phone, there seems to be less waves visible compared to seeing it with my own eyes. This is likely due to a low shutter speed.

Important info: Even with a material such as rubber or sponge that absorbs the energy coming from the speaker, this will mainly affect the amplitude and not the frequency of the waves. Although, if the amplitude is too little, the frequency will likely be inaccurate too.

However, I still do think an alternate setup is needed instead of the current sponge one as when the sound is played for a long enough time, the sponge still shifts which produces non-ring-shaped ripples and therefore inaccurate results.

7/23/25

SPL: Sound Pressure Level

It is a measure of how loud/intense a sound wave is. It's in the units of decibels (dB SPL) and is based off of Pascals (Pa) which is the unit for the sound pressure of a sound wave.

I = (V/R):

This is Ohm's law which relates current, voltage, and resistance.

Current (in Amps): How much electric charge is passing through a conductor. If we think of the circuit like a water hose, the current would be how much water would be flowing out at the end. A wider hose would have more water coming out and a smaller one less.

Voltage (in Volts): Kind of how fast the current is passing through the conductor (flow rate). In the water hose example, it would be like the pressure of the water in the hose. A water gun would have less water coming out but higher pressure than a hose.

Resistance (in Ohms): Controlling the current so it isn't too high and therefore dangerous. In other words, it slows down the flow of current. Adding a resistor will change the current of the entire circuit.

P = V * I

P (Wattage in Watts): Used to measure how much energy is being used/produced per second.

For the speaker setup, I think using a reusable adhesive like blu-tack would be the best. It should be good at transmitting vibrations, easy to adjust, and also easy to remove if needed.

https://www.amazon.com/Blu-Tack-S050Q-Reusable-Adhesive-75g/dp/B001FGLX72

7/24/25

For the relationship between Power and SPL, I found that it has a logarithmic correspondence. Basically, you need to double the power to increase the SPL by 3dB.

Mainly studied how speakers work and also physics relating to sound. How for most speakers, there is a electromagnet, which is usually created by a copper coil, and a larger normal magnet around it. The electromagnet bounces back and forth according to the electrical signals given which effects how the magnetic fields of the electromagnet and the normal magnet interact. This "back and forth" movement creates the pressure forces in the air that we interpret as sound.

For sound waves, what I mainly learned is how sound waves consist of high pressure and low pressure areas of air that is created by the source which could be anything from speakers to a balloon popping. The terms for these are "compressions" for high pressure areas and "rarefactions" for the low pressure areas. Also little extra fact but I learned about timbre which is the unique waveform or sound that different sources of sound such as different instruments make. For example, even if a piano and a trumpet both play a middle c note, you can still tell the difference in the sound by their different timbre.

7/25/25

Read chapter 1 in the JBL Sound System Design Reference Manual.

Learned mainly about modelling sound waves as sine waves, along with the relationship between wavelength, velocity, and frequency.

Learned about how phase differences between two separate sounds can effect the amplitude of the waves. Alongside this, I learned about delayed sine waves where two signals arrive at a place at differing times.

Also learned a bit about diffraction of sound and how the size of the obstacle relative to the wavelength of the wave affects the sound waves.

Learned about how temperature affects sound waves as in areas of higher temperatures, the velocity will slightly increase relative to colder areas as warmer air molecules move faster/transmit the vibrations quicker. Lastly, I learned about how wind affects sound waves which is pretty straight forward. 
