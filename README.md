# AOSPA common device tree for Motorola SM6375 (holi)

Common device configuration for Motorola **SM6375 / Snapdragon 695 (holi)** devices,
converted for **AOSPA** (`beryl` / Android 16 QPR0, CLO-based).

Primary device: **moto g34 5G (`fogos`)**.

Converted from `LineageOS/android_device_motorola_sm6375-common` (branch `lineage-23.0`)
- see `CONVERSION-NOTES.md` in the device tree repo for the full change list.

## Sync

Add the local manifest (`fogos-aospa.xml`) to `.repo/local_manifests/`, then:

    repo init -u https://github.com/AOSPA/manifest -b beryl
    repo sync -c --no-tags -j8

## Copyright

    SPDX-FileCopyrightText: The LineageOS Project
    SPDX-FileCopyrightText: Paranoid Android
    SPDX-License-Identifier: Apache-2.0
