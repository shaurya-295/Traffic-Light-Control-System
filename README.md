<h1>Traffic Light Simulation System:</h1>
<h2>Problem Statement:</h2>
    <h5>This project simulates a traffic light system using Python. The system cycles through three traffic light states: Green, Yellow, and Red, for random durations. The total time for the simulation is generated randomly between 100 and 1000 seconds. The system simulates real-time behavior with pauses (using time.sleep()) between each light change. The simulation adjusts the phases based on the remaining time to ensure that the light cycle completes within the randomly generated time.</h5>
<h2>Features:</h2>
<ol>
    <li>Random Total Time: The total duration of the simulation is randomly selected between 100 and 1000 seconds.</li>
    <li>Traffic Light Phases: Simulates the traffic light states: Green (30 seconds), Yellow (10 seconds), and Red (30 seconds).</li>
   <li> Real-time Simulation: Uses time.sleep() to simulate real-time delays for each traffic light phase.</li>
    <li>Partial Cycles: The system adjusts to fit the remaining time for partial cycles, ensuring that no light phase exceeds the total simulation time.</li>
    </ol>
