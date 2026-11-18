# Third-party software in FlowLens

The FlowLens packages include the components below. Each is covered by its own licence, not by the FlowLens licence.
The licence files that the components ship with are inside the package, in the `_internal` folder (Linux) or inside
`FlowLens.app` (macOS), in the `*.dist-info` folders.

| Component | Version | Licence |
|---|---|---|
| Qt for Python (PySide6, Shiboken6) and the Qt libraries | 6.9.3 | LGPL-3.0, GPL-2.0 or GPL-3.0 (FlowLens uses it under the LGPL-3.0) |
| VTK | 9.7.2 | BSD 3-clause |
| NumPy | 2.5.5 | BSD 3-clause, with parts under 0BSD, MIT, Zlib and CC0 |
| SciPy | 1.18.1 | BSD 3-clause, with parts under other permissive licences |
| Matplotlib | 3.11.2 | Matplotlib licence (PSF-style) |
| contourpy, python-dateutil | 1.4.0, 4.0.0 | BSD 3-clause |
| fontTools, pyparsing | 4.68.0, 3.3.3 | MIT |
| Pillow | 13.0.0 | MIT-CMU |
| kiwisolver, cycler | 1.5.1, 0.12.1 | BSD |
| packaging | 26.3 | Apache-2.0 or BSD 2-clause |
| tzdata | 2026.6 | Apache-2.0 |
| Python | 3.12 | Python Software Foundation licence |
| PyInstaller (the bundler) | 6.22.3 | GPL-2.0 with the bootloader exception (programs it makes may use any licence) |

## Qt and the LGPL

Qt is used as shared libraries that are included unchanged in the package. You may replace them with another version of
the same libraries that is compatible with the LGPL-3.0. The Qt source code and the licence text are available from
https://www.qt.io/ and https://doc.qt.io/qt-6/lgpl.html.
