# VKT Weather – Forecast Products Viewer

Web app for viewing GRIB forecasts (GFS, ICON, ECMWF, wave and current models), ERA5 climatology, Saildocs requests,
Open-Meteo downloads and Go / No-Go wind limits. Everything runs in the browser – GRIB files are read on your own
computer and are **never uploaded**.

**Open:** https://r11metoc.github.io/vkt-weather/ (Chrome or Edge recommended).
**Install as an app:** in Chrome / Edge click the install icon in the address bar (or menu → *Install VKT Weather*);
on Android *Add to home screen*. After the first visit it also opens without internet.

Files: `index.html` (the whole app, ~21 MB incl. climatology), `sw.js` (offline cache), `manifest.webmanifest` + icons (install),
`.nojekyll`. To update, replace `index.html` (and raise `CACHE` in `sw.js` to force an immediate refresh).
Built from `pyprojects/webapp/standalone` with `python build.py`.

Data credits: ERA5 (Copernicus / ECMWF), NOAA GFS / WaveWatch III / RTOFS via Saildocs, Open-Meteo.com (CC BY 4.0, non-commercial),
Natural Earth boundaries (India point of view).
