# wpts-deploy-test

## Cluster deployment

- [Deploy to Azure](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fanamikoye.github.io%2Fwpts-deploy-test%2Fcluster-azuredeploy.json)
- [Combined ARM template](cluster-azuredeploy.json)
- [Cluster-Package.zip](https://github.com/anamikoye/wpts-deploy-test/releases/download/cluster-test-v1/Cluster-Package.zip)
- Package SHA-256: `781D88F2829DAEAB9A7CA9374C564F6161CAEB7E8EBAF6B800EB15C44185B5EA`

The combined template performs both infrastructure phases in one deployment and
blocks domain-member provisioning until the DC and Storage readiness checks pass.
