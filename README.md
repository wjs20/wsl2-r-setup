# wsl2-r-setup
Environment and instructions for setting up your wsl2 to run R

Create a new conda/mamba env using this environment.yml
```
mamba env install -f environment.yml
```
To use R when the env is not activated, use aliases.
E.g. in you .zshrc
```
alias runR="$HOME/mambaforge/envs/r_env/bin/Rscript"
alias runRscript="$HOME/mambaforge/envs/r_env/bin/R"
```

To plot interactively follow the instructions [here](https://nx10.github.io/httpgd/articles/a01_how-to-get-started.html)
