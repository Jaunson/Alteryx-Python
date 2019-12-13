# Alteryx-Python

This repository contains useful python notebooks and tools that are built to be utilized with Alteryx.

### Master List Runner
Much like the CRew List Runner, this list runner runs all of the modules that it finds when supplied a list of 
paths to those modules. This list runner comes with several new key features:

- Parallelism, run workflows concurrently (defaults=2)
- Workflow timeout, kills workflows that are taking too long (default = 40 minutes)
- Email alerts, supply credentials and the list runner will email you if your total run time goes above a threshold
  (default = 2.5 hours)
