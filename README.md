# On-Xp-replicable-python-hello-world-task
Task in a On-Xp Python Web Development with Django Class

How to ship/build it?
1. If you're in Windows run WSL, type `wsl` in your command line and press enter, or install it first if you don't have it yet.
https://learn.microsoft.com/en-us/windows/wsl/install

2. Then run nix-shell to start an interactive shell based on a Nix expression by typing `nix-shell` in this wsl opened folder, in the Nix-shell the dependencies like PDM is already prepared
https://nixos.org/download/
https://nixos.org/manual/nix/stable/command-ref/nix-shell

3. Run PDM, Python package and dependency manager by writing `pdm <your_command>`.

4. Run PDM command suitable for your build purpose, for example `pdm build` to Build artifacts for distribution, you can run `pdm -h`

Happy Shipping