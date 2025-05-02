# TorappuAudio

**Namespace:** `Torappu`


## Fields

- `AudioMiddleware m_middleware`


## Methods

- `Void _Init()`

- `Void _ReloadBanks()`

- `Boolean _Play(String, String, String, Vector3)`

- `Void _Play(String, String, String, Vector3, out)`

- `Boolean _PlayEvent(String, Vector3)`

- `Void _Preload(String, String, String, String)`

- `Void _UnloadPreloadedAssets(String)`

- `Void _StopPreloadedEvents(String)`

- `Void _SetListenerPosition(Vector3, Quaternion)`

- `Void _StopAll(Single, Boolean)`

- `Void Update()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class TorappuAudio : PersistentSingleton`1, ILuaCallCSharp
{
	private AudioMiddleware m_middleware; // 0x18
	private static StringBuilder m_sb; // 0x0
	private static DelegateBridge __Hotfix0_GetChannelStatus; // 0x8
	private static DelegateBridge __Hotfix0_PlayBattle; // 0x10
	private static DelegateBridge __Hotfix1_PlayBattle; // 0x18
	private static DelegateBridge __Hotfix0_PlayBattleAndGetAtoms; // 0x20
	private static DelegateBridge __Hotfix0_PlayUI; // 0x28
	private static DelegateBridge __Hotfix0_PlaySystem; // 0x30
	private static DelegateBridge __Hotfix0_PlayEvent; // 0x38
	private static DelegateBridge __Hotfix1_PlayEvent; // 0x40
	private static DelegateBridge __Hotfix0_CreateEventName; // 0x48
	private static DelegateBridge __Hotfix0_TestEvent; // 0x50
	private static DelegateBridge __Hotfix0_PlayAndGetAtoms; // 0x58
	private static DelegateBridge __Hotfix0_SetListenerPosition; // 0x60
	private static DelegateBridge __Hotfix0_PreloadBattle; // 0x68
	private static DelegateBridge __Hotfix0_PreloadUI; // 0x70
	private static DelegateBridge __Hotfix0_PreloadSystem; // 0x78
	private static DelegateBridge __Hotfix0_UnloadPreloadedAssets; // 0x80
	private static DelegateBridge __Hotfix0_StopPreloadedEvents; // 0x88
	private static DelegateBridge __Hotfix0_Init; // 0x90
	private static DelegateBridge __Hotfix0_ReloadBanks; // 0x98
	private static DelegateBridge __Hotfix0_StopAll; // 0xa0
	private static DelegateBridge __Hotfix0__Init; // 0xa8
	private static DelegateBridge __Hotfix0__ReloadBanks; // 0xb0
	private static DelegateBridge __Hotfix0__GenerateEventName; // 0xb8
	private static DelegateBridge __Hotfix0__Play; // 0xc0
	private static DelegateBridge __Hotfix1__Play; // 0xc8
	private static DelegateBridge __Hotfix0__PlayEvent; // 0xd0
	private static DelegateBridge __Hotfix0__Preload; // 0xd8
	private static DelegateBridge __Hotfix0__UnloadPreloadedAssets; // 0xe0
	private static DelegateBridge __Hotfix0__StopPreloadedEvents; // 0xe8
	private static DelegateBridge __Hotfix0__SetListenerPosition; // 0xf0
	private static DelegateBridge __Hotfix0__StopAll; // 0xf8
	private static DelegateBridge __Hotfix0_OnInit; // 0x100
	private static DelegateBridge __Hotfix0_Update; // 0x108
	private static DelegateBridge _c__Hotfix0_ctor; // 0x110


	// RVA: 0x2d00eb4 VA: 0x7595318eb4
	public static ChannelStatus GetChannelStatus(String channelTag) { }
	// RVA: 0x2d00f28 VA: 0x7595318f28
	public static Boolean PlayBattle(String signal, String subSignal) { }
	// RVA: 0x2d01150 VA: 0x7595319150
	public static Boolean PlayBattle(String signal, String subSignal, Vector3 worldPosition) { }
	// RVA: 0x2d01258 VA: 0x7595319258
	public static AudioAtom[] PlayBattleAndGetAtoms(String signal, String subSignal, Vector3 worldPosition) { }
	// RVA: 0x2d01490 VA: 0x7595319490
	public static Boolean PlayUI(String signal, String subSignal) { }
	// RVA: 0x2d0159c VA: 0x759531959c
	public static Boolean PlaySystem(String signal, String subSignal) { }
	// RVA: 0x2d016a8 VA: 0x75953196a8
	public static Boolean PlayEvent(String eventName) { }
	// RVA: 0x2d01860 VA: 0x7595319860
	public static Boolean PlayEvent(String eventName, Vector3 worldPosition) { }
	// RVA: 0x2d01938 VA: 0x7595319938
	public static String CreateEventName(String module, String signal, String subSignal) { }
	// RVA: 0x2d01c0c VA: 0x7595319c0c
	public static Boolean TestEvent(String eventName) { }
	// RVA: 0x2d01d2c VA: 0x7595319d2c
	public static AudioAtom[] PlayAndGetAtoms(String module, String signal, String subSignal) { }
	// RVA: 0x2d01e40 VA: 0x7595319e40
	public static Void SetListenerPosition(Vector3 worldPosition, Quaternion worldRotation) { }
	// RVA: 0x2d02060 VA: 0x759531a060
	public static Void PreloadBattle(String persistTag, String signal, String subSignal) { }
	// RVA: 0x2d02224 VA: 0x759531a224
	public static Void PreloadUI(String persistTag, String signal, String subSignal) { }
	// RVA: 0x2d022fc VA: 0x759531a2fc
	public static Void PreloadSystem(String persistTag, String signal, String subSignal) { }
	// RVA: 0x2d023d4 VA: 0x759531a3d4
	public static Void UnloadPreloadedAssets(String persistTag) { }
	// RVA: 0x2d0253c VA: 0x759531a53c
	public static Void StopPreloadedEvents(String persistTag) { }
	// RVA: 0x2d026a4 VA: 0x759531a6a4
	public static Void Init() { }
	// RVA: 0x2d0280c VA: 0x759531a80c
	public static Void ReloadBanks() { }
	// RVA: 0x2d02924 VA: 0x759531a924
	public static Void StopAll(Single fadeTime, Boolean exceptMusic) { }
	// RVA: 0x2d02734 VA: 0x759531a734
	private Void _Init() { }
	// RVA: 0x2d0289c VA: 0x759531a89c
	private Void _ReloadBanks() { }
	// RVA: 0x2d019e4 VA: 0x75953199e4
	private static String _GenerateEventName(String module, String signal, String subSignal) { }
	// RVA: 0x2d01034 VA: 0x7595319034
	private Boolean _Play(String module, String signal, String subSignal, Vector3 worldPosition) { }
	// RVA: 0x2d01368 VA: 0x7595319368
	private Void _Play(String module, String signal, String subSignal, Vector3 worldPosition, out AudioAtom[] atoms) { }
	// RVA: 0x2d01784 VA: 0x7595319784
	private Boolean _PlayEvent(String eventName, Vector3 worldPosition) { }
	// RVA: 0x2d02138 VA: 0x759531a138
	private Void _Preload(String persistTag, String module, String signal, String subSignal) { }
	// RVA: 0x2d0249c VA: 0x759531a49c
	private Void _UnloadPreloadedAssets(String persistTag) { }
	// RVA: 0x2d02604 VA: 0x759531a604
	private Void _StopPreloadedEvents(String persistTag) { }
	// RVA: 0x2d01f54 VA: 0x7595319f54
	private Void _SetListenerPosition(Vector3 worldPosition, Quaternion worldRotation) { }
	// RVA: 0x2d029d8 VA: 0x759531a9d8
	private Void _StopAll(Single fadeTime, Boolean exceptMusic) { }
	// RVA: 0x2d02a94 VA: 0x759531aa94
	protected override Void OnInit() { }
	// RVA: 0x2d02b34 VA: 0x759531ab34
	private Void Update() { }
	// RVA: 0x2d02bc8 VA: 0x759531abc8
	public Void .ctor() { }
	// RVA: 0x2d02c68 VA: 0x759531ac68
	private static Void .cctor() { }
}
```