# Act5D1RuneMissionState

**Namespace:** `Torappu.Activity.Act5D1`


## Fields

- `Act5D1RuneMissionStateBean _stateBean`

- `Act5D1RuneMissionPanel _urgentMission`

- `Act5D1RuneMissionPanel _permanentMissison`

- `Boolean m_cannotUseBenefit`


## Methods

- `Void showRuneDetail(List`1, Boolean)`

- `Void <OnEnter>b__6_0()`

- `Void <RegisterToDataListener>b__8_0(IStateBean)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D1
public class Act5D1RuneMissionState : PopupFloatState
{
	private Act5D1RuneMissionStateBean _stateBean; // 0x70
	private Act5D1RuneMissionPanel _urgentMission; // 0x78
	private Act5D1RuneMissionPanel _permanentMissison; // 0x80
	private List`1 m_tempRunesForShow; // 0x88
	private Boolean m_cannotUseBenefit; // 0x90
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_showRuneDetail; // 0x10
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x31d3e18 VA: 0x75957ebe18
	public override IStateBean GetCacheBean() { }
	// RVA: 0x31d3e80 VA: 0x75957ebe80
	protected override Void OnEnter() { }
	// RVA: 0x31d2f7c VA: 0x75957eaf7c
	public Void showRuneDetail(List`1 runes, Boolean cannotUseBenefit) { }
	// RVA: 0x31d3f5c VA: 0x75957ebf5c
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x31d40d4 VA: 0x75957ec0d4
	public Void .ctor() { }
	// RVA: 0x31d4144 VA: 0x75957ec144
	private Void <OnEnter>b__6_0() { }
	// RVA: 0x31d43dc VA: 0x75957ec3dc
	private Void <RegisterToDataListener>b__8_0(IStateBean stateBean) { }
	// RVA: 0x31d4548 VA: 0x75957ec548
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x31d4550 VA: 0x75957ec550
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```