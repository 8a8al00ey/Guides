## Workflow Logic

??? summary "Workflow Logic - [CLICK TO EXPAND]"

    **Depending what's released first and available the following Workflow Logic will be used:**

    - When the 4k WEBDL is released it will download the 4k WEB-DL. (streaming services)
    - When the HQ Encode is released it will upgrade to the HQ Encode.
    - When the IMAX-E is released it will upgrade to the IMAX-E. (*optional, see below*)

    `1080p-Remux` => `1080p-WEBDL DV/HDR` => `2160p-WEBDL` =>  `2160p-Encodes` =>  `2160p-WEBDL IMAX-E`

    ------

    *Possible Variables*

    **When no 4k exist it will grab the following:**

    - 1080p WEBDL with DV/HDR
    - 1080p Remux

    !!! info "[*Optional*] IMAX Enhanced (IMAX-E)<br>- When a IMAX Enhanced exist it will upgrade/downgrade to IMAX Enhanced.<br>- IMAX Enhanced will be **ONLY** chosen if it has the same **AUDIO** and **HDR Metadata**<br>- It won't downgrade from a `TrueHD Atmos` to a `DD+ Atmos` or from a `DV` to a `HDR`."
