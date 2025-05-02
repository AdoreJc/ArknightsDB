# SceneMusicPlayer

**Namespace:** `Torappu.Audio`


## Methods

- `Void Start()`

- `Void _StartImpl()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Audio
public class SceneMusicPlayer : MonoBehaviour, IHotfixable
{
	private static readonly String[] SCENES_DISABLE_AUTO_PLAY; // 0x0
	private static DelegateBridge __Hotfix0_Start; // 0x8
	private static DelegateBridge __Hotfix0__StartImpl; // 0x10
	private static DelegateBridge __Hotfix0_GameFlowController_AutoTrigger; // 0x18
	private static DelegateBridge __Hotfix0_ManuallyTrigger; // 0x20
	private static DelegateBridge __Hotfix0_StopAll; // 0x28
	private static DelegateBridge __Hotfix0__IsAutoTriggerDisabled; // 0x30
	private static DelegateBridge __Hotfix0__PlayBGM; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x3eb9124 VA: 0x75964d1124
	private Void Start() { }
	// RVA: 0x3eb9220 VA: 0x75964d1220
	private Void _StartImpl() { }
	// RVA: 0x3eb952c VA: 0x75964d152c
	public static Void GameFlowController_AutoTrigger(String sceneName) { }
	// RVA: 0x3eb95dc VA: 0x75964d15dc
	public static Void ManuallyTrigger() { }
	// RVA: 0x3eb9668 VA: 0x75964d1668
	public static Void StopAll() { }
	// RVA: 0x3eb9314 VA: 0x75964d1314
	private static Boolean _IsAutoTriggerDisabled(String sceneName) { }
	// RVA: 0x3eb9474 VA: 0x75964d1474
	private static Void _PlayBGM(String sceneName) { }
	// RVA: 0x3eb9704 VA: 0x75964d1704
	public Void .ctor() { }
	// RVA: 0x3eb9784 VA: 0x75964d1784
	private static Void .cctor() { }
}
```