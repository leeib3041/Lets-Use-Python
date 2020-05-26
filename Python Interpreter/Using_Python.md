# Using Python

Your results may vary based on what OS and tool you are using. If you are using MacOS(Unix)/Linux/Ubuntu(Windows) terminal, then you should be on par with me. If you are going by other means, your commands may vary but path is the same. Here is what I am working with:

**MacOS Catalina (v10.15.4)** - You should be find with most of the other MacOS flavors/versions
**zsh terminal (v5.7.1)** - bash terminal should be perfectly fine. The difference between the two won't matter at all at this level.
**Miniconda (v4.8.3)** - Anaconda and Miniconda should be exactly the same in the terminal. The only difference will be the Anaconda GUI.

Relevant commands for above:
```
bash --version
zsh --version
conda --version
```

Alright, now lets get coding.

## Activating Conda

This is fairly simple, and conda does provide a command [cheat sheet](conda-cheatsheet.pdf).

1. Let's first confirm conda is installed on your system, type the command `conda --version`. If you get an output of its version, then you can move on to the next step. If not, consult with Anaconda.
![](Images/version.png)
2. Check what environments you currently have. You should only have **base**.
![](Images/list.png)
3. For the sake of practicing, lets create a new environment by typing the command `conda create --name python101`. If you want to create an environment with a specific python version, then use `conda create --name python101 python=3.5`.
![](Images/create.png)
