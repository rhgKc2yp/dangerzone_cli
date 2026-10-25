# dangerzone_cli
Dangerzone CLI Only Version

Build an unofficial Dangerzone 0.11.1 CLI-only RPM on Fedora 45 (x86_64). Designed for Fedora Toolbox: NO build tools are installed on the Silverblue host.

Changes to upstream: remove GUI/PySide6/Shiboken6; retain only english Tesseract(OCR) dependencies; extend Python range for F45;

retain all other runtime dependencies and Dangerzone's cosign image verification.