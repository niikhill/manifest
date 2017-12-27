<p align="center">
<img src="" width="320px" height="320px" > 
</p>




How to Build?
-------------

To initialize your local repository using the AospExtended trees, use a 
command like this:

```bash
  repo init -u git://github.com/backchod/manifest.git -b 8.1.x
```
  
Then to sync up:
----------------

```bash
  repo sync -c -jx --force-sync --no-clone-bundle --no-tags
```
Finally to build:
-----------------

```bash
  . build/envsetup.sh
  lunch bakchod_device_codename-userdebug
   
```
