# Cellz.io-Protocol
Packets sent by client to server

## Client => Server

| OnOpen        | Type         |  Value            |
| ------------- |:------------:| -----------------:|
| 1             | Uint8Array   | [254, 5, 0, 0, 0] |
|2            | Uint8Array   | [255, 0, 0, 0, 0] |


| Function  |  Type    |  Value    |
| ---------- |:-------:| ----------:|
| Split | Uint8Array  |  [17] |
| Feed | Uint8Array  |  [21] |
|Spectate| Uint8Array| [1]|

### Spawn
|Offset| Type | Value |
|------|------|--------|
| 0 | Uint8 | 99 |
| 1 | Uint8 | 0 |
| Nick | UInt16 | asPerCharCode|

| Mouse | Type | Value |
|-------|:-----:|------:|
| x     | Uint32| - |
| y     | Uint32| - |
| opcode| Uint8 | 0x10|

