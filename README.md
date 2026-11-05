<div align="center">

# Devansh Mishra

### Robotics Software | Simulation | Controls | Integration | Verification

I build reproducible robotics systems that connect models, planning and control
software, simulation, operator workflows, and engineering evidence.

**C++ | Python | ROS 2 | Gazebo | MoveIt 2 | Nav2 | PyBullet | CUDA | Docker**

[GitHub](https://github.com/Devansh-Mishra-30) ·
[LinkedIn](https://linkedin.com/in/dvm)

</div>

## Featured robotics and simulation work

### [ROS 2 AMR Platform](https://github.com/Devansh-Mishra-30/ros2-amr-platform)

Browser-operated autonomous mobile robot platform for ROS 2 Jazzy and Gazebo
Harmonic. It integrates differential-drive control, SLAM Toolbox mapping, map
management, AMCL localization, Nav2 goal execution, command arbitration, and
managed process lifecycles.

- **Engineering focus:** autonomy integration, ROS 2 interfaces, lifecycle
  ownership, safe command routing, and end-to-end verification.
- **Published evidence:** tagged `v0.1.0` baseline with 357 automated tests,
  native and Docker validation, launch regression, dashboard integration, and
  launcher lifecycle tests.
- **Stack:** C++17, Python, ROS 2 Jazzy, Gazebo Harmonic, `ros2_control`, Nav2,
  SLAM Toolbox, AMCL, rosbridge, Docker, GitHub Actions.

### [Franka Writing Studio](https://github.com/Devansh-Mishra-30/franka-writing-studio)

Physics-based digital twin for a 7-DoF Franka manipulator that converts SVG
geometry into validated minimum-jerk writing trajectories and executes them in
PyBullet with differential inverse kinematics and hybrid Cartesian
position/normal-force control.

- **Engineering focus:** manipulator kinematics and dynamics, trajectory
  generation, force control, workcell validation, and experiment provenance.
- **Published evidence:** `v1.0.0`, 129-test release gate, 0.0848 mm WRITE XY
  RMSE, and 100% WRITE contact in the documented deterministic simulation
  experiment. These are simulation results, not physical-robot accuracy claims.
- **Stack:** Python, PyBullet, Pinocchio, MATLAB, PySide6, Docker, pytest.

### [Parallel Particle Dynamics Lab](https://github.com/Devansh-Mishra-30/cuda-particle-simulation)

Educational 2D particle-dynamics workbench for studying numerical integration,
collision response, dense contacts, and parallel computing across sequential
C++, OpenMP, and CUDA implementations.

- **Engineering focus:** numerical methods, analytical verification,
  thread-safe parallel solvers, GPU kernels, experiment automation, and
  scientific visualization.
- **Verified v2 release-candidate evidence:** 10/10 CUDA-enabled CTest suites,
  46/46 OpenMP checks across 1-16 threads, and 4/4 documented cross-backend
  scenarios on the recorded environment.
- **Benchmark provenance:** the historical v1 `25.72x` figure is not presented
  as a current-v2 result; controlled v2 performance publication is pending.
- **Stack:** C++17, CUDA, OpenMP, CMake, Dear ImGui, ImPlot, GoogleTest.

### [ROS 2 ArduinoBot Manipulator](https://github.com/Devansh-Mishra-30/github_arduinobot_ws)

Simulation-to-hardware manipulator workspace using a shared URDF/Xacro model,
Gazebo, MoveIt 2, trajectory controllers, a custom `ros2_control` serial hardware
interface, and Arduino servo firmware.

- **Engineering focus:** robot description, motion-planning integration,
  controller configuration, serial protocol design, firmware, and hardware
  bringup.
- **Repository scope:** 10 ROS 2 packages; three actuated arm joints, a mirrored
  gripper model, and four-servo Arduino firmware at 115200 baud.
- **Evidence boundary:** the implementation is documented without fabricated
  tracking or repeatability metrics; a new clean simulation and hardware
  validation pass is the next milestone.
- **Stack:** C++, Python, ROS 2, MoveIt 2, Gazebo, `ros2_control`, Arduino.

## Engineering strengths

| Area | Experience |
| --- | --- |
| Robotics software | ROS 2 nodes, actions, services, launch systems, lifecycle and process ownership |
| Autonomy and planning | Nav2, SLAM, AMCL, MoveIt 2, task orchestration, cancellation and fault handling |
| Modeling and controls | Kinematics, rigid-body dynamics, trajectory generation, differential IK, force/admittance control |
| Simulation and integration | Gazebo, PyBullet, robot descriptions, controller interfaces, serial hardware integration |
| Verification | Unit/integration/E2E tests, analytical and cross-software checks, Docker, CI, evidence-backed release gates |
| Performance computing | Modern C++, CUDA, OpenMP, profiling, numerical experiments |

## Current engineering direction

- Building dependable ROS 2 systems for autonomous mobile robots and
  manipulators.
- Strengthening controls, planning, simulation-to-hardware integration, and
  verification workflows.
- Extending industrial integration skills across PLC/HMI interfaces, command
  handshakes, fault handling, and reproducible acceptance testing.

**M.S. Mechanical Engineering - Modeling & Simulation**, University of
Wisconsin-Madison
