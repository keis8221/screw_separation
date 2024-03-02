# screw_separation
app for creating screw detector

# Documentation
<details>
  <summary>preparation</summary>
  Before running the detection, please install the following and make it executable.

  - python(I ran it on 3.9.18)
  - pip
  - conda
</details>

<details>
  <summary>When using conda</summary>
  The following assumes that conda is installed.
  
  ```
  # conda create virtual environment
  conda create -n screw_separation python=${version}

  # activate
  conda activate screw_separation

  # deactivate
  conda deactivate screw_separation
  ```
</details>

<details>
  <summary>Install</summary>
  
  ```
  cd yolov5
  pip install -r requirements.txt
  ```
</details>

<details>
  <summary>Inference with detect.py</summary>
  If you want to use the web camera, do the following with it attached.
  
  ```
  python detect.py --weights runs/train/exp3/weights/last.pt --source 0
  ```
</details>
