# Linux Assistant Flatpak

## Building

```
flatpak run org.flatpak.Builder --force-clean --sandbox --user --install --install-deps-from=flathub --ccache --mirror-screenshots-url=https://dl.flathub.org/media/ --repo=repo builddir io.github.jean28518.Linux-Assistant.yml
```

Then you can run it via the command line:

```
flatpak run io.github.jean28518.Linux-Assistant
```

or just search for the installed app on your system
