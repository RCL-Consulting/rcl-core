![License](https://img.shields.io/github/license/RCL-Consulting/rcl-core)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/RCL-Consulting/rcl-core)
![GitHub last commit](https://img.shields.io/github/last-commit/RCL-Consulting/rcl-core)

rcl-core – Core Engineering Library
===================================

`rcl-core` is the foundational C++20 library for the **RCL Consulting** ecosystem.  
It provides the essential building blocks for engineering and scientific applications, including:

- **Math primitives**: vectors, matrices, transforms
- **Geometry utilities**: points, lines, arcs, mesh helpers
- **Numerical helpers**: tolerances, constants, algorithms
- **Logging and diagnostics**
- **Extensible modular design**: intended to support finite element analysis, meshing, and visualization projects

This library underpins higher-level projects such as:

- [QuadMind](https://github.com/RCL-Consulting/QuadMind) – AI-assisted mesh generation  
- [QMVision](https://github.com/RCL-Consulting/QMVision) – OpenGL-based mesh viewer  
- [Wombat](https://github.com/RCL-Consulting/Wombat) – Web-based assessment platform  

---

## Goals

- **Consistency** – a unified math/geometry foundation across all RCL projects  
- **Modern C++** – designed with C++20 features (modules, concepts, ranges where applicable)  
- **Extensibility** – clean namespaces (`rcl::core`, `rcl::geometry`, etc.) for gradual expansion  
- **Open source** – built to be shared, reused, and extended by the community  

---

## Status

🚧 **Work in Progress** – APIs are experimental and subject to change as we build out FEA, meshing, and visualization capabilities.  

Initial components:  
- `vec2`, `vec3`, `mat3`, `mat4`  
- `point` alias for clarity in geometry  
- PSLG (Planar Straight Line Graph) segments and arcs  
- Early OpenGL bindings for visualization demos  

---

## License

This project is licensed under the [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html).  

---

## Attribution

Some components and design ideas reference prior academic and open-source work in geometry and meshing, adapted to modern C++ idioms.  
No external code is copied; attribution is provided where applicable.
