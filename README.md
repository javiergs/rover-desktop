# Universal Robots Desktop

**A visual desktop application for exploring Universal Robots e-Series robots and simulators.**

Universal Robots Desktop brings robot visualization and interactive controls together in a graphical interface. It is designed for experimentation with Universal Robots and URSim, with a simulator-first approach.

![Universal Robots Desktop interface showing a 3D robot view, joint controls, and tool-position readouts](assets/app-screenshot.png)

## What you can explore

- **3D robot view** — visualize a robot with workspace references and coordinate axes.
- **Joint controls** — interact with six joint sliders and inspect angles in degrees and radians.
- **Tool position** — view Cartesian coordinates and orientation readouts.
- **Jog Canvas** — explore an interface for motion-vector interaction.
- **Spatial Board** — work with a grid-based spatial interaction view.
- **Connection settings** — enter a robot or simulator IP address and communication ports.
- **Preset poses** — access *Initial Pose* and *Drawing Pose* controls.

## Validation

Universal Robots Desktop was validated with a physical Universal Robots robot and with URSim.

## Download

See **[Releases](https://github.com/javiergs/universal-robots-desktop/releases)** for version 1.0.0 installers and supported platforms. Download the installer from the release assets. GitHub’s automatically generated archives contain this public documentation repository.

## Getting started

1. Download the installer for your operating system from the Releases page.
2. Install and launch **Universal Robots Desktop**.
3. For initial experimentation, start a **URSim** simulator. The [URSim setup guide](https://github.com/javiergs/rtde4j-getting-started/blob/main/docs/ursim-setup.md) explains one Docker-based setup.
4. Enter the IP address of the simulator in the application's connection settings.
5. Begin by inspecting the visualization and controls in simulation. Confirm connection and motion behavior before using any physical robot.

The application currently exposes connection settings for Universal Robots interfaces, including ports **30002** and **30004**. Your simulator network configuration may differ.

## Safety

**Use URSim first.** This application is experimental and is **not a safety-rated robot controller**. Its interface does not replace PolyScope, protective stops, emergency-stop equipment, or the safety procedures required for a physical robot. Do not command a physical robot without validating compatibility, performing an appropriate risk assessment, and establishing suitable safeguards.

## Feedback

Have a question, found a problem, or want to suggest an improvement? Use [Issues](https://github.com/javiergs/universal-robots-desktop/issues).

When reporting an issue, include your operating system, application version, whether you used URSim or physical hardware, and steps to reproduce the problem.
