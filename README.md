# Cone Detection for Formula Student Driverless Competition

## Introduction

This project is all about bringing a **skidpad test** to life in MATLAB. A skidpad test is normally used to study how a car behaves when cornering — it helps engineers understand grip, stability, and handling.

In our version, we created a **racetrack with boundaries, random cones, and a moving car**. The car isn’t just blindly driving; it actively avoids cones, stays inside the track, and leaves behind a path so you can see its journey in real time. Think of it as a mini driving simulation where math and visualization meet.

---

## What’s Inside

* A **racetrack** that’s smooth and continuous (thanks to spline interpolation).
* **Track boundaries** and a **start/finish line** for reference.
* Randomly scattered **cones** in different colors (red, green, blue).
* A moving **car dot** that:

  * Follows the track,
  * Avoids cones, and
  * Stays within the boundaries.
* A clear **visual output** where you can watch everything unfold in real time.

---

## What You’ll Need

* MATLAB R2023a or later
* Vehicle Dynamics Blockset™ (for skidpad concepts; though our simulation runs with plain MATLAB plotting)

---

## How to Run It

1. Open MATLAB.
2. Load the script file: `skidpad_simulation.m`.
3. Hit **Run (F5)**.
4. Watch the figure window open with:

   * The racetrack and its boundaries,
   * Random cones,
   * And the car navigating the course live.

---

## What You’ll See

* A closed-loop racetrack with smooth curves.
* Randomly placed cones in red, green, and blue.
* A car path that updates step by step as it avoids obstacles.
* A **start/finish line** to mark the lap.

It’s a simple, visual way to understand how cars behave when challenged with obstacles and track limits.

---

## Future Ideas

We designed this as a foundation, but it can easily be expanded:

* Use **Unreal Engine (Simulation 3D Viewer)** for realistic 3D visuals.
* Add more advanced **driver logic** for smoother maneuvers.
* Track and analyze **lap times, speed, and cornering behavior**.
* Push it further into **autonomous driving simulations**.
