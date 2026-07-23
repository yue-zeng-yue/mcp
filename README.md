# ARM64 SIF build workspace

This repository is used to build a native ARM64 Apptainer sandbox for the Polar/SWE-Gym smoke instance `getmoto__moto-7365`.

The workflow builds from the public Moto source commit `7f6c9cb1deafb280fe7fcc7551c38e397f11a706`, validates the task test before and after the gold patch, validates the Apptainer instance lifecycle, and publishes the `.sif` file with a SHA-256 checksum.
