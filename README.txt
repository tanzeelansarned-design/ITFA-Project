README
======

# Inspect the experiment:
-------------------------
1. Open `ITFA FINAL.xlsx` in Microsoft Excel or a compatible spreadsheet application with formula and chart support.
2. Open `Dataset` and review all 12 file extensions, owners and original recorded sizes.
3. Open `Comp`. Inspect the main ZIP results in rows 7–18 and the separate 7-Zip results in rows 26–37. Review the formulas for space saved, percentage reduction and compression ratio.
4. Open `Insights` to review file-type classifications and the compression charts. The charts are summaries of the Comp sheet rather than additional measurements.
5. Open `Transfer` to review six destination/time observations and the throughput calculations. The values are recorded observations; the workbook does not establish identical test conditions across members.
6. Open `Hashes` and compare the before/after SHA-256 strings. The `Tests` sheet contains screenshot evidence supporting the file, transfer, archive, encryption and script activities.
7. Open `321Backup` to inspect the proposed laptop, external-storage and off-site cloud arrangement.

# Required package contents:
----------------------------
Item	                                           | Submission purpose
Excel Records	                                   | Master experiment, calculations, charts and evidence screenshots.
Word Report	                                   | Problem/objectives, method, architecture, results, limitations, contributions and theory.
Original twelve sample files	                   | Allow another person to repeat the compression experiment.
Compression outputs / archive files	           | Allow verification of the measured compressed sizes and settings.
Checksum script source (`.py`) and sample output   | Make checksum automation executable and reproducible rather than screenshot-only.
README                                         	   | Explain how to open and inspect the experiment.

# Final readiness checklist against the handbook:
-------------------------------------------------
Requirement	                                                             | Status
12-file dataset across required types	                                     | Complete in workbook
Original/compressed sizes and derived metrics	                             | Complete in workbook
File type compression explanation; lossless vs lossy; repeated compression   | Addressed in report
Transfer time and throughput, USB vs cloud upload	                     | Complete in workbook + report
SHA-256 integrity before/after for at least two files	                     | Complete: six PASS results
Backup vs synchronization; 3-2-1 design	                                     | Addressed in report + workbook
Architecture/data flow/storage/offline/deletion/terms/limitation	     | Addressed in report
Tool and AI disclosure; contribution table	                             | Included in report
Multiple archive algorithms/settings bonus	                             | Output-level comparison 
Encryption and key management bonus	                                     | Evidence present
Cloud upload/download bonus	                                             | Evidence present
Automated checksum script bonus	                                             | Screenshot evidence present

