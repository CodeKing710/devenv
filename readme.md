# devenv (1.0)

Simply run `devenv` in the terminal of your choice and watch as your optimal developing environment is built right before your eyes! This is a per-user setup and does not affect the system components. Optional tools can be installed as well!

**Includes**:
- Bash Script Manager (bsm)
- CLI App Generator (clapp)
- Virtual Environment Manager (vem)
- Path Manager (chpath)

**Sets up**:
- A repos folder at ~/repos
  - Respective optional includes get added here
- A bin folder for yourself at ~/bin
  - Adds `kjob`, kills process by name, less overhead than complicated `ps | kill` commands
  - Adds `cal`, a terminal calculator that can evaluate almost any numeric expression
  - Adds `yn`, a yes/no wrapper that runs specified code for each condition
  - Adds `smart-rm`, replaces traditional `rm` by interpreting the path(s) passed and removes respective to the type
  - Adds `smart-cp`, replaces traditional `cp` by interpreting the path(s) passed and copies respective to the suffix
- Your .bashrc file to parse files in a directory called '.d', resides at ~/.d
  - Puts a useful aliases file into '.d'
  - Puts a useful prompt file into '.d' (colored prompt)
  - Puts a useful functions file into '.d' (adds better 'read' functionality)
