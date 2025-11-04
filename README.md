# meen-612-ur5e-sim-project
A copy of the code repository for the MEEN 408/612 class project involving UR5e robots simulated in Drake.

---

**NOTE:**
This is a personal copy of an earlier version of the project before I handed it off to Gray Thomas and Jonas Land to finish setting up the realtime portions for the class. 

The final version of the project is public [here.](https://github.com/tamu-edu/meen-612-ur5e-sim-project)

---

**Set up Python Virtual Environment**

After cloning this repo, run the following on the command line. This will create a virtual environment in the env/ folder. You may choose to call it something else, but you will need to update the `.gitignore`

```sh
python3 -m venv env

# then source the environment to activate it (for linux machines)

source env/bin/activate

# (env) will then appear at the start of the terminal line. This can also be set happen automatically when opening vscode by selecting the activated file as the default interpreter in the command pallet `ctrl+p`

# Finally, install drake and matplotlib to the venv

pip install drake
```

you are now ready to run the examples in this repo!



### Running the Sim

`python3 run_simulator.py`


### Task Description

Edit the `CalcControlEffort` function within the `FeedbackController` class in `my_controller.py` to implement your impedance controller
