QUASIMODO ENGINE

QUASIMODO is an experimental real-time rendering engine platform focused on modern GPU ray tracing workflows, deterministic performance behavior, and classic mod-driven engine architecture.
The project originates as a research-oriented fork of Quake II RTX and is developed by Cynic Games, an independent studio exploring graphics engineering, renderer design, and next-generation engine technologies.
QUASIMODO aims to evolve beyond a simple engine fork into a lightweight rendering platform where developers can fully understand runtime behavior, experiment with modern rendering techniques, and build gameplay systems as dynamically loaded modules.
Engine Direction
QUASIMODO follows a renderer-centric philosophy.
Instead of large editor-driven workflows and heavy abstraction layers, the engine prioritizes:

small and understandable runtime architecture
deterministic frame scheduling and GPU workload behavior
deep rendering experimentation
modular gameplay integration
minimal unnecessary subsystems
The goal is to enable developers to keep the entire engine mental model in view while working on advanced real-time graphics problems.


Rendering Focus
Current development focuses on modern real-time rendering research including:

hardware-accelerated path tracing
hybrid rasterization + ray tracing pipelines
temporal reconstruction and stability experimentation
latency-aware frame submission strategies
dynamic resolution and upscaling workflows
Vendor acceleration technologies such as DLSS and Reflex are being explored through optional middleware integration layers. These features are not required for engine functionality and are treated as external runtime capabilities.
Fallback rendering paths and open upscaling solutions remain supported to maintain experimentation flexibility.


Mod-Driven Game Architecture
QUASIMODO adopts a classic engine platform model inspired by late-generation Quake-style designs.

Engine runtime operates as a standalone executable
Gameplay logic is delivered as dynamically loaded game modules
Assets and total conversions can evolve independently of engine development
This structure encourages:
rapid gameplay prototyping
renderer research projects
experimental game designs
community mod ecosystems


Origins
QUASIMODO builds upon the technical foundations of Quake II RTX, itself derived from:

Q2VKPT real-time path tracing research
Q2PRO modernized Quake II engine architecture
Many renderer subsystems, console behaviors, and configuration systems therefore retain compatibility with legacy Quake-derived workflows.


License
The QUASIMODO engine runtime is distributed under the GNU General Public License v2.
Developers are free to study, modify, and redistribute the engine source code under the same terms.
Original Quake II game data files remain copyrighted and cannot be redistributed.
Current Development Focus

renderer profiling and correctness improvements
gameplay module API stabilization
middleware abstraction layer experimentation
asset and map pipeline design
technical demonstration projects


Project Status
Early experimental development.
The current priority is validating architectural direction and rendering performance characteristics before expanding into production-ready tooling and workflows.
