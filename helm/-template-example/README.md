## Adding a new microservice

Create `new-service/`, edit `Chart.yaml` (name) and
`values.yaml` (image, env, ingress host, etc.). `templates/all.yaml` needs
**zero changes** — it's identical across every service.