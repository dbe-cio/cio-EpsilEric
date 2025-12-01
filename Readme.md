# CIO Programming Test

The goal of this exercise is to understand your approach to solving a task. A perfect result is not required. What matters most is your methodology, clarity, and reproducibility.

## Task
Your task is to count the number of ricecorn in the image `figs/rice.png` and to colour each ricecorn with a unique colour. Then save the colourised result and document how to run your code.

![rice.png](figs/rice.png)

# Solution

Proposed solution from Eric Freiermuth, given the image characteristics, I chose to go with OpenCV and classical computer vision algorithms to preprocess the image and then isolate the individual clusters corresponding to rice grains. A more detailed explanation of the different steps can be found at the end of this `Readme.md`.

## Setup and Run

Open a terminal and run the following commands:

```bash
# Navigate to your project folder
cd /path/to/your/project

# Create a conda environment in the folder and install Python + packages
conda create --prefix ./my_env python=3.12 numpy matplotlib opencv -y

# Activate the environment
conda activate ./my_env

# Run the Rice Counter script
python Rice_Counter_OpenCV.py
```

### Notes:
- Replace `/path/to/your/project` with the actual path where your script is located.  
- After running the script, you can deactivate the environment with:

```bash
conda deactivate
```

# Rice Detection Report
<!-- RICE-REPORT-START -->
**Timestamp:** 2025-12-01 14:57:13  
**Rice Count:** 101  
**Detection Report:** All rice grains appear to be detected.  

![Labeled Rice Grains](figs/rice_coloured.png)
<!-- RICE-REPORT-END -->

# Method Description

