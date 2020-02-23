# obs-studio settings

i like to keep my obs-studio settings tracked in git because that allows me to
revert back to a working state if i break something.

## clean installation

linux:

```
rm -rf ${HOME}/.config/obs-studio
git clone git@github.com:komidore64/obs-settings.git
ln -s $(realpath obs-settings) ${HOME}/.config/obs-studio
```

## plugins

- [obs-linuxbrowser](https://github.com/bazukas/obs-linuxbrowser)
