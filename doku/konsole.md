
# Farben setzen

Prompt 34 durch 35 ersetzen in .bashrc
```
if [ "$color_prompt" = yes ]; then
    PS1='${debian_chroot:+($debian_chroot)}\[\033[01;32m\]\u@\h\[\033[00m\]:\[\033[01;35m\]\w \$\[\033[00m\] '
else
    PS1='${debian_chroot:+($debian_chroot)}\u@\h:\w\$ '
fi
```

weiter unten more allias aktivieren, ll und so

```
dircolors -p > ~/.dircolors
```
in der Datei dann 34 durch 35 ersetzen
