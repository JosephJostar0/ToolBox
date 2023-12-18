# conda

### conda create
> conda create --name [env_name] python=[version]

Create an environment with a specific Python version.

### conda activate & deactivate
> conda activate [env_name]

Activate an environment.

> conda deactivate

Deactivate the current environment.

### conda install & update
> conda install [package_name]=[version]

Install a specific version of a package.

> conda install --file [requirements.txt]

Install all dependencies from a requirements.txt file.

> conda update [package_name] / --all

Update a specific package / all installed packages.

> conda install -c conda-forge [package_name]=[version]

Install a specific version of a package from conda-forge.

### conda info & list
> conda info --envs

View all created environments.

> conda list

List all packages installed in the current enviroment.

### conda search
> conda search package_name

Search for a specific package in the Conda repository.

### conda remove
> conda remove [package_name]

Remove a specific package.

> conda env remove --name [env_name]

Remove a specific environment.
