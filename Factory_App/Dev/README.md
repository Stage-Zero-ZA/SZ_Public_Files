# Factory App - Dev Binaries
Factory App binaries to be used during developent.

1. Binaries are available in the following format:
  - `${fw_version}/binaries/dev/` : Dev Kubernetes Server Hardcoded.
  - `${fw_version}/binaries/prod1/` : Prod Monolithic Server Hardcoded.
  - `${fw_version}/binaries/qa1/` : QA Monolithic Server Hardcoded.
  - `${fw_version}/binaries/nvs/` : Firmware uses server stored in NVS.
2. You have to generate your own nvs_custom binary with credentials.
3. Bootloader, Partition Table and NVS Standard are shared binaries located in `/${fw_version}/shared/`
