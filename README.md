# conda-envs

A collection of conda environment spec files.

## Micromamba install

For full documentation see the [official install page](https://mamba.readthedocs.io/en/latest/installation/micromamba-installation.html).

### MacOS

The following steps will get micromamba set up on MacOS:

1. Easiest install is with homebrew.

    ```command
    brew install micromamba
    ```

2. Initialize micromamba shell to hook up with the OS shell,
in this case, we're using the `zsh` shell,
but this can be anything.
We will be storing the env directories within this repository directory
called `.micromamba`,
update the command below to actual path to the `conda-envs` directory.

    ```command
    micromamba shell init --shell zsh --root-prefix=/path/to/conda-envs/.micromamba
    ```
