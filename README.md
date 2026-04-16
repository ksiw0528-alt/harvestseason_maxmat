# harvestseason_maxmat

Real-time Granular Synthesis for Violin and Electronics
Developed by Sirang Kang

Description
This project is a real-time interactive patch designed for Violin and Max/MSP. It focuses on transforming live acoustic violin input into immersive, ambient granular clouds and evolving textures. The patch is engineered to capture the nuances of live performance and expand the instrument's sonic palette through high-fidelity granular processing.

Technical Requirements
To run this patch, you will need the following software and external libraries:

Software: Max 8.x / Ableton Live 12 Suite (Max for Live)

Required Externals: * karma~

Bogaudio VCF (if utilizing the VCV Rack bridge)

poly~ based granular engines (included in the patch)

How to Use
Installation: Download the .maxpat file and ensure the karma~ external is located in your Max search path.

Audio Setup: * Connect your audio interface and route the Violin input to the patch.

Ensure the sampling rate is set to 48kHz for optimal buffer performance.

Operation: * Toggle the DSP on.

The patch utilizes a #0_sweet_spot buffer system to prevent instance conflicts during live recording.

Use the main "Cloud Density" and "Grain Size" parameters to shape the ambient environment in response to the score.

Performance Notes
The patch is designed to be highly responsive to the performer's dynamics.

Real-time Capture: The granular engine captures the live violin signal into a circular buffer, allowing the performer to layer harmonies over their own playing.

Signal Flow: Integrated with poly~ for dense, overlapping "cloud" effects without CPU spikes.

Contact
For any inquiries regarding the performance or technical setup, please contact:

Name: Sirang Kang

Email: ksiw0528@hanyang.ac.kr
