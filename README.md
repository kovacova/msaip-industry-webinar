# MSAIP Industry Webinar


Create a service principal account:
```bash
az ad sp create-for-rbac --name "ml-pipeline-sp" \
  --role contributor \
  --scopes /subscriptions/<YOUR_SUBSCRIPTION_ID> \
  --sdk-auth
```
