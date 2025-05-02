# UIShowCardState

**Namespace:** `Torappu.Battle.UI`


## Fields

- `UICardList _cardList`


## Properties

- `UICharacterInfoPanel characterInfo`

- `UICardList cardList`


## Methods

- `UICharacterInfoPanel get_characterInfo()`

- `UICardList get_cardList()`

- `Void _OnCardToggled(Object)`

- `Void _OnTileClicked(Tile)`

- `Void <OnInit>b__10_0(Object)`

- `Boolean <>xLuaBaseProxy_get_enableSpeedSwitch()`

- `Void <>xLuaBaseProxy_OnInit(UIStateEnum, UIStateMachine)`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`

- `Void <>xLuaBaseProxy_OnExit(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIShowCardState : UIStateNode
{
	private UICardList _cardList; // 0x20
	private static DelegateBridge __Hotfix0_get_characterInfo; // 0x0
	private static DelegateBridge __Hotfix0_get_cardList; // 0x8
	private static DelegateBridge __Hotfix0_get_uiState; // 0x10
	private static DelegateBridge __Hotfix0_get_enableSpeedSwitch; // 0x18
	private static DelegateBridge __Hotfix0__OnCardToggled; // 0x20
	private static DelegateBridge __Hotfix0_OnInit; // 0x28
	private static DelegateBridge __Hotfix0_OnEnter; // 0x30
	private static DelegateBridge __Hotfix0_OnTick; // 0x38
	private static DelegateBridge __Hotfix0_OnExit; // 0x40
	private static DelegateBridge __Hotfix0__OnTileClicked; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	private UICharacterInfoPanel characterInfo { get; }
	private UICardList cardList { get; }
	public override UIStateEnum uiState { get; }
	public override Boolean enableSpeedSwitch { get; }

	// RVA: 0x205c304 VA: 0x7594674304
	private UICharacterInfoPanel get_characterInfo() { }
	// RVA: 0x205c390 VA: 0x7594674390
	private UICardList get_cardList() { }
	// RVA: 0x205c3f8 VA: 0x75946743f8
	public override UIStateEnum get_uiState() { }
	// RVA: 0x205c460 VA: 0x7594674460
	public override Boolean get_enableSpeedSwitch() { }
	// RVA: 0x205c4c4 VA: 0x75946744c4
	private Void _OnCardToggled(Object _) { }
	// RVA: 0x205c720 VA: 0x7594674720
	public override Void OnInit(UIStateEnum state, UIStateMachine stateMachine) { }
	// RVA: 0x205c8cc VA: 0x75946748cc
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x205cb70 VA: 0x7594674b70
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x205cda4 VA: 0x7594674da4
	public override Void OnExit(Int32 nextState) { }
	// RVA: 0x205ce8c VA: 0x7594674e8c
	private Void _OnTileClicked(Tile tile) { }
	// RVA: 0x205d104 VA: 0x7594675104
	public Void .ctor() { }
	// RVA: 0x205d174 VA: 0x7594675174
	private Void <OnInit>b__10_0(Object tile) { }
	// RVA: 0x205d1f4 VA: 0x75946751f4
	private Boolean <>xLuaBaseProxy_get_enableSpeedSwitch() { }
	// RVA: 0x205d1fc VA: 0x75946751fc
	private Void <>xLuaBaseProxy_OnInit(UIStateEnum P0, UIStateMachine P1) { }
	// RVA: 0x205d204 VA: 0x7594675204
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x205d20c VA: 0x759467520c
	private Void <>xLuaBaseProxy_OnExit(Int32 P0) { }
}
```