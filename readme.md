# devenv (2.0)

Simply run `devenv` in the terminal of your choice and watch as your optimal developing environment is built right before your eyes! This is a per-user setup and does not affect the system components. Optional tools can be installed as well!

**Includes**:

- Bash Script Manager (bsm)
- CLI App Generator (clapp)
- Virtual Environment Manager (vem)
- Path Manager (chpath)
- Semantic Versioner (semver)

**Sets up**:

- A repos folder at ~/repos
  - Respective optional includes get added here
- A bin folder for yourself at ~/bin
  - Working on fixing the original tools that came standard in the devenv
- Your .bashrc file to parse files in a directory called '.d', resides at ~/.d
  - Puts a useful aliases file into '~/.d'
  - Puts a useful prompt file into '~/.d' (colored prompt)
  - Puts a useful functions file into '~/.d'
