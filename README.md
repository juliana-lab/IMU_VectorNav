<img width="187" height="238" alt="IMU_Case" src="https://github.com/user-attachments/assets/bc53544f-729e-418a-8b59-748dc220a1be" />
![Uploading FrontView.PNG…]()

# IMU_VectorNav

LabVIEW tool for collecting VectorNav IMU data using external pulse synchronization.

The program waits for a pulse signal to start IMU data collection and waits for a second pulse to stop. A 20-second buffer is included at the beginning so the user has time to start the robot motion.

The VI uses an efficient two-loop structure: one loop adds incoming IMU data to the array while the other removes/processes data from it.

## Files

- `SynchronizationSaveTestWithTimer.vi` — main LabVIEW VI
- `FrontView.PNG` — front panel image
- `Snippet.png` — code snippet image
- `Video_frontWindow.mp4` — demo video

## Requirements

- LabVIEW
- VectorNav IMU
- External pulse signal
