# event_display
Repository for arm64 knative event_display container image

```
export KO_DOCKER_REPO=ghcr.io/derekelewis/event_display
git clone https://github.com/knative/eventing knative-eventing
cd knative-eventing
ko build -B --platform linux/arm64 ./cmd/event_display
```
