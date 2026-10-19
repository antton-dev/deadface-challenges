# Bad Calibration

**Category:** Brain Scans

**Points:** 210

## Description

\<iframe src="" style="background-image: url('https://deadface.sfo3.cdn.digitaloceanspaces.com/2026/img/wayfinder/brainscans.png');background-size:cover;background-position:center center;background-origin:content-box;background-repeat:no-repeat;background-color:rgba(40, 40, 40,0);min-height:80px;height:130px;width:100%;padding:10px;border:none" title="Thumbnail">\</iframe>
\<sup>Created By: \<code>@syyntax\</code>\</sup>

The CS-9000 refuses to run a scan unless its calibration file passes an integrity check — so the vendor clearly thought about this. Clearly.

Find how the calibration file is validated, then prove the check is worthless. We need you to determine if the scanner misreads a patient with a genuine anomaly as perfectly healthy (which would potentially cause patient harm if the anomaly goes undetected).

Make the integrity check still pass, and run the scan. If the device accepts your tampered calibration, the scan log will prove it.

Submit the flag as `deadface{flag-text}`.

[Access the Device](https://emedra.dctf.io:8080)

## Services

- [https://deadface.sfo3.cdn.digitaloceanspaces.com](https://deadface.sfo3.cdn.digitaloceanspaces.com)
- [https://emedra.dctf.io:8080](https://emedra.dctf.io:8080)
