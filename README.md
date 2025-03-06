# VR-Interaction
Template# Gesture-based VR Interaction Demo
A VR project built in Unity demonstrating gesture-based interactions using hand tracking.
## Setup Instructions
1. Clone this repository.
2. Open in Unity (2022.3.45 LTS recommended).
3. Install Meta XR SDK via Package Manager (`com.meta.xr.sdk.core`).
4. Ensure XR Plugin Management is enabled for Oculus/OpenXR.
5. Load `DemoExample.unity` and press Play.
## How to Run
- Use a VR headset with hand tracking (e.g., Meta Quest2).
- Pinch near the cube to grab and move it.
- Swipe near the sphere to rotate it left or right.
## Features
- Custom gesture system (Grab and Swipe).
- Visual feedback (glow on interaction).
- Onboarding tutorial for new users.
## Challenges & Solutions
- **Gesture Detection**: Used velocity and pinch strength for reliable detection.
