# ChemDesign Studio

A standalone Windows desktop application for chemical-engineering **process design** and **mechanical design**. Pick *Process* or *Mechanical*, enter your data, and every result comes with a step-by-step calculation sheet, an interactive 3D model of the equipment, and a paginated PDF report.

## Download

**[Download the latest Windows build](https://github.com/sharmakrish092005-web/ChemDesignStudio/releases/latest)** (64-bit Windows 10/11)

Python is **not** required on the computer that runs it.

1. Download `ChemDesignStudio-v3-win64.zip` from the Releases page.
2. Right-click the zip and choose **Extract All**.
3. Open the extracted `ChemDesignStudio` folder and run **`ChemDesignStudio.exe`**.

Keep the `_internal` folder next to the exe - the program will not start without it. The extracted app is about 185 MB.

## Check the installation

Open a terminal in the app folder and run:

```
ChemDesignStudio.exe --self-test
```

It opens every calculation module, exports a test PDF and writes `chemdesign_selftest.log`. The last line should read `SELF-TEST PASSED`.

## Note

The executable is not code-signed, so Windows SmartScreen may warn on first launch. Choose **More info -> Run anyway**.

---

This repository hosts the released builds only. The application is closed source.
