WIP - This rom is an ode to Pure Nexus and will continue that thought process. 

Use as much aosp as the good Google gives us. This rom will only support pixels. 

set these alias' in .bashrc bc why type shit over and over?


alias sync='repo sync --force-sync --no-clone-bundle --current-branch --no-tags -j$(nproc --all)'


alias startkomodo='source build/envsetup.sh && lunch komodo-ap3a-userdebug && m'

sync it:

repo init -u https://github.com/Pure-Pixel/manifest -b 15

type sync

after sync and checkout

type startkomodo


