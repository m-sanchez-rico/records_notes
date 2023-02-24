
**Compile only one package:**
```
catkin_make --only-pkg-with-deps <target_package>
```
Important, Do not Forget switch back to build all packages:
```
catkin_make -DCATKIN_WHITELIST_PACKAGES=""
```


