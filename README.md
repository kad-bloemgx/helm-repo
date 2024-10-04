# helm-repo

## how to build 

1. Create a new helm chart in the repo "helm-repo"
2. Create helm package from terminal (IntelliJ)
   - helm package [DIR]
3. Update index.yaml from terminal (IntelliJ)
    - helm repo index [DIR]

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
| service.type   | Nodeport                     |
| service.port   | 30168                        |

