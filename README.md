# CloudRun-jobs
Deploying CloudRUn jobs using Goblet Serverless Framework

## pip install goblet

# You can test your jobs locally by using the goblet cli

## goblet job run FUNCTION_NAME-JOB_NAME TASK_ID
```goblet job run example-job-test 1```

## Deploying your Cloud Run Job
```goblet deploy -p Project -l Region```