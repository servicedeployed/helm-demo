# Jitsi Meet - Secure, Simple and Scalable Video Conferences

Jitsi Meet is an open-source (Apache) WebRTC JavaScript application that uses [Jitsi Videobridge](https://jitsi.org/videobridge) to provide high quality, [secure](https://jitsi.org/security) and scalable video conferences. The Jitsi Meet client runs in your browser, without installing anything else on your computer. Jitsi Meet allows very efficient collaboration. Users can stream their desktop or only certain windows. 

## Example Deployment Values

Copy and paste these values into the "Custom Values" tab on app deloyment and enable DNS to access the app publicly.

```yaml
web:
  ingress:
    enabled: true
    hostname: SD_APPLICATION_DNS
```

---

<img src="https://storage.googleapis.com/deployment-images/servicedeployed/repo_images/jitsi-video-room1.jpg" alt="Jitsi Video" width="600" class="w-100"/> 

Version 0.0.3