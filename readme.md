## build instructions
```
flatpak install org.gnome.Sdk/x86_64/44
flatpak install org.freedesktop.Sdk.Extension.rust-nightly/x86_64/22.08    
flatpak-builder --install --user --force-clean --state-dir=../build/flatpak-builder --repo=./build/flatpak-builder --repo=../build/flatpak-repo ../build/flatpak-target ./com.gitbutler.gitbutler.yaml 
```