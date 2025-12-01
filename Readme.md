# CIO Programming Test

The goal of this exercise is to understand your approach to solving a task. A perfect result is not required. What matters most is your methodology, clarity, and reproducibility.

## Task
Your task is to count the number of ricecorn in the image `figs/rice.png` and to colour each ricecorn with a unique colour. Then save the colourised result and document how to run your code.

![rice.png](figs/rice.png)

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

### Step 3: Documentation
Add a description in the `Readme.md` that explains how to run your code. Please include:
- All steps needed to set up and run your solution.
- Instructions to create and activate any Conda environment if required.
- Instructions for installing all dependencies.
- Clear steps to execute the script or program so that we can reproduce your result without issues.

Assume the reviewer is familiar with:
- Terminal and command line
- Conda, Miniconda, or Micromamba
- Creating and activating Conda environments


### Step 4: Push your code
- Push all your code, documentation, and results to your own GitHub repository.
- Send us the link to your repository when you are done.



**Remarks:** 
- Any programming language is allowed (Python preferred).
- Even if you do not manage to count all ricecorn, this is acceptable.
- The most important part is your approach, structure, and clarity.
- Make sure your instructions allow us to run your code without problems.


# Rice Detection Report
<!-- RICE-REPORT-START -->
**Timestamp:** 2025-12-01 15:15:42  
**Rice Count:** 101  
**Detection Report:** All rice grains appear to be detected.  

![Labeled Rice Grains](figs/rice_coloured.png)
<!-- RICE-REPORT-END -->
