# Zugriff über SSH

github Keys aus Google Drive Ordner/Keys auf den Pi kopieren

chmod 0600 auf die Dateien

## ~/.ssh/config

```
Host github_ssh_connection
    HostName github.com
    IdentityFile ~/github_privatekey.pem
```

## Remote einrichten
```
git clone git@github_ssh_connection:JanHBade/InfoEPaper.git
```
