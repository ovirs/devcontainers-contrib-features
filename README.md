<div align="center">

 # [List of features](https://github.com/devcontainers-contrib/features/tree/main/src) 

👀 Don't see your feature here? 

 ## [🔥Suggest a new feature!🔥](https://github.com/danielbraun89/devcontainer-bug-replication/issues/new?template=suggest-feature.yaml) 

</div>

<div align="center">

![](https://i.imgur.com/VgiY81S.png)

</div>

## devcontainer features

🧰 Feature addons for [@devcontainers] \
💻 Works with [devcontainers] \
☁️ Works with [GitHub Codespaces]


### Usage

![VS Code](https://img.shields.io/static/v1?style=for-the-badge&message=VS+Code&color=007ACC&logo=Visual+Studio+Code&logoColor=FFFFFF&label=)
![Codespaces](https://img.shields.io/static/v1?style=for-the-badge&message=Codespaces&color=181717&logo=GitHub&logoColor=FFFFFF&label=)
![Devcontainers](https://img.shields.io/static/v1?style=for-the-badge&message=Devcontainers&color=2496ED&logo=Docker&logoColor=FFFFFF&label=)

📄 [Complete feature list]

Just add a `.devcontainer/devcontainer.json` file with a `features` key. It's
very similar to `package.json`'s `dependencies` object, just with the addition
of an `options` object.

📚 Make sure to inspect each feature for feature-specific options!

```json
{
  "image": "mcr.microsoft.com/devcontainers/universal",
  "features": {
    "ghcr.io/devcontainers-contrib/features/deno:": {},
    "ghcr.io/devcontainers-contrib/features/neovim": {}
  }
}
```

Then, after adding your devcontainer config file, you can open it in GitHub
Codespaces, or [open it locally using VS Code]. Be warned some features will
compile things from source code and may take a while!

<div align="center">

![](https://i.imgur.com/JMdowst.png)

</div>

## Development

![Devcontainers](https://img.shields.io/static/v1?style=for-the-badge&message=Devcontainers&color=2496ED&logo=Docker&logoColor=FFFFFF&label=)
![JSON](https://img.shields.io/static/v1?style=for-the-badge&message=JSON&color=000000&logo=JSON&logoColor=FFFFFF&label=)
![Bash](https://img.shields.io/static/v1?style=for-the-badge&message=Bash&color=4EAA25&logo=GNU+Bash&logoColor=FFFFFF&label=)


This project uses a devcontainer config to outline the development environment.
We also provide various VS Code customizations for your coding pleasure.

<!-- prettier-ignore-start -->
[🐞open an bug report🐞]: https://github.com/devcontainers-contrib/features/issues/new?template=bug-report.yaml
[@devcontainers]: https://github.com/devcontainers
[complete feature list]: https://github.com/devcontainers-contrib/features/tree/main/src
[open it locally using vs code]: https://code.visualstudio.com/docs/devcontainers/containers#_quick-start-open-an-existing-folder-in-a-container
[devcontainers]: https://containers.dev/
[github codespaces]: https://github.com/features/codespaces
<!-- prettier-ignore-end -->
