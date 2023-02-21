# Build Flags
## Build Flags to make the ROM more customizable



### Use 64-bit dex2oat for better dexopt time.

```
TARGET_SUPPORTS_64_BIT_APPS := true
```

----------------------------------------------------------------------------
### Add GAPPS to build

```
TARGET_BUILD_GAPPS := true
```



----------------------------------------------------------------------------

### Add Revamped FM Radio to build  **ONLY FOR MTK**

```
SHIP_MTK_FM_RADIO := true
```

----------------------------------------------------------------------------


### Ship AdAway

```
WITH_ADAWAY := true
```

----------------------------------------------------------------------------


### Add some props to optimize battery 
## **MAY NOT WORK ON ALL DEVICES!**

```
BUILD_BATTERY_OPT:= true
```

----------------------------------------------------------------------------


### Enable blurs on supported devices

```
TARGET_ENABLE_BLUR:= true
```

----------------------------------------------------------------------------

