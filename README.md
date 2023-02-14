# CloudRun-jobs
Deploying CloudRUn jobs using Goblet Serverless Framework

## pip install goblet

### You can test your jobs locally by using the goblet cli

### goblet job run Function_Name-Job_Name Task_id
```goblet job run example-job-test 1```

### Deploying your Cloud Run Job
```goblet deploy -p Project -l Region```