# NYTC2026
National Youth Tech Championship 2026

This repository contains the documentation of code and setup tutorials used for the **National Youth Tech Championship 2026** robotics challenge.

The project focuses on using **Python and computer vision** to enable a robot to perform **image recognition tasks**.

---

## Repository Structure

```
NYTC2026/
│
├── code/
│   ├── python_scripts
│   └── jupyter_notebooks
│
└── requirements.txt
```

### `code/`

This folder contains all the **Python scripts and Jupyter notebooks** used for the robot's image recognition system.

The code includes:

* Image capture and processing
* Model testing and debugging notebooks
* Supporting scripts used during development

### `material/`

This folder contains setup guides to help users prepare their development environment.

Current material include:

* **`requirements.txt`**
  A shortcut to install all the modules.
  
  ```bash
  pip install -r requirements.txt
  ```

## Notes

Some scripts may require a connected UGOT robot to function properly.

The links to the relevant documentation of some packages that will be used are below:
- [UGOT](https://docs.ubtrobot.com/ugot/#/en-us/extension/python_sdk/version)
- [face_recognition](https://github.com/ageitgey/face_recognition)
- [opencv-python](https://docs.opencv.org/4.x/d6/d00/tutorial_py_root.html)
- [ultralytics](https://docs.ultralytics.com/reference/engine/results/#ultralytics.engine.results.Boxes)
