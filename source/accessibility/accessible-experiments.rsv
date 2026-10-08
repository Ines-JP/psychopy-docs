How to create accessible experiments?
If you are working with a specific population or clinical group, you might want to adapt your experiment in various ways to make it easy for your sample to interact with. 

Resources:
﻿W3Accessibility Principles
﻿W3How to Meet WCAG (Quickref Reference)
﻿EuropaPOUR-CAF principles: Flexible﻿

Content: 
How to create accessible experiments?
Add Text-to-Speech & Read Aloud Features
Add Volume Adjustments
Use Appropriate Colour Palettes
Allow participants to adjust font or stimulus size
Accessible Font Choices
Sign language videos or text transcriptions for audio content
Operable user interface
Time experiments appropriately
Avoid photosensitive content
Information must be easy to understand

Add text-to-speech and read aloud features
Tags: Accessibility for those with sight or reading difficulties

Text-to-speech applications (e.g. NVDA) are not compatible with running PsychoPy experiments (or PsychoJS experiments running in browser). However, you can easily add sound components to your routine that caption any text, narrate instructions, or describe non-text content (e.g. images, graphs, or videos). A demo experiment in which text is read aloud upon clicking on it can be found here﻿.


Add volume adjustments
Tags: Hearing accessibility

Allow the participant to select the volume at which the sound is presenting, to ensure it is at an appropriate level. You can start your experiment by presenting a sample sound in a loop and ask the participant to adjust their device volume to a comfortable level (and press a key or click an onscreen button to confirm the volume is at a comfortable level). Alternatively, you can ask your participant to use the keyboard or onscreen buttons to adjust the PsychoPy volume of sound components directly and then use this volume in all sound components throughout the task. A demo in which the participant can adapt the volume of a white noise recording with an on-screen slider can be found here.


 
Use appropriate colour palettes 
Tags: Accessibility for those with sight difficulties

Use colourblind-friendly palettes and high contrast in your experiments' visual components. This includes stimuli components (e.g. text, polygons, images, videos…) but also responses (e.g. mouse, slider, textbox…). You can get more information about accessible colour palettes here﻿. General recommendations include using blues with reds or oranges, as they are the most colourblind-friendly combination.
You could also allow your participant to choose a bespoke colour palette for your experiment; a demo experiment in which the participant can modify the text and background colours can be found here.


Allow participants to adjust font or stimulus size
Tags: Accessibility for those with sight difficulties

For text, you can modify letter height in the Formatting tab within the component. For images, you can modify the size of stimuli in the Layout tab. To ensure that the size is kept constant between runs, ensure that the height unit you are using is appropriate to be read, and maintain the screen size of your participants constant. You can make sure only devices of a certain size access the experiment 

A demo experiment in which you can modify the size of the text can be found here﻿.

Accessible font choices
Tags: Accessibility for those with sight difficulties

Use a Sans Serif font (i.e., without decorative strokes) to facilitate readability (you can find some guidance on font recommendations here). Sans Serif fonts include Arial, the default font of PsychoPy text. They also include Calibri, Open Sans, or Verdana. You can modify the font by typing its name in the formatting setting window of the text component. If you do not have a specific font installed, PsychoPy will ask you to download it.
 
Add sign language videos or text transcriptions for audio content
Tags: Accessibility for those with listening difficulties

You can add a video component to your routine that translates your audio content to sign language, or include a text component of sufficient contrast and size (demo here) that displays the dictation of the audio (demo here).
When possible, pair audio cues with visual ones.

Operable user interface
Tags: Accessibility for those with sight or mobility difficulties

Avoid using high-dexterity inputs, such as touch screen or mouse clicks, to advance the experiment or record your responses. Instead, use lower-dexterity interfaces such as large buttons, a keyboard, or sound sensors.

If you need a mouse click, make sure the cursor is a high-contrast colour and large enough to be visible to everyone. You can add a cursor image and set its position to `mouse.getPos()` every frame, and adapt its size and colour as needed. You can also allow the participant to adapt the mouse image; a demo experiment in which the size and the colour of the cursor can adapted is found here﻿.
 
Time experiments appropriately 
Tags: Accessibility for those with focus or learning difficulties

Allow users to decide when to move to the next routine. To avoid the routine finishing by itself, leave the duration setting of your routine empty. To allow the routine to finish when pressing a keyboard key, create a keyboard response with no duration, “Force end of routine” ticked, “Register keypress on…” press, and select whichever allowed keys you specify to the user (e.g. ‘space’).

Allow users to repeat the instructions (either text and/or sound). A demo experiment in which the audio is repeated whenever ‘r’ is pressed can be found here.

You can also allow participants to move forwards and backwards through instruction slides. You can find a tutorial on this here. 
 
Avoid photosensitive content
Tags: Accessibility to avoid seizures

Avoid content that flashes. If flashing content is necessary, warn users before it appears and, if possible, let them skip that routine, e.g. by pressing a specific key. To do so, create a keyboard response with no duration, “Force end of routine” ticked, “Register keypress on…” pressed, and select whichever allowed keys you specify to the user (e.g. ‘space’).
 
Information must be easy to understand
Tags: Accessibility for those with focus or learning difficulties

Use clear, simple language.
Define complex concepts and unusual words.

