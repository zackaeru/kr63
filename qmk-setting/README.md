KR63 works on [QMK Firmware](https://qmk.fm/) 

1. Setup your QMK environment : [Official QMK document](https://docs.qmk.fm/newbs_getting_started).
1. Put this kr63 directory in `\qmk_firmware\keyboards` in your qmk home folder.
1. Build a firmware by the below command :
    ```
    qmk compile -kb kr63 -km default
    ```