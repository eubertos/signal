README for Devin – Signal Node Debugging

Hey Devin,

This project—Signal Node—was built using an AI assistant and an autonomous coder (Windsurf). It’s a Flask-based biosignal dashboard that simulates real-time EEG, heartbeat, and breath data using Python scripts. The frontend is supposed to use a minimal dark theme with animated graphs (Chart.js) and styled pages for each signal route.

🧠 Core Features:
	•	Flask + Flask-SocketIO backend
	•	Routes:
	•	/ → homepage (“Signal Node is LIVE”)
	•	/brain → EEG simulation (line graph)
	•	/heartbeat → heart rate + HRV (pulse + waveform)
	•	/breathe → paced breathing animation
	•	Scripts folder runs simulations for EEG/heart/breath
	•	Chart.js visuals (expected)
	•	CSS theme: #0a0a0f background, electric cyan accents
	•	Session logging into /data/session-YYYY-MM-DD/*.json
	•	/system/startup.sh for Raspberry Pi boot
	•	Designed to be local-first, portable, and modular

🛠️ Problems to Fix:
	•	Site loads but renders blank pages
	•	CSS and/or JS likely not being served correctly
	•	Static/templating errors might be breaking visual output
	•	Code needs sanity check, possibly component refactor

🔧 Goal:

Get it working again as a beautiful, functioning local dashboard with the current features intact. You can clean/streamline as needed—we trust your judgment.

Thanks for jumping in.
