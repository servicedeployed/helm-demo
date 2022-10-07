# Deepstream-Analytics

A Helm Chart for deploying a video analytics demonstration powered by NVIDIA Deepstream. The application must be deployed on providers who support NVIDIA GPU processors. After deployment the inferenced video can be viewed in any modern browser. Please note that the loadbalancer element may be returned as an IP address or domain name depending on the cloud provider.

## Example Deployment Values

Copy and paste these values into the "Custom Values" tab on app deloyment and enable DNS to access the app publicly.

```yaml
ingress:
  annotations:
    kubernetes.io/ingress.class: nginx
  enabled: true
  hostname: SD_APPLICATION_DNS
```

---

<img src="https://storage.googleapis.com/deployment-images/servicedeployed/repo_images/deepstream-video-analytics1.jpg" alt="Deepstream Video Analytics" width="600" class="w-100"/>

v.2.0
