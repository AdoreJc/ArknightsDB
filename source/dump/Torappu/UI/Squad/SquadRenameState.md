# SquadRenameState

**Namespace:** `Torappu.UI.Squad`


## Fields

- `SquadHomeStateBean _statebean`

- `InputField _inputName`


## Methods

- `Void BackToState()`

- `Void SaveSquadName()`

- `Void _SaveSquadName()`

- `Void <_SaveSquadName>b__6_0(SquadRenameResponse)`

- `Void <_SaveSquadName>b__6_1()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Squad
public class SquadRenameState : PopupFloatState
{
	private SquadHomeStateBean _statebean; // 0x70
	private InputField _inputName; // 0x78
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_BackToState; // 0x10
	private static DelegateBridge __Hotfix0_SaveSquadName; // 0x18
	private static DelegateBridge __Hotfix0__SaveSquadName; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x238b37c VA: 0x75949a337c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x238b3e4 VA: 0x75949a33e4
	protected override Void OnEnter() { }
	// RVA: 0x238b550 VA: 0x75949a3550
	public Void BackToState() { }
	// RVA: 0x238b5c4 VA: 0x75949a35c4
	public Void SaveSquadName() { }
	// RVA: 0x238b62c VA: 0x75949a362c
	private Void _SaveSquadName() { }
	// RVA: 0x238b890 VA: 0x75949a3890
	public Void .ctor() { }
	// RVA: 0x238b900 VA: 0x75949a3900
	private Void <_SaveSquadName>b__6_0(SquadRenameResponse response) { }
	// RVA: 0x238b990 VA: 0x75949a3990
	private Void <_SaveSquadName>b__6_1() { }
	// RVA: 0x238b9a0 VA: 0x75949a39a0
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```