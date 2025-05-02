# FunLiveUIPhotoLibraryState

**Namespace:** `Torappu.Battle.FunLive`


## Fields

- `FunLiveUIPlugin m_plugin`

- `FunLiveUIBattlePhotoLibraryPanel m_panel`


## Methods

- `Void ClosePhotoLibraryPanel()`

- `Void <>xLuaBaseProxy_OnInit(UIStateEnum, UIStateMachine)`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`

- `Void <>xLuaBaseProxy_OnExit(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.FunLive
public class FunLiveUIPhotoLibraryState : CommonUIStateNode
{
	private FunLiveUIPlugin m_plugin; // 0x50
	private FunLiveUIBattlePhotoLibraryPanel m_panel; // 0x58
	private List`1 m_eventList; // 0x60
	private static DelegateBridge __Hotfix0_get_uiState; // 0x0
	private static DelegateBridge __Hotfix0_OnTick; // 0x8
	private static DelegateBridge __Hotfix0_OnInit; // 0x10
	private static DelegateBridge __Hotfix0_OnEnter; // 0x18
	private static DelegateBridge __Hotfix0_OnExit; // 0x20
	private static DelegateBridge __Hotfix0_ClosePhotoLibraryPanel; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public override UIStateEnum uiState { get; }

	// RVA: 0x1c5d758 VA: 0x7594275758
	public override UIStateEnum get_uiState() { }
	// RVA: 0x1c5d7ec VA: 0x75942757ec
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1c5d864 VA: 0x7594275864
	public override Void OnInit(UIStateEnum state, UIStateMachine stateMachine) { }
	// RVA: 0x1c5d99c VA: 0x759427599c
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x1c5dbd8 VA: 0x7594275bd8
	public override Void OnExit(Int32 nextState) { }
	// RVA: 0x1c5c2a0 VA: 0x75942742a0
	public Void ClosePhotoLibraryPanel() { }
	// RVA: 0x1c5dd74 VA: 0x7594275d74
	public Void .ctor() { }
	// RVA: 0x1c5dde4 VA: 0x7594275de4
	private Void <>xLuaBaseProxy_OnInit(UIStateEnum P0, UIStateMachine P1) { }
	// RVA: 0x1c5ddec VA: 0x7594275dec
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x1c5ddf4 VA: 0x7594275df4
	private Void <>xLuaBaseProxy_OnExit(Int32 P0) { }
}
```