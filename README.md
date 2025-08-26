# Astrology-robot-project
super cool physics robot :P

## Project setup
### Step 1: Create a virtual environment

For this step we will be using anaconda.
If you have anaconda already installed then you can create a virtual environment by opening a terminal or the ananconda prompt and enter the following command.
`conda create -n astro_proj python=3.11`

You can replace `astro_proj` with whatever name you like.
It will ask to download a bunch of stuff, type `Y` and press `Enter`.

### Step 2: Open VScode and clone the repository

Open vscode, you will be greeted to a screen as shown below:
![vscode welcome window](./images/vscode_welcome.png)

Close the `Welcome` page and click on the `Explorer` icon
![Explorer icon](./images/Explorer_icon.png).
This should be located on the left hand side of the screen.

This should open a selection menu as shown below.
![Explorer selected](./images/Explorer_selected.png)

Here, click on `Clone Repository` and this select the clone from github option.
![Clone from github](./images/clone_from_github.png)

If this is the first time you are cloning something from github then you will get a prompt or a browser pop-up asking you to login with your github account.

Once you have successfully logged in with your github account, you should be able to search for this repository with the notation `upir_username/repository_name`. If we were searching for this repository, then it would be `Chonkusauru/Astrology-robot-project`.
It should look something like this:
![search for repo](./images/search_for_repo.png)

Click on or press `Enter` on the repository that you are interested in. It will open up a menu to choose where to donwload the reposity to. Pick a section or folder that you like and confirm.

If you get no errors and everything runs smoothly, then you should have a local copy of the repository on which you can develop on.

### Step 3: Activate your virtual environemnt

Open the terminal in vscode. This can be done with `ctrl+shift+p`
and then type `toggle terminal`. Press `Enter` on the toggle terminal selection.

![toggle terminal](./images/toggle_terminal.png)

The command for activating your virtual environment is:
`conda activate <your_environment>`

For example, if your environment's name is `astro_porj` then your
command would be `conda activate astro_proj`

If successfull, you shouldn't get any errors and the name of the environment would 
be displayed before the username in the terminal like this.
![successfully created conda env](./images/created_conda_env.png)

Don't worry if that doesn't happen as a pop-up will appear on the bottom right corner of vscode which might state that a conda virtual environment was created but doesn't show up on the terminal.

#### Deactivating your virtual environment
If for some reason you would like to deactivate your environment,
simply enter `conda deactivate` in your terminal.