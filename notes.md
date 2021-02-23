#changes the name of the pipeline

az devops configure --defaults organization=https://dev.azure.com/singh0034/
az devops configure --defaults project=firstpipeline
pipelines update --id 1 --description "rename pipeline" --new-name ss1n9h.pipeline-dotnetcoresexample --output table

