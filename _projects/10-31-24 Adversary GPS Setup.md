# Development of Indoor GPS System for Drone Localization

During my time in the Aerospace Adversary lab under Dr. Gregory Falco, I worked on developing an indoor GPS system alongside a team member to accurately determine the position of a drone. Below is a summary of the project and my contributions:

## System Overview
- The Marvelmind GPS system was employed to locate the drone relative to a semi-arbitrary "origin."
- Together, we developed a Python script to query the position of the drone.

## Contributions
1. **Setup and Configuration**:
   - Flashed the GPS devices with updated software to ensure proper functionality.
   - Followed Marvelmind's instructions to set up the beacons accurately, ensuring a clear line of sight between GPS units.

2. **Position Querying**:
   - Initially attempted to use ROS 2 to query the drone's position but pivoted to using Python for simplicity and efficiency.

3. **Algorithm Development**:
   - **Position Filtering Algorithm**: Designed an algorithm to discard queried positions that failed to meet a minimum tolerance of 70% accuracy, as measured by an internal quality indicator.
   - **Position Averaging Algorithm**: Developed an algorithm to average an arbitrary number of position values to improve the smoothness and reliability of the positions.

4. **Testing and Graphing**:
   - Created a graphing protocol to test and analyze the drone's position data.

5. **Documentation**:
   - Updated the system setup directions to ensure the process could be replicated successfully in the future.

## Visual Representation
Below is a submap of the GPS system used:

![Submap of the GPS](https://github.com/user-attachments/assets/0067cc3e-60d7-4406-94e7-b9b1930a3b9a)

![Position Querying Graph](https://github.com/user-attachments/assets/866a0878-7e57-4d7a-92d8-bd94cbaacf0b)

[Peer-reviewed cybersecurity and AI algorithm paper](https://scholarspace.manoa.hawaii.edu/items/)



