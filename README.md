# Chia-Chen MSc Project
Development and evaluation of cloud-based speech control for the mobile robot

*   [Elisa-3 Robot](#robot)
    *   [Elisa3-arduino](#arduino)
    *   [pc-side-elisa3-library](#library)
*   [Goole Cloud Speech API](#api)
    *   [micstreaming.js](#micstream)
* * *   
<h2 id="robot">Elisa-3 Robot</h2>

<h3 id="arduino">Elisa3-arduino</h3>
<p>- Needs the Arduino IDE</p>
<p>- The Elisa3 Library can be downloaded from the wiki<br />
   - The wiki also explains how to add the Library to the IDE<br />
   - The program can be uploaded to the robots using the IDE.</p>
<p>- The program only allows the robots to respond to commands coming from the base station.<br /></p>

<h3 id="library">pc-side-elisa3-library</h3>
<p>- Running on OS Windows 10</p>
<p>- The radio module drivers should be installed on the PC. The Link can be found on GCtronic-wiki
http://www.gctronic.com/doc/index.php/Elisa-3/</p>

<p>- Once the project has been imported in the IDE you should be able to run it.<br />
   Input the number of robots and their addresses to connect with the base station.</p>
   
* * * 
<h2 id="api">Google Cloud Speech API</h2>

<h3 id="micstream">micstreaming.js</h3>
<p>- Using Nodejs to implement the streaming speech recogniton from microphone.<br />
https://cloud.google.com/speech-to-text/docs/streaming-recognize/</p>
<p>- Follow the instrutions to install Google Cloud Speech API from:<br />
https://github.com/googleapis/nodejs-speech/</p>
<p>- Using robot.js packet to simulate the keyboard pressing.<br />
http://getrobot.net/docs/node.html/</p>
