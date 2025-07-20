This Python-based system simulates an autonomous security robot that patrols designated areas, detects intruders using randomized threat modeling, and executes security protocols. The solution leverages multi-threading for concurrent operations and includes battery management logic.
Feature	Description
Autonomous Patrol	Cycles through user-defined checkpoints with configurable battery consumption
Intruder Detection	Randomized threat detection (30% probability per location) with alert escalation 2
Security Protocols	Audible alarms, team notifications, and incident logging with timestamps
Power Management	Auto-recharging when battery < 30% with real-time monitoring
Multi-threaded	Simultaneous patrolling and system diagnostics via threading
# Clone repository (requires Python 3.6+)
git clone https://github.com/mongi7754/mongi7754.github.io.git
cd robotic-security-surveillance

# No external dependencies needed
python security_robot.py
# Clone repository (requires Python 3.6+)
git clone https://github.com/mongi7754/mongi7754.github.io.git
cd robotic-security-surveillance

# No external dependencies needed
python security_robot.py
robot = SecurityRobot()
robot.start()  # Activates patrol and monitoring threads
=== SECURITY ROBOT ACTIVATED ===

[Patrolling] Moving to Server Room...
[Security Check] Scanning Server Room...
! INTRUDER DETECTED AT SERVER ROOM !
! AUDIBLE ALARM ACTIVATED !
! INCIDENT RECORDED: 2025-07-20 14:35:22 at Server Room !

[System Check] Status: ALERT | Battery: 78% | Incidents: 1
self.patrol_points = ["Lobby", "Data Center", "Research Lab"]

