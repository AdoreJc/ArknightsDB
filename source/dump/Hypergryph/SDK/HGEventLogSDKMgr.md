# HGEventLogSDKMgr

**Namespace:** `Hypergryph.SDK`


## Methods

- `Void OnApplicationPause(Boolean)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Hypergryph.SDK
public class HGEventLogSDKMgr : MonoBehaviour
{
	private static String appIdForInstance; // 0x0


	// RVA: 0x66cb1a4 VA: 0x7598ce31a4
	public static Boolean SetEnvironment(String env) { }
	// RVA: 0x66cb280 VA: 0x7598ce3280
	public static Boolean Init(String appId, String regionTag) { }
	// RVA: 0x66cb390 VA: 0x7598ce3390
	public static Boolean SetGlobalProperties(String globalProperties) { }
	// RVA: 0x66cb480 VA: 0x7598ce3480
	public static Boolean UnsetGlobalProperties(String propertyKeys) { }
	// RVA: 0x66cb570 VA: 0x7598ce3570
	public static Void ClearGlobalProperties() { }
	// RVA: 0x66cb654 VA: 0x7598ce3654
	public static Boolean EventTrack(String name, String properties) { }
	// RVA: 0x66cb758 VA: 0x7598ce3758
	public static Boolean AppStartEvent(String channel1, String channel2, Boolean beat, String properties) { }
	// RVA: 0x66cb878 VA: 0x7598ce3878
	public static Boolean UserLoginEvent(String userId, String properties) { }
	// RVA: 0x66cb97c VA: 0x7598ce397c
	public static Void UnsetUser() { }
	// RVA: 0x66cba60 VA: 0x7598ce3a60
	public static Boolean CharacterLoginEvent(String characterId, String serverId, String properties) { }
	// RVA: 0x66cbb6c VA: 0x7598ce3b6c
	public static Void UnsetCharacter() { }
	// RVA: 0x66cbc50 VA: 0x7598ce3c50
	public static String GetPresetProperties() { }
	// RVA: 0x66cbd38 VA: 0x7598ce3d38
	public static Void PauseBeat() { }
	// RVA: 0x66cbe1c VA: 0x7598ce3e1c
	public static Void ResumeBeat() { }
	// RVA: 0x66cbf00 VA: 0x7598ce3f00
	public static Void Flush() { }
	// RVA: 0x66cbfe4 VA: 0x7598ce3fe4
	public static Boolean EnableRealTimeSend(Boolean enable) { }
	// RVA: 0x66cc090 VA: 0x7598ce4090
	public static String GetStaticPresetProperties() { }
	// RVA: 0x66cc178 VA: 0x7598ce4178
	public static String GetDeviceIdProperties() { }
	// RVA: 0x66cc260 VA: 0x7598ce4260
	private Void OnApplicationPause(Boolean pause) { }
	// RVA: 0x66cc3ac VA: 0x7598ce43ac
	public Void .ctor() { }
}
```