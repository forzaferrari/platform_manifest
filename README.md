Get Repo
---------------------------------------

    mkdir ~/bin
    PATH=~/bin:$PATH
    curl http://commondatastorage.googleapis.com/git-repo-downloads/repo > ~/bin/repo
    chmod a+x ~/bin/repo

Syncing the DU Source
---------------------------------------

    mkdir ~/dirtyunicorns
    cd ~/dirtyunicorns
    repo init -u https://github.com/AOSP-TD/platform_manifest.git -b du44
    repo sync -f -j 4 | 8 | 16 | 24 | 32

