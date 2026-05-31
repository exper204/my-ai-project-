## Pilkhuwa Drone Pothole Patrol
Final project for the Building AI course
Summary
This project uses AI and drone camera footage to identify and map damaged roads and potholes around Pilkhuwa. The goal is to help local authorities locate and fix road hazards much faster.

Background
Roads frequently get damaged, and finding every pothole manually takes a lot of time and effort. My motivation for this project is to make driving and riding RC cars or regular vehicles safer and smoother. This topic is important because:

Potholes cause damage to vehicles.

Manual inspections are slow and inefficient.

Quick repairs prevent accidents.

How is it used?
A standard toy drone equipped with a 4K UHD camera flies over the neighborhood and records video of the streets. The video is fed into an AI model that scans the footage, detects the potholes, and drops a pin on a digital map. It would be used by local city planners or community members who want to report road damage.

Data sources and AI methods
The data would come from recorded drone video footage of the streets. The AI would use Computer Vision and a Convolutional Neural Network (CNN) to recognize the specific visual patterns of a pothole, similar to how an AI learns to recognize a cat's ear.

Challenges
The project does not physically fix the potholes. Also, small toy drones have short battery lives and cannot fly in bad weather, so data collection would be limited to sunny, clear days.

What next?
The project could grow by connecting the AI to a MySQL database using Python. This database could track the exact GPS coordinates of each pothole and automatically update its status to "Fixed" once a new drone flight confirms the road is smooth.

Acknowledgments
Elements of AI Course for the inspiration.

Open source Convolutional Neural Network tutorials.
