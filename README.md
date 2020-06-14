![Sugar App Store logo](https://raw.githubusercontent.com/sugarlabs-appstore/appstore-assets/22a34f9d134a526f1cb8ce49059d8a140ae885f9/sugarappstore.svg)

# sugar-activity-build
A simple continuous integration tool that clones all repositories from `sugarlabs/` and then builds a sugar activity bundle, aka `.xo`

## Adding your Bundles (.xo)
Adding your bundles are easy; Just click the following file and add the exact url 
To your git repositort (all git links are supported)
The provided link should include a `activity/activity.info` file

#### [Click to add your bundle here](https://github.com/srevinsaju/sugar-activity-build/new/master/bundles)

## Download all the bundles
All the Bundles are built on an Ubuntu 18.04 LTS Build Image provided by GitHub actions. 
The bundles are built every _0th minute_ according to the UTC Timezone. Build frequency 
will be releaxed once development on static files ceases. The tar.gz also includes the 
static website resources which was used to build the 
[sugarappstore](https://sugarstore.netlify.app) which is continuously deployed to upstream

Check out [Releases](https://github.com/srevinsaju/sugar-activity-build/releases/tag/latest) to download a release asset which is periodical basis.

## Copyright
```
Copyleft 2020 Srevin Saju. Licensed under MIT 
```
