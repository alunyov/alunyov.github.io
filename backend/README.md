# Installation

See https://cloud.google.com/sdk/cloudplatform#appengine

# Development

```sh
dev_appserver.py backend/app.yaml
```

# Deployment
```sh
appcfg.py -A chromatic-yeti-496 update backend/app.yaml
```