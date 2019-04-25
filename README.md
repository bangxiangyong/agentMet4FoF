# Multi-Agent System for Metrology for Factory of the Future (Met4FoF) Code
The research presented was supported by European Metrology Programme for Innovation and Research (EMPIR) under the project Metrology for the Factory of the Future (Met4FoF), project number 17IND12.

About
---
 - How can metrological input be incorporated into an agent-based system for addressing uncertainty of machine learning in future manufacturing?
 - Includes agent-based simulation and implementation


Updates
---
 - Implemented Sensor Agent, Aggregator Agent, Predictor Agent, DecisionMaker Agent, Sensor Network Agent
 - Able to handle multiple Sensor Agents & Predictor Agents (each equipped with a different model)
 - Implemented with ZEMA Condition Monitoring of Hydraulic data set as use case
 - Implemented web visualization with user interface



Note
---
 - In the event of agents not terminating cleanly, run ```taskkill /f /im python.exe /t``` in Windows Command Prompt to terminate all background python processes.
 - Condition Monitoring data set for our use case can be obtained from  [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1323611.svg)](https://doi.org/10.5281/zenodo.1323611)
## Screenshot of web visualization
![Web Screenshot](https://github.com/bangxiangyong/agentMet4FoF/blob/master/screenshot_met4fof.png)
