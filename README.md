# Tern Windows test downloads
Public distribution repository for Tern. Application source is private.

Download the latest Windows x64 test ZIP from Releases, extract it fully and run Install-Tern.cmd. Installation is per-user and downloads pinned, hash-verified FFmpeg tools directly from their publisher. The Windows test executable is unsigned. Validate your actual devices before relying on it for meetings.

Settings → Check for updates → Update uses the signed preview.json feed. Checks and installation are manual. The application verifies the notice signature, package size/hash, file inventory and version before an idle update/restart. No GitHub credentials are required on the work computer.

This repository contains test binaries, distribution notes and a signed feed only. Do not upload diagnostics or audio here. No production approval or Windows publisher-signing claim is implied.