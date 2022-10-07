# speedtest

Speedtest is a lightweight, simple bandwidth tester implemented in Javascript, using XMLHttpRequest and Web Workers. Upload and download speeds are tested from server to client using standard http requests. It is intended for non-critical testing and does not take the place of network monitoring tools.

## Example Deployment Values

Copy and paste these values into the "Custom Values" tab on app deloyment and enable DNS to access the app publicly.

```yaml
ingress:
  enabled: true
  hostname: SD_APPLICATION_DNS

clusterinfo:
  name: SD_CLUSTER_NAME
  provider: SD_CLUSTER_PROVIDER
  location: SD_CLUSTER_LOCATION
```

---

<img src="https://storage.googleapis.com/deployment-images/servicedeployed/repo_images/speedtest.jpg" alt="speedtest" width="600" class="w-100"/>


v.0.4
