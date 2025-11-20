# DTCell – URDF to AAS Generator

This project converts **URDF robot models** and related YAML/JSON configuration files into **AAS (Asset Administration Shell) Submodels**.  
Supported submodels:

- Structure
- Control
- Kinematics
- Dynamics
- Safety
- Visualization
- Combined Environment File (AAS import-ready)

Supports all UR robots (UR3–UR20).

---

## 🚀 Features

- Parse URDF links/joints, inertia, mass, origins  
- Extract visual/collision mesh info  
- Read controller, joint limit, dynamics, and kinematic configs  
- Auto-fix AAS structures (SMC.value always list)  
- Convert mesh paths to `package://ur_description/...`  
- Batch generation for all UR series

---

## 🛠 Usage

```bash
python generator.py
