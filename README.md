# lcls-plc-template-twincat-project

This repository contains the standard files for starting a TwinCAT3 project and
can be used as a template. 

For more documentation on integrating TwinCAT3 and git, please see our confluence page:
https://confluence.slac.stanford.edu/display/PCDS/TwinCAT+3+Git+Setup+and+Best+Practices

For all of our TwinCAT standards and style recommendations, please see this confluence page:
https://confluence.slac.stanford.edu/display/PCDS/ECS+TwinCAT+Standards+and+Style+Guide

## When starting a new project

 - [ ] Name your repository appropriately (see below)
 - [ ] Customize this ``README.md`` to match your own project.
 - [ ] Create an Environment on GitHub called ``gh-pages`` for documentation deployment. 

Settings -> Environments -> New Environment -> name it "gh-pages" -> "Configure environment" -> "Save protection rules".

### Naming

* Libraries should be named: ``lcls-twincat-(function)``. Examples: ``lcls-twincat-general``, ``lcls-twincat-motion``
* PLC projects should be named: ``lcls-plc-(area)-(function)``. Examples: ``lcls-plc-kfe-motion``, ``lcls-plc-las-bts``
* Development or testing-focused PLC projects should be named: ``lcls-plc-test-(area)-(function)`` or ``lcls-plc-test-(name)``. Examples: ``lcls-plc-test-arbiter``, acceptance testing: ``lcls-plc-test-sat-m1l1``, ``lcls-plc-test-pmps``
* Template PLC projects should be named: ``lcls-plc-template-(name)``.
* Example PLC projects should be named: ``lcls-plc-example-(name)``.
