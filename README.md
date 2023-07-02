# flatpak-manifests



Install dependencies

```sh

flatpak install flathub org.freedesktop.Platform//22.08
flatpak install flathub org.freedesktop.Sdk//22.08


flatpak install flathub org.electronjs.Electron2.BaseApp//22.08
flatpak install flathub org.freedesktop.Sdk.Extension.node18//22.08



# old
flatpak install flathub org.freedesktop.Platform//21.08
flatpak install flathub org.freedesktop.Sdk//21.08

flatpak install flathub org.electronjs.Electron2.BaseApp//21.08
flatpak install flathub org.freedesktop.Sdk.Extension.node14//21.08

```


Build flatpak
```sh

flatpak-builder --user --install --force-clean build-dir manifest.yml

```
