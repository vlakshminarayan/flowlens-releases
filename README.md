# FlowLens releases

FlowLens is a CFD post-processor for 3-D and 2-D field data and XY plots, with a Tecplot-style workflow.
This repository only holds the downloads; get the latest from the [Releases](../../releases/latest) page.

## Install

### Linux (x86_64)

1. Download `flowlens-<version>-linux-x86_64.tar.gz`.
2. Unpack it anywhere and run it:

   ```bash
   tar xzf flowlens-<version>-linux-x86_64.tar.gz
   ./flowlens/flowlens
   ```

It needs a desktop with OpenGL and glibc 2.30 or newer (Ubuntu 20.04+, RHEL / Rocky / Alma 9+, Debian 11+, Fedora, Arch).
Nothing else needs to be installed.

### macOS (Apple silicon)

1. Download `FlowLens-<version>-macos-arm64.dmg`.
2. Open it and drag **FlowLens.app** to **Applications**.
3. The first time, right-click the app and choose **Open** (the app is not notarised, so a plain double-click can be blocked).

## Open data

Start FlowLens and use **File → Open**, or pass files on the command line: `./flowlens/flowlens case.plt`.
