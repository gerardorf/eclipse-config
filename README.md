# Eclipse workspace configuration
## Download barebone version of eclipse
Download latest release from [eclipse downloads site] (only the [Platform Runtime Binaries] ~60MB)

## Suggested plugins
All of them can be downloaded from the marketplace
- eclemma
- vrapper
- startexplorer
- mousefeed
- workspace mechanic
- saros pair programming

Downloaded from repository sites: (repo added with workspace mechanics)
- cucumber

## Workspace configuration
This is my most common configuration on eclipse.
* mechanic directory contains [Workspace Mechanic] Preferences.
* vrapper directory contains [Vrapper] Configuration.

#### Installation process

```sh
$ git clone https://github.com/gerardorf/eclipse-config.git ~/.eclipse
$ ln -s ~/.eclipse/vrapper/.vrapperrc ~/.vrapperrc
```

[eclipse downloads site]:http://download.eclipse.org/eclipse/downloads/
[Platform Runtime Binaries]:http://www.eclipse.org/downloads/download.php?file=/eclipse/downloads/drops4/R-4.4.2-201502041700/eclipse-platform-4.4.2-linux-gtk-x86_64.tar.gz
[Workspace Mechanic]:http://marketplace.eclipse.org/content/workspace-mechanic
[Vrapper]:http://marketplace.eclipse.org/content/vrapper
