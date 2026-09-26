# OptiScaler_DLSSNR builds

Official builds of **OptiScaler_DLSSNR**, the OptiScaler fork with the DLSS 5 (Neural Rendering) developer panel that
[OptiDLSS5-UI](https://github.com/mrcgibb9876-hash/OptiDLSS5-UI-releases) installs into games. The app downloads
these for you; you only need this page to install a build by hand or to get its source.

## Download

Every [release](https://github.com/mrcgibb9876-hash/OptiScaler_DLSSNR-releases/releases) carries two zips:

| File | What it is |
|---|---|
| `OptiScaler_<tag>.zip` | The build: OptiScaler.dll, OptiScaler.ini, the setup scripts and the licences |
| `OptiScaler_DLSSNR-<tag>-source.zip` | The complete corresponding source for that build |

`nvngx_dlssnr.dll` is never in a release. It is NVIDIA's, it comes with the driver, and it is not ours to redistribute.

## Licence and source

OptiScaler_DLSSNR is a fork of [OptiScaler](https://github.com/optiscaler/OptiScaler) and, like it, is licensed under the
**GNU General Public License v3.0**. The source zip on each release is an archive of exactly the commit that release was
built from. Its `SUBMODULES.txt` lists each third-party library the build uses (FidelityFX SDK, XeSS, ReShade, ImGui,
spdlog and others) with its upstream URL and the exact commit, all from their own public repositories.

The git tags in this repository only label the releases; they do not point at the engine's source history. The source is
the zip.
