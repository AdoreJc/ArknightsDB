# HGEventLogSDKPluginAndroid

**Namespace:** `Hypergryph.SDK`


## Fields

- `AndroidJavaClass jc`

- `AndroidJavaObject currentActivity`

- `AndroidJavaClass eventLogModule`

- `AndroidJavaObject appController`


## Methods

- `Boolean setEnvironment(String)`

- `Boolean init(String, String)`

- `Boolean setGlobalProperties(String, String)`

- `Boolean setGlobalPropertiesV2(String)`

- `Boolean unsetGlobalProperties(String, String)`

- `Boolean unsetGlobalPropertiesV2(String)`

- `Void clearGlobalProperties(String)`

- `Void clearGlobalPropertiesV2()`

- `Boolean eventTrack(String, String, String)`

- `Boolean eventTrackV2(String, String)`

- `Boolean appStartEvent(String, String, String, Boolean, String)`

- `Boolean appStartEventV2(String, String, Boolean, String)`

- `Void pauseBeat(String)`

- `Void pauseBeatV2()`

- `Void resumeBeat(String)`

- `Void resumeBeatV2()`

- `Boolean userLoginEvent(String, String, String)`

- `Boolean userLoginEventV2(String, String)`

- `Void unsetUser(String)`

- `Void unsetUserV2()`

- `Boolean characterLoginEvent(String, String, String, String)`

- `Boolean characterLoginEventV2(String, String, String)`

- `Void unsetCharacter(String)`

- `Void unsetCharacterV2()`

- `String getPresetProperties(String)`

- `String getPresetPropertiesV2()`

- `String getStaticPresetProperties(String)`

- `String getStaticPresetPropertiesV2()`

- `String getDeviceIdProperties(String)`

- `String getDeviceIdPropertiesV2()`

- `Void flush(String)`

- `Void flushV2()`

- `Boolean enableRealTimeSend(Boolean)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Hypergryph.SDK
public class HGEventLogSDKPluginAndroid : IEventLogSDK
{
	private AndroidJavaClass jc; // 0x10
	private AndroidJavaObject currentActivity; // 0x18
	private AndroidJavaClass eventLogModule; // 0x20
	private AndroidJavaObject appController; // 0x28


	// RVA: 0x66ca3cc VA: 0x7598ce23cc
	public Void .ctor() { }
	// RVA: 0x66cc3b4 VA: 0x7598ce43b4
	public Boolean setEnvironment(String env) { }
	// RVA: 0x66cc520 VA: 0x7598ce4520
	public Boolean init(String appId, String regionTag) { }
	// RVA: 0x66cc724 VA: 0x7598ce4724
	public Boolean setGlobalProperties(String appId, String globalProperties) { }
	// RVA: 0x66cc890 VA: 0x7598ce4890
	public Boolean setGlobalPropertiesV2(String globalProperties) { }
	// RVA: 0x66cc9fc VA: 0x7598ce49fc
	public Boolean unsetGlobalProperties(String appId, String propertyKeys) { }
	// RVA: 0x66ccb68 VA: 0x7598ce4b68
	public Boolean unsetGlobalPropertiesV2(String propertyKeys) { }
	// RVA: 0x66cccd4 VA: 0x7598ce4cd4
	public Void clearGlobalProperties(String appId) { }
	// RVA: 0x66cce10 VA: 0x7598ce4e10
	public Void clearGlobalPropertiesV2() { }
	// RVA: 0x66ccf4c VA: 0x7598ce4f4c
	public Boolean eventTrack(String appId, String name, String properties) { }
	// RVA: 0x66cd104 VA: 0x7598ce5104
	public Boolean eventTrackV2(String name, String properties) { }
	// RVA: 0x66cd2bc VA: 0x7598ce52bc
	public Boolean appStartEvent(String appId, String channel1, String channel2, Boolean beat, String properties) { }
	// RVA: 0x66cd548 VA: 0x7598ce5548
	public Boolean appStartEventV2(String channel1, String channel2, Boolean beat, String properties) { }
	// RVA: 0x66cd7d4 VA: 0x7598ce57d4
	public Void pauseBeat(String appId) { }
	// RVA: 0x66cd910 VA: 0x7598ce5910
	public Void pauseBeatV2() { }
	// RVA: 0x66cda4c VA: 0x7598ce5a4c
	public Void resumeBeat(String appId) { }
	// RVA: 0x66cdb88 VA: 0x7598ce5b88
	public Void resumeBeatV2() { }
	// RVA: 0x66cdcc4 VA: 0x7598ce5cc4
	public Boolean userLoginEvent(String appId, String userId, String properties) { }
	// RVA: 0x66cde7c VA: 0x7598ce5e7c
	public Boolean userLoginEventV2(String userId, String properties) { }
	// RVA: 0x66ce034 VA: 0x7598ce6034
	public Void unsetUser(String appId) { }
	// RVA: 0x66ce170 VA: 0x7598ce6170
	public Void unsetUserV2() { }
	// RVA: 0x66ce2ac VA: 0x7598ce62ac
	public Boolean characterLoginEvent(String appId, String characterId, String serverId, String properties) { }
	// RVA: 0x66ce4b8 VA: 0x7598ce64b8
	public Boolean characterLoginEventV2(String characterId, String serverId, String properties) { }
	// RVA: 0x66ce6c4 VA: 0x7598ce66c4
	public Void unsetCharacter(String appId) { }
	// RVA: 0x66ce800 VA: 0x7598ce6800
	public Void unsetCharacterV2() { }
	// RVA: 0x66ce93c VA: 0x7598ce693c
	public String getPresetProperties(String appId) { }
	// RVA: 0x66cea78 VA: 0x7598ce6a78
	public String getPresetPropertiesV2() { }
	// RVA: 0x66cebb4 VA: 0x7598ce6bb4
	public String getStaticPresetProperties(String appId) { }
	// RVA: 0x66cecf0 VA: 0x7598ce6cf0
	public String getStaticPresetPropertiesV2() { }
	// RVA: 0x66cee2c VA: 0x7598ce6e2c
	public String getDeviceIdProperties(String appId) { }
	// RVA: 0x66cef68 VA: 0x7598ce6f68
	public String getDeviceIdPropertiesV2() { }
	// RVA: 0x66cf0a4 VA: 0x7598ce70a4
	public Void flush(String appId) { }
	// RVA: 0x66cf1c8 VA: 0x7598ce71c8
	public Void flushV2() { }
	// RVA: 0x66cf2ec VA: 0x7598ce72ec
	public Boolean enableRealTimeSend(Boolean enable) { }
}
```