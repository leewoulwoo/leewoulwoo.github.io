# leewoulwoo.github.io
This repository has codes, documents, logs and etc for IVU development of 4GSR
# lcls-twincat-motion
Twincat 3 Motion Control Utilities for LCLS PCDS EPICS

## Quick Start
The library is installed on the plc programming nodes as `lcls-twincat-motion`. Once installed, you can create a motion-ioc-compatible setup with default settings by declaring in `Main`:
```
M1: ST_MotionStage;
fbMotion1: FB_MotionStage;
```
And invoking as:
```
fbMotion1(stMotionStage:=M1);
```

