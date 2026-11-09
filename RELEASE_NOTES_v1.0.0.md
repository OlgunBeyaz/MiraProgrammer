# MiraProgrammer v1.0.0 – Windows Portable & Linux

## First release

MiraProgrammer is distributed as **freeware for Windows and Linux**. This release provides the distribution information and installation instructions for the first version. The application is intended to be used without access to its source code.

> **Before publishing:** Attach the actual, tested Windows and Linux application packages to this release. Do not publish this release as a completed software download until those files are available.

## Available platforms and planned packages

| Platform | Release file | Architecture | Installation |
| --- | --- | --- | --- |
| Windows | `MiraProgrammer-Windows-Portable.zip` | x86-64 | Extract and run |
| Linux | `MiraProgrammer-Linux.AppImage` | x86-64 | Download and execute |

The package names above are the intended release asset names. Their availability depends on which binaries are uploaded.

## Windows – Portable version

1. Download `MiraProgrammer-Windows-Portable.zip` from the **Assets** section below.
2. Extract the ZIP archive to a folder of your choice.
3. Open the extracted folder and run `MiraProgrammer.exe`.
4. Keep any bundled files and subfolders together with the executable.

A traditional Windows installer is not required for the portable package. Depending on the final build, the application may still store user settings in standard Windows user directories.

## Linux – AppImage version

1. Download `MiraProgrammer-Linux.AppImage` from the **Assets** section below.
2. Open a terminal in the directory containing the downloaded file.
3. Grant execute permission and start the application:

```bash
chmod +x MiraProgrammer-Linux.AppImage
./MiraProgrammer-Linux.AppImage
```

Alternatively, mark the AppImage as executable through the file manager and launch it there.

An AppImage generally does not require installation with a package manager. Some Linux distributions may need additional runtime libraries or AppImage/FUSE compatibility support, depending on the final build.

## Distribution and licensing

- **Freeware:** MiraProgrammer is available for use at no purchase cost.
- **Closed source:** The application source code is not included in the downloads.
- **Separate packages:** Download only the package that matches your operating system.
- **No source repository access required:** Users only need the compiled release files.

**Copyright:** All rights reserved. Freeware does not automatically grant permission to redistribute, modify, or reverse-engineer the application. Any additional permissions must be stated in the software's accompanying terms.

## Version details

- **Version:** 1.0.0
- **Release tag:** `v1.0.0`
- **Release channel:** Stable (after the application packages have been built and tested)
- **Platforms:** Windows x86-64 and Linux x86-64
- **Distribution:** Portable ZIP (Windows) and AppImage (Linux)
- **Source code:** Not publicly distributed

## Troubleshooting

**Windows:** If the application does not start, check that the complete ZIP was extracted and all required companion files are still in the same relative folders. The appropriate system runtime may be needed depending on the build.

**Linux:** If the file does not start, check its executable permission, confirm that the CPU architecture matches, and run it from a terminal to view the error message.

## Downloads

When the compiled packages are uploaded, they will appear in the **Assets** area of this release. GitHub's automatically generated *Source code (zip/tar.gz)* archives are repository snapshots and are **not** the Windows or Linux application downloads.

---
Official repository: https://github.com/OlgunBeyaz/MiraProgrammer
