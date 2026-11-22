# FeatherLux
# 🪶 FeatherFlux Shaders

**A pure-math, zero-shadow-pass Minecraft shader built for integrated graphics and low-end hardware.**

FeatherFlux delivers rich lighting, dynamic cloud shadows, reflective water, and cinematic color grading without tanking your FPS—even while flying at full speed with an Elytra.

---

## ✨ Key Features

* **Zero Shadow Map Overhead:** Calculates directional sunlight and ambient shading purely through vector math (`N·L` dot products) instead of rendering the world twice.
* **Procedural Cloud Shadows:** Dynamic, moving cloud shadows computed mathematically in world space with zero texture lookups.
* **Analytical Water & Fresnel Reflections:** Real-time wave normals derived from sine/cosine functions paired with Schlick's Fresnel approximation and sun specular highlights.
* **ACES Filmic Tone Mapping:** Cinema-grade contrast and color balance at almost zero GPU cost.
* **Potato-PC Friendly:** Designed and tested specifically on Intel UHD integrated graphics (128 MB dedicated VRAM / shared system memory).

---

## 💻 Requirements & Compatibility

* **Mod Loader:** Fabric / Quilt / NeoForge
* **Required Mods:** [Sodium](https://modrinth.com/mod/sodium) + [Iris Shaders](https://modrinth.com/mod/iris) *(OptiFine is not recommended on Intel integrated GPUs)*
* **Minecraft Versions:** 1.20.x – 1.21.x
* **Tested Hardware:** Intel Core i3-1215U · Intel UHD Graphics · 8 GB RAM

---

## 📥 Installation

1. Go to the **[Releases](../../releases)** tab on the right side of this page.
2. Download the latest `FeatherFlux-vX.X.zip` file.
3. Open Minecraft and navigate to `Options → Video Settings → Shader Packs`.
4. Click **Open Shader Pack Folder** and drop the `.zip` file inside (do not extract it).
5. Select **FeatherFlux** in-game and click **Apply**.

---

## 🐛 Feedback & Bug Reports

Found a visual glitch or have an idea for a lightweight math-based effect? Open an issue in the **[Issues](../../issues)** tab with your Minecraft version, Iris version, and a screenshot.
