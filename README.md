# C2HO_Hackathon_MCTeam
 
 ## A Personal Audiovisual logo for C2HO
 
 MCTeam's contribution to this hackathon is a personalized audio visual logo for C2HO. <br>
 C2HO is a network, and to symbolize the network the logo uses the Dual-tone Multi-Frequency Signaling (DTMF) protocol used in telecommunication. Audio is generated that dials up the users IP adress, while the visual logo starts to build on screen. <br>
 The visuals are created in pygame and the background color will be different based on the users IP adress. <br>
 After dialing up, a voice message welcomes the user by their name, or at least the name of the owner of the computer who is used when logging on. <br>
  A sound logo ends the audio part of the logo, created by using the morse code for C2HO (-.-. / ..--- / .... / ---) as a rythm and the frequencies of the IP adress. This is all processed through some old fashioned Schroeder all pass reverb and a simple Impulse Response Delay, before being saturated for that last nice touch. <br>
  
Main libraries used:
* pygame
* numpy
* pyttsx3 (the voice synthesizer)
* socket (to get the ip and hostname)
<br>
The audio visual logo is generated in a jupyter notebook to adher to the rules of the C2HO hackathon <br>

For a demo version (which will be based on one of the creator's IP and hostname) can be seen in the folder RENDER.

 
