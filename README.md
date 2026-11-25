# PCNME results viewer

Interactive replays of the PCNME experiments: every scenario and method on the VFC grid and LuST maps
(seeds 3000) and the Docker testbed runs. Exported 25 Nov 2026.

[![Dataset DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24500522.svg)](https://doi.org/10.5281/zenodo.24500522)
[![Code DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24526626.svg)](https://doi.org/10.5281/zenodo.24526626)

## Run

Requires Python 3.9 or newer; nothing else is installed.

| | Windows | Linux / macOS |
| --- | --- | --- |
| Start | double-click `start.bat` | `./start.sh` |
| Stop | double-click `stop.bat` | `./stop.sh` |

The viewer opens at http://127.0.0.1:8765. Example: `#vfc/S3/pcnme/3000/fast/greedy` shows PCNME next to
Greedy in scenario S3.

**Keys:** Space play/pause · arrow keys step · `[` `]` speed · H hide the bar · F full screen ·
Esc close the panel.

## Source

Generated from [pcnme-src](https://github.com/imadbenmadi/pcnme-src) with
`uv run python -m pcnme.viewer.export`. Code: MIT. Data: CC BY 4.0.
