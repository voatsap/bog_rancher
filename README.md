# Rancher Session for BoG

## Install required tools

Helm

```bash
curl -fsSL https://raw.githubusercontent.com/helm/helm/master/scripts/get-helm-3 | bash -
```

Helm diff plugin

```bash
helm plugin install https://github.com/databus23/helm-diff
```

Helmfile

```bash
wget https://github.com/roboll/helmfile/releases/download/v0.135.0/helmfile_linux_amd64 -O helmfile_linux_amd64
chmod +x helmfile_linux_amd64
sudo mv helmfile_linux_amd64 /usr/local/bin/helmfile
```

Kubectx

```bash
wget https://github.com/ahmetb/kubectx/releases/download/v0.9.3/kubectx_v0.9.3_linux_x86_64.tar.gz && tar -xzvf kubectx_v0.9.3_linux_x86_64.tar.gz -C /usr/local/bin
wget https://github.com/ahmetb/kubectx/releases/download/v0.9.3/kubens_v0.9.3_linux_x86_64.tar.gz  && tar -xzvf kubens_v0.9.3_linux_x86_64.tar.gz -C /usr/local/bin
```

## Calico Network Policies

[Calico Network Policies](https://docs.projectcalico.org/security/tutorials/kubernetes-policy-basic)

## Falco

[Falco Charts](https://github.com/falcosecurity/charts/tree/master/falco)