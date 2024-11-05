# helm-repo

## how to build 

1. Create a new helm chart in the repo "helm-repo"
2. If update chache version number Chart.yaml
3Create helm package from terminal (IntelliJ)
   - helm package [DIR]
   - mv package [DIR]
4. Update index.yaml from terminal (IntelliJ)
    - helm repo index [DIR]
5. Commit and Push
6. helm repo update
7. helm search repo

## github pages

- using github actions [pages-build-deployment ]

  - [Repo](https://kad-bloemgx.github.io/helm-repo/)
  - [Repo index.yaml](https://kad-bloemgx.github.io/helm-repo/index.yaml)

## pgadmin


## homeassistant


| key            | Value                        |
|----------------|------------------------------|
| appName        | homeassistant                |
| namespace      | homeassistant                |
| repository     | homeassistant/home-assistant |
| container.port | 8123                         |

