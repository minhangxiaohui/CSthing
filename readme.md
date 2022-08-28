# 这个项目主要存放，研究Cobaltstrike的时候可能会用到的一些tools：

## 1、1768 for getting infomation from stagebeacon

eg：``python3 1768.py stagebeaconname``

## 2、cs-decrypt-metadata for decryptting the metadata with the common key or the specified key

eg：``python3 cs-decrypt-metadata.py -p privetakey encryptedmetadata``

eg: ``python3 cs-decrypt-metadata.py -p .cobaltstrike.beaconkey encryptedmetadata``

## 3、cs-parse-http-traffic for decryptting the datas with the key in metadata（symmetric key）

eg：``python3 cs-parse-http-traffic.py -r Rawkey -Y "wireshark filter command" file.pcap ``



