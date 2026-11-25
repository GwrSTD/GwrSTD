<div align="center">
  <h1>Hi, I'm Gunewr7 (GwrSTD) 👋</h1>
  <p><strong>Building offline-first mobile apps, 3D geometry tools, and Minecraft Java utilities with Rust and Android.</strong></p>

  <p>
    <a href="https://github.com/GwrSTD/render-builds">
      <img src="https://img.shields.io/badge/Featured-Render%20Builds-007AFF?style=for-the-badge" alt="Render Builds" />
    </a>
    <a href="https://github.com/GwrSTD/render-builds/releases/latest/download/Render-Builds.apk">
      <img src="https://img.shields.io/badge/Android%20APK-Download-34C759?style=for-the-badge&logo=android&logoColor=white" alt="Download Render Builds APK" />
    </a>
  </p>
</div>

---

## Featured Project

### 🧊 [Render Builds](https://github.com/GwrSTD/render-builds)
A **100% offline, Rust-powered Android app** that converts front, side, and top photos into Minecraft Java `.schem` schematics—with zero AI APIs and zero network permissions.

- **Native Rust Engine:** Image decoding, threshold silhouette extraction, 3D Visual Hull reconstruction, CIELAB block matching, face-culled 3D meshing, and Gzip-compressed Sponge v2 NBT export compiled to native ARM64/ARMv7 via JNI
- **Clean Apple HIG-Inspired Design:** Calm Light & Dark appearance, translucent controls, layer-by-layer 2D editing (doors, windows, undo/redo), and built-in English & Turkish support
- **Direct Android Downloads Export:** Writes `.schem` files directly to Android **Downloads** using native Rust JNI → `MediaStore`

👉 [**Explore Repository**](https://github.com/GwrSTD/render-builds) • [**Download Render-Builds.apk**](https://github.com/GwrSTD/render-builds/releases/latest/download/Render-Builds.apk) • [**Releases**](https://github.com/GwrSTD/render-builds/releases)

---

## Tech Stack

| Area | Tools & Technologies |
| --- | --- |
| **Systems & Core** | `Rust` · `JNI` · `Android NDK` · `WebGL` |
| **Mobile** | `Android` · `Gradle` · `MediaStore API` · `Apple HIG Design` |
| **Minecraft Formats** | `Sponge Schematic v2 (.schem)` · `NBT` · `Gzip (flate2)` · `WorldEdit / Litematica` |
| **Automation** | `GitHub Actions` · `Cross-Compilation` · `APK Signing` · `GitHub Releases` |
