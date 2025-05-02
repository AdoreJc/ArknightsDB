# CriAtomServer

**Namespace:** `CriWare`


## Methods

- `Void Awake()`

- `Void ConsumePcmOutput()`

- `Void OnApplicationPause(Boolean)`

- `Void ProcessApplicationPause(Boolean)`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriAtomServer : CriMonoBehaviour
{
	private static CriAtomServer _instance; // 0x0
	public Action`1 onApplicationPausePreProcess; // 0x28
	public Action`1 onApplicationPausePostProcess; // 0x30
	public static Boolean KeepPlayingSoundOnPause; // 0x8
	public static Boolean EnableAutoConsumePcmOutput; // 0x9
	public static Boolean EnableBackgroundPlayback_ANDROID; // 0xa

	public static CriAtomServer instance { get; }

	// RVA: 0x4117920 VA: 0x759672f920
	public static CriAtomServer get_instance() { }
	// RVA: 0x4113c94 VA: 0x759672bc94
	public static Void CreateInstance() { }
	// RVA: 0x4113f28 VA: 0x759672bf28
	public static Void DestroyInstance() { }
	// RVA: 0x411797c VA: 0x759672f97c
	private Void Awake() { }
	// RVA: 0x4117a6c VA: 0x759672fa6c
	protected override Void OnEnable() { }
	// RVA: 0x4117a74 VA: 0x759672fa74
	protected override Void OnDisable() { }
	// RVA: 0x4117b4c VA: 0x759672fb4c
	public override Void CriInternalUpdate() { }
	// RVA: 0x4117ba4 VA: 0x759672fba4
	public override Void CriInternalLateUpdate() { }
	// RVA: 0x4117ba0 VA: 0x759672fba0
	private Void ConsumePcmOutput() { }
	// RVA: 0x4117ba8 VA: 0x759672fba8
	private Void OnApplicationPause(Boolean appPause) { }
	// RVA: 0x4117bb0 VA: 0x759672fbb0
	private Void ProcessApplicationPause(Boolean appPause) { }
	// RVA: 0x4117c80 VA: 0x759672fc80
	public Void .ctor() { }
	// RVA: 0x4117c88 VA: 0x759672fc88
	private static Void .cctor() { }
}
```