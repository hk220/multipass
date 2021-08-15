# multipass

multipassに渡すcloud-init.yamlファイル置き場

## How to Use

```bash
# checkout this repository
cd multipass
multipass launch --name primary --cpus 2 --memory 2048M --disk 64G --cloud-init ./cloud-config.yaml 20.04
```
