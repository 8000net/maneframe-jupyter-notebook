This is a set of scripts to launch a Jupyter Notebook server on ManeFrame2, and handle all
the port forwarding. All you have to do is run one script.

Setup:
- Fill in `USERNAME` in `setup.sh` and `launch_nb.sh`  
- Run `setup.sh`  
  - This will generate a SSH key pair, copy to ManeFrame2, along with a script to launch the notebook server  

Usage:
- Edit `TIME_LIMIT` in `launch_nb.sh` if you need the compute node to run for more than 2 hours
- Edit `NODETYPE` in `launch_nb.sh` to use a different node type
- Run `launch_nb.sh`  
  - If successful, your default browser should open a tab with the Jupyter Notebook home.


Todo:
- Check that selected port isn't already in use   
- Generalize for any supercomputer running SLURM  

Should be compatible with Linux and OS X
