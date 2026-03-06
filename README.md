To initialize your local repository use
---------------------------------------

    git clone https://github.com/Tonklaistonton/local_manifests_oscaro.git -b havoc16 .repo/local_manifests
    

Then to sync up:
----------------

    repo sync --force-sync -j8 --current-branch --no-tags --no-clone-bundle --optimized-fetch --force-broken
