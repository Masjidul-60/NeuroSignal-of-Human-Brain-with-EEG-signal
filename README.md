# NeuroSignal 4D

An interactive face-to-brain signal visualization built with Three.js.

## Run

Keep `NeuroSignal 4D.html`, `professional-lab-researcher.glb`, and `portrait.png` together. Serve the folder over localhost (for example, with VS Code Live Server) and open the local server URL. The 3D libraries load from jsDelivr; the app also needs an internet connection.

The default face is a textured, rotatable 3D bust. The GLB is adapted from MakeHuman CC0 assets and published as CC0 by [Innerscene](https://www.innerscene.com/tools/library/3d-parts/laboratory-researcher-3d-person-healthcare-7a3ceb81). The app uses the head, facial details, and neck, and omits its clothing, ID badge, and safety glasses. If the GLB cannot load, the portrait and procedural head remain as a fallback.

## Explore

- Drag to inspect the head from all sides; zoom in to reveal the skull and spine, then the brain and neural pathways.
- Choose **Speak**, **Hear**, **See**, **Touch**, or **Conversation** to follow a signal path.
- Use **Pause**, **Step**, **Restart**, or the progress slider to control a scenario.
- Switch camera views, toggle anatomy layers, and adjust simulation speed.
- Use the EEG Live Monitor for 12 scrolling simulated 10–20 channels, an FFT spectrum, band-power readouts, channel selection, sensitivity, timescale, speed, pause, reset, collapse, and fullscreen controls. Scenario events and selected motor, sensory, or visual regions modulate corresponding channels.
- Use the Anatomy level slider, +/- controls, or mouse wheel to move through the external head, skull guide, internal guide, brain regions, pathways, and microscopic signal views. Layers are independently toggleable; the skull, brain surface, region nodes, and neuron network are educational illustrations, not precision anatomical assets.
- The bundled Innerscene / MakeHuman bust is loaded as the external head model. Its attribution and CC0 source are shown in the interface. The portrait image remains only a legacy fallback and is not used when the GLB bust loads.
- Enable **Mic live** to let microphone input animate speech-related activity. Microphone access requires browser permission and localhost or HTTPS. Turn it off to release the microphone.
- Keyboard: **Space** toggles play/pause; **Left/Right Arrow** moves between scenario steps.

## Educational note

This is a conceptual visualization. EEG is synthetic and is not patient data. Neural paths, region markers, internal anatomy guides, and latency values are illustrative, not diagnostic or precision scientific measurements. The current bundle does not include a verified high-resolution skull or brain mesh; NIH 3D entries linked in the interface require checking their individual licenses before redistribution.
