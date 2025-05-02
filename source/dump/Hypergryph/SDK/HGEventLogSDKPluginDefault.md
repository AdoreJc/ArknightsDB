# HGEventLogSDKPluginDefault

**Namespace:** `Hypergryph.SDK`


## Methods

- `Boolean setEnvironment(String)`

- `Boolean init(String, String)`

- `Boolean setGlobalProperties(String, String)`

- `Boolean unsetGlobalProperties(String, String)`

- `Void clearGlobalProperties(String)`

- `Boolean eventTrack(String, String, String)`

- `Boolean appStartEvent(String, String, String, Boolean, String)`

- `Void pauseBeat(String)`

- `Void resumeBeat(String)`

- `Boolean userLoginEvent(String, String, String)`

- `Void unsetUser(String)`

- `Boolean characterLoginEvent(String, String, String, String)`

- `Void unsetCharacter(String)`

- `String getPresetProperties(String)`

- `String getStaticPresetProperties(String)`

- `String getDeviceIdProperties(String)`

- `Void flush(String)`

- `Boolean enableRealTimeSend(Boolean)`

- `Boolean setGlobalPropertiesV2(String)`

- `Boolean unsetGlobalPropertiesV2(String)`

- `Void clearGlobalPropertiesV2()`

- `Boolean eventTrackV2(String, String)`

- `Boolean appStartEventV2(String, String, Boolean, String)`

- `Void pauseBeatV2()`

- `Void resumeBeatV2()`

- `Boolean userLoginEventV2(String, String)`

- `Void unsetUserV2()`

- `Boolean characterLoginEventV2(String, String, String)`

- `Void unsetCharacterV2()`

- `String getPresetPropertiesV2()`

- `Void flushV2()`

- `String getStaticPresetPropertiesV2()`

- `String getDeviceIdPropertiesV2()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Hypergryph.SDK
public class HGEventLogSDKPluginDefault : IEventLogSDK
{


	// RVA: 0x66cf484 VA: 0x7598ce7484
	public Void .ctor() { }
	// RVA: 0x66cf48c VA: 0x7598ce748c
	public Boolean setEnvironment(String env) { }
	// RVA: 0x66cf494 VA: 0x7598ce7494
	public Boolean init(String appId, String regionTag) { }
	// RVA: 0x66cf49c VA: 0x7598ce749c
	public Boolean setGlobalProperties(String appId, String globalProperties) { }
	// RVA: 0x66cf4a4 VA: 0x7598ce74a4
	public Boolean unsetGlobalProperties(String appId, String propertyKeys) { }
	// RVA: 0x66cf4ac VA: 0x7598ce74ac
	public Void clearGlobalProperties(String appId) { }
	// RVA: 0x66cf4b0 VA: 0x7598ce74b0
	public Boolean eventTrack(String appId, String name, String properties) { }
	// RVA: 0x66cf4b8 VA: 0x7598ce74b8
	public Boolean appStartEvent(String appId, String channel1, String channel2, Boolean beat, String properties) { }
	// RVA: 0x66cf4c0 VA: 0x7598ce74c0
	public Void pauseBeat(String appId) { }
	// RVA: 0x66cf4c4 VA: 0x7598ce74c4
	public Void resumeBeat(String appId) { }
	// RVA: 0x66cf4c8 VA: 0x7598ce74c8
	public Boolean userLoginEvent(String appId, String userId, String properties) { }
	// RVA: 0x66cf4d0 VA: 0x7598ce74d0
	public Void unsetUser(String appId) { }
	// RVA: 0x66cf4d4 VA: 0x7598ce74d4
	public Boolean characterLoginEvent(String appId, String characterId, String serverId, String properties) { }
	// RVA: 0x66cf4dc VA: 0x7598ce74dc
	public Void unsetCharacter(String appId) { }
	// RVA: 0x66cf4e0 VA: 0x7598ce74e0
	public String getPresetProperties(String appId) { }
	// RVA: 0x66cf520 VA: 0x7598ce7520
	public String getStaticPresetProperties(String appId) { }
	// RVA: 0x66cf560 VA: 0x7598ce7560
	public String getDeviceIdProperties(String appId) { }
	// RVA: 0x66cf5a0 VA: 0x7598ce75a0
	public Void flush(String appId) { }
	// RVA: 0x66cf5a4 VA: 0x7598ce75a4
	public Boolean enableRealTimeSend(Boolean enable) { }
	// RVA: 0x66cf5ac VA: 0x7598ce75ac
	public Boolean setGlobalPropertiesV2(String globalProperties) { }
	// RVA: 0x66cf5b4 VA: 0x7598ce75b4
	public Boolean unsetGlobalPropertiesV2(String propertyKeys) { }
	// RVA: 0x66cf5bc VA: 0x7598ce75bc
	public Void clearGlobalPropertiesV2() { }
	// RVA: 0x66cf5c0 VA: 0x7598ce75c0
	public Boolean eventTrackV2(String name, String properties) { }
	// RVA: 0x66cf5c8 VA: 0x7598ce75c8
	public Boolean appStartEventV2(String channel1, String channel2, Boolean beat, String properties) { }
	// RVA: 0x66cf5d0 VA: 0x7598ce75d0
	public Void pauseBeatV2() { }
	// RVA: 0x66cf5d4 VA: 0x7598ce75d4
	public Void resumeBeatV2() { }
	// RVA: 0x66cf5d8 VA: 0x7598ce75d8
	public Boolean userLoginEventV2(String userId, String properties) { }
	// RVA: 0x66cf5e0 VA: 0x7598ce75e0
	public Void unsetUserV2() { }
	// RVA: 0x66cf5e4 VA: 0x7598ce75e4
	public Boolean characterLoginEventV2(String characterId, String serverId, String properties) { }
	// RVA: 0x66cf5ec VA: 0x7598ce75ec
	public Void unsetCharacterV2() { }
	// RVA: 0x66cf5f0 VA: 0x7598ce75f0
	public String getPresetPropertiesV2() { }
	// RVA: 0x66cf630 VA: 0x7598ce7630
	public Void flushV2() { }
	// RVA: 0x66cf634 VA: 0x7598ce7634
	public String getStaticPresetPropertiesV2() { }
	// RVA: 0x66cf674 VA: 0x7598ce7674
	public String getDeviceIdPropertiesV2() { }
}
```