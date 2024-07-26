Installing Python
-Windows: https://www.python.org/downloads/
-Linux/UNIX: https://www.python.org/downloads/source/
-Mac: https://www.python.org/downloads/macos/
-Other: https://www.python.org/download/other/

Installing Jupyter Notebook
  Create a file directory and open any command line terminal (right click and select either command prompt, windows powershell, anaconda prompt, etc), then execute: pip install jupyter
  To run, execute: jupyter notebook
  It is recommended you save a shortcut for that specific directory as that workspace can only be accessed through running jupyter notebook there.

For a beginner's guide to Jupyter Notebook: https://www.youtube.com/watch?v=5pf0_bpNbkw

Installing plug-ins for program
  Execute:
  pip install openai
  python -m venv openai_venv
  python -m ipykernel install --user --name openai_kernel
  pip install numpy
  python -m venv numpy_venv
  python -m ipykernel install --user --name numpy_kernel
  pip install pandas
  python -m venv pandas_venv
  python -m ipykernel install --user --name pandas_kernel
  pip install tqdm
  python -m venv rqdm_venv
  python -m ipykernel install --user --name tqdm_kernel
  pip install scipy
  python -m venv scipy_venv
  python -m ipykernel install --user --name scipy_kernel
  pip install matplot
  python -m venv matplot_venv
  python -m ipykernel install --user --name matplot_kernel
