# PanTilt — Non-Commercial Evaluation License

**This is not a commercial license.**

This **evaluation build** may be used only for **testing**, **student / teaching use**, and **scientific research**. Source code is not included in the zip. No commercial, industrial, or production rights are granted by this document.

Copyright © 2026 olesha-ai. All rights reserved.

## 1. Permitted use

You may download, install, and run the compiled PanTilt binaries (`PanTilt.exe`, optional `trig.exe`, associated DLLs / models) **only** for:

- Personal or lab testing and benchmarking
- Student coursework, teaching demos, university projects
- Scientific research and non-commercial academic experiments
- Sending the author feedback (performance, cameras, neck/COM, bugs)

## 2. Prohibited without a separate written agreement

Under this license you may **not**:

- Use the software for commercial, industrial, OEM, or paid production purposes
- Deploy it as a commercial product on a production line or paid service
- Sell, rent, or sublicense the binaries for profit
- Reverse-engineer or decompile the binaries to extract source
- Redistribute the package publicly without this license still applying
- Remove copyright / brand notices from the binaries

## 3. No commercial rights here

If you need commercial or OEM use, that needs a **separate written agreement**. Until then you have no commercial rights under this file.

Contact: GitHub Issue (`license-inquiry`) or the author’s GitHub profile.

## 4. Liability

THIS SOFTWARE IS PROVIDED “AS IS” WITHOUT WARRANTY OF ANY KIND. THE AUTHOR IS NOT LIABLE FOR DAMAGES FROM USE OR MISUSE, INCLUDING DOWNTIME, HARDWARE DAMAGE, DATA LOSS, OR BAD DETECTIONS. YOU RUN IT AT YOUR OWN RISK.

## 5. Third-party (not our IP)

PanTilt links against and may ship DLLs / model files from others. This license does **not** own those projects.

| Component | Typical license |
|-----------|-----------------|
| Intel OpenVINO | Apache 2.0 |
| ONNX Runtime | MIT |
| YOLOX (weights line) | Apache 2.0 (upstream) |
| LightGBM / Cat ONNX (if shipped) | upstream + my trained weights under this eval package |
| Nim, Dear ImGui, GLFW, libyuv | MIT / zlib / BSD as upstream |
| MinGW runtime DLLs next to the exe | GCC runtime exception / upstream |
| Arduino sketches (Adafruit PCA9685, U8g2) | upstream BSD/MIT-style — see their repos if you flash them |
| Windows Media Foundation | Microsoft platform terms |

Full texts for the main redistributed pieces are in the `licenses/` folder. Keep that folder with the zip.

PanTilt is not an Intel, Microsoft, or Megvii product and is not endorsed by them. Trademarks belong to their owners.

Vision UI/Out rails relate to my [EdgeInfer](https://github.com/olesha-ai/edgeinfer-eval) eval line; that project has its own license text as well.

---

*By running `PanTilt.exe` from this evaluation package you agree to the limits above.*
