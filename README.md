# UniFi Network 8.2.93 — L7_EKS

Controller UniFi no MicroK8s (`mrzsrv` / `192.168.1.200`).

- UI: https://192.168.1.240:8443
- Inform: http://192.168.1.240:8080/inform
- Imagem: `lscr.io/linuxserver/unifi-network-application:8.2.93`
- Mongo: `mongo:7.0.40` (ClusterIP)
- Path Argo: `k8s/`
- Secret `unifi-mongo-auth` fica só no cluster, não neste repo.

Não usar o path antigo `base/`.
