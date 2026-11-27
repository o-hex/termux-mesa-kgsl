# termux-mesa-kgsl

Automated GitHub Actions build of Termux `mesa` (`26.3.1`, aarch64) with **Freedreno + KGSL Gallium** (`kgsl_dri.so` / `/dev/kgsl-3d0`) enabled for native OpenGL acceleration on Adreno GPUs in Termux:X11.

Based on `termux/termux-packages` (`packages/mesa`) with the Freedreno KGSL DRM, Gallium, EGL, GLX, Loader, and X11/DRI3 WSI patches adapted from `lfdevs/mesa-for-android-container`.
