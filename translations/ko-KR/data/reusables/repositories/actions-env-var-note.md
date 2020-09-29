When more than one environment variable is defined with the same name, {{ site.data.variables.product.prodname_dotcom }} uses the most specific environment variable. For example, an environment variable defined in a step will override job and workflow variables with the same name, while the step executes. A variable defined for a job will override a workflow variable with the same name, while the job executes.