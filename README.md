# PCNME history viewer (exported 06 Nov 2026)

Replays of the PCNME runs: every scenario and method, seeds 3000, and the testbed runs.

    python serve.py          (any Python 3.9+, nothing to install; Windows: double-click start.bat)

The browser opens http://127.0.0.1:8765. Try #vfc/S3/pcnme/3000/fast/greedy for PCNME next to Greedy.
Keys: Space play/pause, arrow keys step, [ ] speed, H hide the bar, F full screen, Esc close the panel.

Made with `uv run python -m pcnme.viewer.export` in the pcnme-src repo; export again to update it.
