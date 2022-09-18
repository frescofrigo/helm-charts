# FrescoFrigo Hel Chart repository
This repo is served as a Chart repository for opensource helm releases

## temporal.io
@see: https://github.com/temporalio/helm-charts

Generate the chart bundle:
```shell
git clone git@github.com:temporalio/helm-charts.git
cd helm-charts && helm dependencies update
cd .. &&  helm package helm-charts
```

# Update the index
helm repo index --url https://frescofrigo.github.io/helm-charts .