# BLACKWAVE K230 OTA releases

Public **binary-only** update channel for LilyGO T-Display K230 Linux v0.2.7.
This repository contains no private FR3K research, secrets, credentials, telemetry,
device identifiers, configuration files, or user data.

The associated on-device updater at `/root/blackwave/ota_agent.py` downloads
release assets over verified HTTPS, checks each asset's SHA-256 against a strict
allowlisted manifest, stages updates before installing, and keeps rollback copies.

**Scope:** user-space launcher, XiaoZhi helper and BLACKWAVE tools only.
This channel does not flash firmware partitions, bootloaders, or kernels.
