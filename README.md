# lcls-twincat-template-project

This repository contains the standard files for starting a TwinCAT3 project and
can be used as a template. 

For more documentation on integrating TwinCAT3 and git, please see our confluence page:
https://confluence.slac.stanford.edu/display/PCDS/TwinCAT+3+Git+Setup+and+Best+Practices

## When starting a new project

 - [ ] Customize this Readme.md to match your own project.
 - [ ] (optional) Configure [doctr](https://pypi.org/project/doctr/) and add the deploy key to the .travis.yml file for auto-generated documentation. Doctr is a python utility for automatically pushing a gh-pages branch through the travis build process. A repository requires some 1st time configuration using the `doctr` command line tool but once that is complete, the pushing process is fully automated. For instructions on configuring doctr: https://github.com/drdoctr/doctr#run-doctr-configure. The doctr command line tool can be found in the [PCDS conda environment](https://github.com/pcdshub/pcds-envs).
