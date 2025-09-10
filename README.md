
Files generated with [KNI](https://github.com/kniEngine/kni) wasm template using Visual Studio 2022.
- Removed dependency `nkast.Xna.Framework.Content.Pipeline.Builder` (MGCB.exe) to avoid build issues (e.g. run on Linux)

# Run WASM build

## CLI
```
dotnet run --launch-profile KNI_web_3 --project KNI-web-3
```

## Rider
- Select Configuration: `KNI_web_3`
- Click Run
