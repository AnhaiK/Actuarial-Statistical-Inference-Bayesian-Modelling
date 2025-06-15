This is for running the IPYNB files in the Code folder



Step 1: Install Conda

Ensure that either Miniconda or Anaconda is installed on your system.

You can verify the installation by running the following command in your terminal:

    conda --version

If the command is not recognized, download and install Miniconda from:
https://docs.conda.io/en/latest/miniconda.html


Step 2: Create the Environment from the YAML File

Place the file named `sem8_env.yaml` in a directory of your choice. Then, open a terminal or command prompt in that directory and execute the following command:

    conda env create -n my_env_name -f sem8_env.yaml

Replace `my_env_name` with the name you would like to assign to the new environment.
If you wish to use the original environment name, you may omit the `-n my_env_name` part.

Doing this will install all the dependencies and packages — with the exact versions — that are required to run the associated code.


Step 3: Activate the Environment

Once the environment has been successfully created, activate it using the following command:

    conda activate my_env_name

Replace `my_env_name` with the environment name you used in the previous step.

