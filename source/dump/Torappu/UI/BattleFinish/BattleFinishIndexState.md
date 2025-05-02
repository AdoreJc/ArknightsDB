# BattleFinishIndexState

**Namespace:** `Torappu.UI.BattleFinish`


## Methods

- `Void _RouteToProperState()`

- `IEnumerator _SwitchToStateCoroutine()`

- `Void _PreprocessOnBattleFinishResponse(CommonFinishBattleResponse)`

- `Void _TriggerDefaultBattleFinishBGM()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BattleFinish
public class BattleFinishIndexState : State
{
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnResume; // 0x8
	private static DelegateBridge __Hotfix0__RouteToProperState; // 0x10
	private static DelegateBridge __Hotfix0__SwitchToStateCoroutine; // 0x18
	private static DelegateBridge __Hotfix0__PreprocessOnBattleFinishResponse; // 0x20
	private static DelegateBridge __Hotfix0__TriggerDefaultBattleFinishBGM; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2e89508 VA: 0x75954a1508
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2e8956c VA: 0x75954a156c
	protected override Void OnResume() { }
	// RVA: 0x2e89a50 VA: 0x75954a1a50
	private Void _RouteToProperState() { }
	// RVA: 0x VA: 0x0
	private IEnumerator _SwitchToStateCoroutine() { }
	// RVA: 0x2e897e0 VA: 0x75954a17e0
	private Void _PreprocessOnBattleFinishResponse(CommonFinishBattleResponse response) { }
	// RVA: 0x2e8989c VA: 0x75954a189c
	private Void _TriggerDefaultBattleFinishBGM() { }
	// RVA: 0x2e89b94 VA: 0x75954a1b94
	public Void .ctor() { }
	// RVA: 0x2e89c04 VA: 0x75954a1c04
	private Void <>xLuaBaseProxy_OnResume() { }
}
```