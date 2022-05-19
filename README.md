# clam-test
This repo is only for POC work.
Example output:
```
[jsztuka@fedora clam-test]$ tkn task start clamav-poc --showlog
? Value for param `image-digest` of type `string`? (Default is `quay.io/cvpops/test-index@sha256:50154de7c88e9243afd3dfc767d4db83ff5583786405c35078746f95bb50dea9`) (quay.io/cvpops/test-index@sha? Value for param `image-digest` of type `string`? (Default is `quay.io/cvpops/test-index@sha256:50154de7c88e9243afd3dfc767d4db83ff5583786405c35078746f95bb50dea9`) quay.io/cvpops/test-index@sha256:50154de7c88e9243afd3dfc767d4db83ff5583786405c35078746f95bb50dea9
TaskRun started: clamav-poc-run-987kb
Waiting for logs to be available...
[extract-and-scan-image] 
[extract-and-scan-image] ----------- SCAN SUMMARY -----------
[extract-and-scan-image] Known viruses: 8616496
[extract-and-scan-image] Engine version: 0.103.6
[extract-and-scan-image] Scanned directories: 1328
[extract-and-scan-image] Scanned files: 8972
[extract-and-scan-image] Infected files: 0
[extract-and-scan-image] Data scanned: 277.67 MB
[extract-and-scan-image] Data read: 946.71 MB (ratio 0.29:1)
[extract-and-scan-image] Time: 129.539 sec (2 m 9 s)
[extract-and-scan-image] Start Date: 2022:05:18 11:40:31
[extract-and-scan-image] End Date:   2022:05:18 11:42:40
[extract-and-scan-image] Scan was executed on version: ClamAV 0.103.6/26543/Mon May 16 08:03:34 2022
```