# HGEventLogSDKAppInstance

**Namespace:** `Hypergryph.SDK`


## Methods

- `Void OnApplicationPause(Boolean)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Hypergryph.SDK
public class HGEventLogSDKAppInstance : MonoBehaviour
{


	// RVA: 0x66ca598 VA: 0x7598ce2598
	public static Boolean SetEnvironment(String env) { }
	// RVA: 0x66ca640 VA: 0x7598ce2640
	public static Boolean SetGlobalProperties(String globalProperties) { }
	// RVA: 0x66ca6ec VA: 0x7598ce26ec
	public static Boolean UnsetGlobalProperties(String propertyKeys) { }
	// RVA: 0x66ca798 VA: 0x7598ce2798
	public static Void ClearGlobalProperties() { }
	// RVA: 0x66ca834 VA: 0x7598ce2834
	public static Boolean EventTrack(String name, String properties) { }
	// RVA: 0x66ca8e8 VA: 0x7598ce28e8
	public static Boolean AppStartEvent(String channel1, String channel2, Boolean beat, String properties) { }
	// RVA: 0x66ca9b4 VA: 0x7598ce29b4
	public static Boolean UserLoginEvent(String userId, String properties) { }
	// RVA: 0x66caa68 VA: 0x7598ce2a68
	public static Void UnsetUser() { }
	// RVA: 0x66cab04 VA: 0x7598ce2b04
	public static Boolean CharacterLoginEvent(String characterId, String serverId, String properties) { }
	// RVA: 0x66cabc8 VA: 0x7598ce2bc8
	public static Void UnsetCharacter() { }
	// RVA: 0x66cac64 VA: 0x7598ce2c64
	public static String GetPresetProperties() { }
	// RVA: 0x66cad00 VA: 0x7598ce2d00
	public static Void PauseBeat() { }
	// RVA: 0x66cad9c VA: 0x7598ce2d9c
	public static Void ResumeBeat() { }
	// RVA: 0x66cae38 VA: 0x7598ce2e38
	public static Void Flush() { }
	// RVA: 0x66caed4 VA: 0x7598ce2ed4
	public static Boolean EnableRealTimeSend(Boolean enable) { }
	// RVA: 0x66caf80 VA: 0x7598ce2f80
	public static String GetStaticPresetProperties() { }
	// RVA: 0x66cb01c VA: 0x7598ce301c
	public static String GetDeviceIdProperties() { }
	// RVA: 0x66cb0b8 VA: 0x7598ce30b8
	private Void OnApplicationPause(Boolean pause) { }
	// RVA: 0x66cb19c VA: 0x7598ce319c
	public Void .ctor() { }
}
```