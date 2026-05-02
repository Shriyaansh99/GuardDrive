# GuardDrive
GuardDrive is a real-time driver safety monitoring Progressive Web App (PWA) 
built as a college project. It uses MediaPipe Face Mesh running entirely in 
the browser to detect driver drowsiness and fatigue without any backend server.

The app calculates Eye Aspect Ratio (EAR) to detect eye closure and Mouth 
Aspect Ratio (MAR) to detect yawning — the same algorithms used in academic 
drowsiness detection research (Soukupová & Čech, 2016). If the driver's eyes 
stay closed for more than 10 seconds, an alarm fires and the emergency contact 
is called automatically via Twilio API.

Features include live camera feed with facial landmark overlay, real-time EAR 
and MAR graphs, GPS speed tracking with custom speed limit alerts, full alert 
history logs, driver profile with Aadhaar and car details, and a settings panel 
to tune all detection thresholds live. The app installs on any Android or iOS 
device directly from the browser with no app store required.

Tech Stack — MediaPipe Face Mesh JS, Web Audio API, Geolocation API, 
Twilio REST API, Service Worker (offline PWA), localStorage, Chart.js, 
Vanilla JavaScript, HTML5, CSS3.
