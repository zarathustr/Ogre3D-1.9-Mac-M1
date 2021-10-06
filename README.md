# Ogre3D-1.9-Mac-M1
The Modified Ogre3D v1.9.1 with Compatability of Apple M1 Mac. It removes the bug caused in SIMD of Apple aarch64 processors.

# Codes
Enter the directory sinbad-ogre-108ab0bcc696 and:
```
mkdir build
cd build
cmake ..
make install
```

# Executables
Extract the package ogre1.9.zip. If you have installed ```brew```, please use the following commands:
```
cp -rf ogre1.9 /opt/homebrew/Cellar/
brew link ogre1.9
```
