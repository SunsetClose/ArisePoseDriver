# Arise Pose Driver

**Arise Pose Driver** is a free Maya Python utility designed for artists and riggers working with Arise-based character rigs.

It helps create and update pose-reader driven corrective shape setups for arms, legs, fingers, and neck areas. The tool provides a clean Qt interface, Arise naming presets, left/right mirror support, BlendShape target creation, target transfer tools, and quick UpdatePose workflows for adjusting corrective shapes after posing FK controls.

This script is intended to speed up the corrective shape setup process for Arise rigs, especially when building drive-ball / pose-reader based deformation fixes.

---

## Features

- Maya 2023–2027 support
- Clean modern Qt UI
- Theme switching support
- Arise arm and leg pose-reader drive creation
- Finger corrective driver setup
- Neck pose-reader driver setup
- BlendShape creation and target transfer tools
- UpdatePose workflow for body, finger, and neck correctives
- Left-to-right mirror support for pose updates
- Arise naming presets for faster setup
- Single-instance UI behavior to avoid duplicate windows

---

## Download

- Gumroad: https://996298055622.gumroad.com/l/ArisePoseDriver
- GitHub Release: https://github.com/SunsetClose/ArisePoseDriver/releases/tag/v2.0.0

---

## Installation

1. Download `ArisePoseDriver.py`.
2. Copy it to your Maya scripts folder or any custom Python script path.
3. In Maya, run the following Python command:

```python
import importlib
import ArisePoseDriver as m
importlib.reload(m)
m.show_ui()
