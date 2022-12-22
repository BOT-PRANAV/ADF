# How it works
The GitHub Action uses pre and post-deployment scripts to prevent the deployment from potential side effects, such as:

Execution of active triggers during the deployment process that could corrupt resources relationships or have pipelines in undesired states.
Availability of unused resources that could bring confusion to data engineers and reduce maintainability.
