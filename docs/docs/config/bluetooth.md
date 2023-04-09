---
title: Bluetooth Configuration
sidebar_label: Bluetooth
---

See the [bluetooth feature page](../features/bluetooth.md) for more details on the general Bluetooth functionality in ZMK.

See [Configuration Overview](index.md) for instructions on how to change these settings.

## Kconfig

| Option                                | Type | Description                                                                                                             | Default |
| ------------------------------------- | ---- | ----------------------------------------------------------------------------------------------------------------------- | ------- |
| `CONFIG_BT_GATT_ENFORCE_SUBSCRIPTION` | bool | Low level setting for GATT subscriptions. Set to `n` to work around an annoying Windows bug with battery notifications. | y       |
