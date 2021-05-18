# parcelv2troika3dtext

I've encountered an issue with parcel (v2) in combination with the Text component from [@react-three/drei](https://www.npmjs.com/package/@react-three/drei). 

The following command servers the build files
```
parcel serve ./src/index.html
```
but when we navigate to the browser it gives following error
```
Class constructor InstancedBufferGeometry cannot be invoked without 'new'
    at new GlyphsGeometry
```

However, when we build the project using
```
parcel build ./src/index.html
```

and use live-server to quickly check, it runs without issues.
