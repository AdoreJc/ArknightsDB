# RhineBattlePerformanceState

**Namespace:** `Torappu.Activity.Act25side`


## Fields

- `RhineBattlePerformanceView _view`

- `RectTransform _backRect`

- `RhineBattlePerformanceStateBean m_stateBean`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void _ConsumeLocalTrack(String)`

- `Void OnClickBackBtn()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act25side
public class RhineBattlePerformanceState : State
{
	private RhineBattlePerformanceView _view; // 0x50
	private RectTransform _backRect; // 0x58
	private RhineBattlePerformanceStateBean m_stateBean; // 0x60
	private Boolean m_isInited; // 0x68
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__ConsumeLocalTrack; // 0x18
	private static DelegateBridge __Hotfix0_OnClickBackBtn; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x327fabc VA: 0x7595897abc
	public override IStateBean GetCacheBean() { }
	// RVA: 0x327fb24 VA: 0x7595897b24
	protected override Void OnEnter() { }
	// RVA: 0x327fc64 VA: 0x7595897c64
	private Void _InitIfNot() { }
	// RVA: 0x327fe74 VA: 0x7595897e74
	private Void _ConsumeLocalTrack(String groupId) { }
	// RVA: 0x327ffd0 VA: 0x7595897fd0
	public Void OnClickBackBtn() { }
	// RVA: 0x32800d8 VA: 0x75958980d8
	public Void .ctor() { }
	// RVA: 0x3280234 VA: 0x7595898234
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```