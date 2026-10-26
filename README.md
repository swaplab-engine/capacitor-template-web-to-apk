# SwapLab Web-to-APK Template ⚡

Welcome to the official **Web-to-APK** boilerplate template for the [SwapLab Public Builder](https://public.swaplab.net). 

This repository serves as a transparent, minimal Capacitor project base. It is designed to be dynamically cloned by the SwapLab Build Engine when you select the **Web to APK (NEW)** option in the builder UI.

## 🔍 Built for Transparency
We believe in open builds. This repository is completely public so you can audit exactly what source code is being used as the foundation for your application. There is no hidden native code, no tracking, and no bloated plugins—just a standard, clean Capacitor initialization.

## ⚙️ How it Works
When you initiate a Web-to-APK build from the SwapLab interface:
1. The SwapLab Build Engine clones this exact repository.
2. Your specific UI configurations (`App Name`, `Package ID`, and `Website Base URL`) are injected directly into the `capacitor.config.json`.
3. Your uploaded App Icon is dynamically generated into native Android resources.
4. The engine compiles the project into a ready-to-install APK or AAB.

You can verify this automated process transparently through the real-time Build Terminal logs.

## 🛠️ Compatibility (Beta)
The Web-to-APK generation feature is currently in active development (Beta). For now, it requires the following build pipeline configuration:

* **Project Framework:** Capacitor
* **Target Platform:** Android
* **Engine Image:** `capacitor-build-android-engine`
* **Reference (Image Tag):** `v2.1.2` (or higher in upcoming releases)

---