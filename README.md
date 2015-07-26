IPHCFlatTree
============

IPHC analysis framework based on FlatTree

Install
-------

```
# CMSSW Release
RELEASE=7_4_7

# Setup release
cmsrel CMSSW_$RELEASE
cd CMSSW_X_Y_Z/src
cmsenv
git cms-init

# Clone this repo
git clone https://github.com/IPHC/IPHCFlatTree.git

# Switch to particular release, otherwise ignore these lines to use the HEAD
cd IPHCFlatTree
git checkout MantaRay-patch6
cd ../

# Compile the monster
scram b
```
