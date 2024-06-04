# ENVIRONMENT SETUP STEPS

## Prerequisite Dependencies

This Demo Uses Jupyter Notebooks. The following dependencies need to be installed.

### Anaconda

Linux Installation Steps: https://docs.anaconda.com/free/anaconda/install/linux/

### VSCode (Optional)

This can be used to view/run the Jupyter notebooks. Alternatively its also available in the browser.

## Setup Project Folder

- Create project folder e.g. machinelearning-llm-demo
- Create a virtual environmment.
  ```
  python -m venv mlenv
  ```
- Active the environment
  ```
  chmod +x ./mlenv/bin/activate
  ./mlenv/bin/activate
  ```
- Install dependencues
  ```
  pip3 install matplotlib numpy pylzma ipykernel jupyter
  pip3 install torch torchvision torchaudio
  ```
- Check python version
  ```
  python --version
  ```
- Start jupyter notebook
  ```
  jupyter notebook
  ```
