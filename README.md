Vanilla RNN coded using numPy and trained for MNIST handwritten digit classification, achieved ~94% accuracy 

![](https://github.com/suprasauce/RNN_MEDIUM/blob/main/plot.png)

## Running the project
### Windows

1. Install [python](https://www.python.org/) for windows if you don't have it (preferably python 3.8). Activate a virtual environment in Powershell/CMD by either installing virtualenv and following its instructions to make a virtual environment, or by using the venv package which comes with python by default.
   
   Go to the directory where you have cloned the project and run
   ```
   python -m venv env
   ```
   This will make a folder named env.

3. Then type </br>

   (Powershell)
   ```
   path_where_env_is_stored\env\Scripts\Activate.ps1
   ```
   (CMD)
   ```
   path_where_env_is_stored\env\Scripts\activate
   ```

4. To install the dependencies, run
   ```
   pip install numpy tqdm pickle5 matplotlib notebook
   ```

4. To run the notebook, run
   ```
   jupyter notebook
   ```
