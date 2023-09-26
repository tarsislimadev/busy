# Busy

[![GitHub Workflow Status (with event)](https://img.shields.io/github/actions/workflow/status/brtmvdl/busy/docker-pull.yml?label=Docker%20pull&link=https%3A%2F%2Fgithub.com%2Fbrtmvdl%2Fbusy%2Factions%2Fworkflows%2Fdocker-pull.yml)](https://github.com/brtmvdl/busy/blob/main/.github/workflows/docker-push.yml) [![GitHub Workflow Status (with event)](https://img.shields.io/github/actions/workflow/status/brtmvdl/busy/docker-push.yml?label=Docker%20push&link=https%3A%2F%2Fgithub.com%2Fbrtmvdl%2Fbusy%2Factions%2Fworkflows%2Fdocker-push.yml)](https://github.com/brtmvdl/busy/actions/workflows/docker-push.yml) [![GitHub Workflow Status (with event)](https://img.shields.io/github/actions/workflow/status/brtmvdl/busy/github-release.yml?label=GitHub%20release&link=https%3A%2F%2Fgithub.com%2Fbrtmvdl%2Fbusy%2Factions%2Fworkflows%2Fgithub-release.yml)](https://github.com/brtmvdl/busy/actions/workflows/github-release.yml) [![github/license](https://img.shields.io/github/license/brtmvdl/busy)](https://img.shields.io/github/license/brtmvdl/busy)  [![github/stars](https://img.shields.io/github/stars/brtmvdl/busy?style=social)](https://img.shields.io/github/stars/brtmvdl/busy?style=social)

App to manage tasks.

- [ ] Icon

- [ ] Screenshots

## Android APK (development)

```
wget https://github.com/brtmvdl/busy/releases/download/latest/app-debug.apk
```

### Production

```sh
docker run -d -p 80:80 tmvdl/projects:busy
```

### Development

```sh
bash env/pull.sh 

bash env/install.sh 

bash env/up.sh 
```

## License

[MIT](./LICENSE)
