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

OpenAI
  We will be using ChatGPT to assist our use of these programs. From our observations, the cost of usage is incredibly cheap, as running this program from start to   finish costs about one cent per trial.

  Setting up
    To create an account, go to https://platform.openai.com/docs/overview and the portal will be located in the top right of the window.
    In the top left corner, click on your profile picture and in the drop down, go to Your Profile
    On the left-hand side, go to Billing
    To pay, click on Add credit balance, input your credit card information, and then hit Continue.
    Go back to Your Profile and then go to the User API Keys tab. 
    Click on Create new secret key, give it a name, and then BEFORE CLOSING, copy and paste the key in the following syntax: openai.api_key = "(insert key here)"       and replace the lines of "#insert API key in this line" with the syntax.
  Running
    Copy and paste the text you would like to analyze into the training_text.txt folder.
    Run the programs in the following order: Evaluate->Word2Vec->Finalize. 
    When running a new file, select the top cell and keep clicking the single arrow pointing to the right to run. The next cell will be autoselected.
    Cells which involve usage of openai will take a few seconds to execute. If you are curious of the parts of context involved within the calculation, you can         access the following files out of curiosity: evaluate.txt, feminine.txt, masculine.txt, neutral.txt, verify.txt.
    The output from the final cell of Finalize will tell you if the text is more associable by men or women.
