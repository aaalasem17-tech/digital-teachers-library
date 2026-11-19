# مكتبة المعلم الرقمية — Digital Teacher's Library (DTL)

Desktop tool for Jordanian teachers: marks registers (side + final), school certificates, the yearly marks table (الملحفة), the daily attendance register, prep books, content analysis and semester plans — plus a content library of 1,592 files (grades 4–12) and NCCD textbook viewing links.

**This repository is the update + distribution channel.** The app checks `manifest.json` here for new versions (paste its raw URL once into the app's «التحديثات» service). Each release carries the program plus the content library split into 9 grade parts (one `.zip` per grade, 4–12).

## Install

1. Download `dtl-0.1.3-app.zip` from [Releases](https://github.com/aaalasem17-tech/digital-teachers-library/releases) and extract it to a folder (e.g. Desktop) — this is the program.
2. Download the 9 library parts `dtl-0.1.3-lib-g4.zip` … `dtl-0.1.3-lib-g12.zip` and extract EACH one INSIDE the `content/library/` folder (so `imanjo-source/grade-N` and `adopted/grade-N` land there).
3. Double-click `مكتبة المعلم الرقمية.bat` — the app opens in your browser and works offline. Your data is safe — it lives in the browser (localStorage), not in the app folder.

## Updates

When a new version is published here, the app announces it with a download button (internet needed only for the check). Download the new app zip and extract it over the same folder; the library parts only need re-downloading if they changed in that version; your saved data is preserved.

## License

The package runs as a trial version; a license key activates the full version (one key per device). See the license screen inside the app.
