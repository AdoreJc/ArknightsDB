# UIPlayingState

**Namespace:** `Torappu.Battle.UI`


## Methods

- `Void _OnCardToggled(Object)`

- `Void _OnTileClicked(Tile)`

- `Void <OnInit>b__2_0(Object)`

- `Void <>xLuaBaseProxy_OnInit(UIStateEnum, UIStateMachine)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIPlayingState : UIStateNode
{
	private static DelegateBridge __Hotfix0_get_uiState; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0_OnTick; // 0x10
	private static DelegateBridge __Hotfix0__OnCardToggled; // 0x18
	private static DelegateBridge __Hotfix0__OnTileClicked; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override UIStateEnum uiState { get; }

	// RVA: 0x205bce0 VA: 0x7594673ce0
	public override UIStateEnum get_uiState() { }
	// RVA: 0x205bd48 VA: 0x7594673d48
	public override Void OnInit(UIStateEnum state, UIStateMachine stateMachine) { }
	// RVA: 0x205bef4 VA: 0x7594673ef4
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x205bf6c VA: 0x7594673f6c
	private Void _OnCardToggled(Object card) { }
	// RVA: 0x205c038 VA: 0x7594674038
	private Void _OnTileClicked(Tile tile) { }
	// RVA: 0x205c20c VA: 0x759467420c
	public Void .ctor() { }
	// RVA: 0x205c27c VA: 0x759467427c
	private Void <OnInit>b__2_0(Object tile) { }
	// RVA: 0x205c2fc VA: 0x75946742fc
	private Void <>xLuaBaseProxy_OnInit(UIStateEnum P0, UIStateMachine P1) { }
}
```