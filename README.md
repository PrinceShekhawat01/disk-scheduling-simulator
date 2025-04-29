A GUI-based Disk Scheduling Simulator built with Python and Tkinter.
It visualizes how disk scheduling algorithms like FCFS, SSTF, SCAN, and C-SCAN handle a series of disk I/O requests.
The simulation includes animated movement of the disk head with arrows for better understanding!

✨ Features
Visualize the movement of disk head across tracks.

Supports four algorithms:

FCFS (First Come First Serve)

SSTF (Shortest Seek Time First)

SCAN (Elevator Algorithm)

C-SCAN (Circular SCAN)

Shows total head movement and order of servicing requests.

Smooth animation with moving arrows.

Easy-to-use GUI.

🛠️ How It Works
Disk Requests (comma separated):
Enter a list of track numbers you want to access (e.g., 82,170,43,140,24).

Initial Head Position:
Enter the starting track number where the head is currently positioned (e.g., 50).

Select Algorithm:
Choose one of the available scheduling algorithms.

Run Simulation:
Click "Run Simulation" to start. The head movement will be animated on a horizontal track, and the total distance moved will be displayed.

📚 Algorithms Explained
FCFS (First Come First Serve):

Serve the requests in the order they arrive.

SSTF (Shortest Seek Time First):

Serve the request closest to the current head position.

SCAN (Elevator Algorithm):

Move the head in one direction (right), serving requests until reaching the end, then reverse.

C-SCAN (Circular SCAN):

Move the head in one direction only. Upon reaching the end, the head jumps to the beginning without servicing in the return trip.

🧠 Why Disk Requests Are Between 0–199?
This simulator assumes a disk with 200 tracks numbered 0 to 199 (a simplified model of a hard drive).
All input requests and initial head position must be in this range.

📋 How to Run
Make sure you have Python 3.x installed.

Install any missing libraries (only tkinter is used; it usually comes pre-installed).

Run the Python script:

bash
Copy
Edit
python disk_scheduling_simulator.py
🖥️ Screenshot
(You can add a screenshot of your running GUI here!)

📦 Project Structure

File	Description
disk_scheduling_simulator.py	Main Python file containing GUI and simulation code
README.md	Project documentation (this file)
🔥 Future Improvements (optional ideas)
Add more algorithms (LOOK, C-LOOK).

Add speed control for animation.

Add different color arrows for different algorithms.

Save simulation results.

🤝 Contribution
Pull requests are welcome!
For major changes, please open an issue first to discuss what you would like to change.

📜 License
This project is open source under the MIT License.

Would you also like me to give a smaller version (in case you want a "short and clean" README too)? 🚀
(And if you want, I can make a sample LICENSE file for you too!)
