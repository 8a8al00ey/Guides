??? summary "Optional UHD - [CLICK TO EXPAND]"

    !!! danger "**The `SDR` is a MUST for this Quality Profile** :warning:"

    | Custom Format                                                                                                       | Score                                                | Trash ID                                          |
    | ------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------- | ------------------------------------------------- |
    | [{{ sonarr['cf']['sdr']['name'] }}](/Sonarr/sonarr-collection-of-custom-formats/#sdr)                                 | {{ sonarr['cf']['sdr']['trash_score'] }}              | {{ sonarr['cf']['sdr']['trash_id'] }}              |

    ------

    Breakdown and Why

    - **{{ sonarr['cf']['sdr']['name'] }}:** This will help to prevent to grab UHD/4k releases without HDR Formats.
