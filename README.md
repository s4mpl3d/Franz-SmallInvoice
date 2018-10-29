# Franz-SmallInvoice
Smallinvoice(https://smallinvoice.com) integration for Franz(https://meetfranz.com/)


- Install custom service

**Development installation on ubuntu**
```
$ git clone git@github.com:s4mpl3d/Franz-SmallInvoice.git && cd Franz-SmallInvoice
$ mkdir ~/.config/Franz/recipes/dev
$ cp -r ./ ~/.config/Franz/recipes/dev
$ rm -rf Franz-SmallInvoice
```

**Development installation on macOS**
```
$ git clone git@github.com:s4mpl3d/Franz-SmallInvoice.git && cd Franz-SmallInvoice
$ mkdir ~/Library/Application\ Support/Franz/recipes/dev
$ cp -r ./ ~/Library/Application\ Support/Franz/recipes/dev/Franz-SmallInvoice
$ rm -rf Franz-SmallInvoice
```

On Windows the directory is located here: `%appdata%/Franz/recipes/dev/`

- Reload Franz

- Open Franz settings. Under 'available services' you will find a 'Development' section