# Instructions for software usage on Midway2 and Midway3 Clusters
These guidelines apply both clusters.

**To use WRF**
- Run: ```module load wrf```

**To use CESM**
- Run: ```module load cesm```

## Custom Installation or Case Creation

If you wish to install your own version, customize workflows, or create new cases for either software:

1. Export the Conda envrionment used.
2. Recreate your own Conda envrionment.
3. Build your personal version/cases in this environment.

_Be sure to adjust environment variables and dependencies as needed for your specific requirements._

## CESM - Specific Guidelines

For CESM, example XML configuration sections can be found in:
- ```config_machines.xml```
- ```config_compilers.xml```
- ```config_batch.xml```

Within these files, look for the section named **simple_linux**. It is recommended to base your own CESM cases or machine configurations on this example. Update relevant parameters (such as machine name, compiler, batch configuration, etc.) to reflect your cluster ssetup and project needs.

## Additional Information

- **Directory Setup:** Use your designated scratch or project directories for storing case files.
- **Documentation:** Refer to the official cluster guides for any environment specific setup steps.
- **Troubleshooting:** If you encounter issues with modules or software bulds, consult the cluster's helpdesk or support documentaiton.


