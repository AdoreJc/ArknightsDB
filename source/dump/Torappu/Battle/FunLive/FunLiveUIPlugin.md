# FunLiveUIPlugin

**Namespace:** `Torappu.Battle.FunLive`


## Fields

- `FunLiveUIBattleTopBar _funliveTopbarStatus`

- `Transform _battleAccomplishedPanel`

- `UIBattleBlurPanel _blurPanel`

- `FunLiveUIBattleTopBar m_curTopbarStatus`

- `FunLiveGameMode m_gameMode`

- `Int32 m_photoTotalCnt`


## Properties

- `Int32 PhotoTotalCnt`


## Methods

- `Int32 get_PhotoTotalCnt()`

- `Void _HookUITopBar()`

- `Void OnPhotoLibraryButtonClicked()`

- `Void CloseSystemMenuPanel()`

- `Void ClosePhotoLibraryPanel()`

- `Void FinishGameDirectly()`

- `Void FinishGameWhenTimeOut()`

- `Void <>xLuaBaseProxy_OnGameInit(Options)`

- `Void <>xLuaBaseProxy_OnInitStateMachine(UIStateMachine)`

- `Void <>xLuaBaseProxy_OnCreate(UIController)`

- `Void <>xLuaBaseProxy_UpdateGameInfo()`

- `Void <>xLuaBaseProxy_OnUIStateChanged(IUIStateNode)`

- `Boolean <>xLuaBaseProxy_HookBattleSystemMenuSwitch()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.FunLive
public class FunLiveUIPlugin : Plugin
{
	public static readonly UIStateEnum UI_STATE_SYSTEM_MENU; // 0x0
	public static readonly UIStateEnum UI_STATE_PHOTO_LIBRARY; // 0x4
	public static readonly UIStateEnum UI_STATE_ACCOMPLISHED; // 0x8
	private FunLiveUIBattleTopBar _funliveTopbarStatus; // 0x28
	private Transform _battleAccomplishedPanel; // 0x30
	private UIBattleBlurPanel _blurPanel; // 0x38
	private UIStateNode[] _states; // 0x40
	private FunLiveUIBattleTopBar m_curTopbarStatus; // 0x48
	private FunLiveGameMode m_gameMode; // 0x50
	private Int32 m_photoTotalCnt; // 0x58
	private static DelegateBridge __Hotfix0_get_PhotoTotalCnt; // 0x10
	private static DelegateBridge __Hotfix0_OnGameInit; // 0x18
	private static DelegateBridge __Hotfix0_OnInitStateMachine; // 0x20
	private static DelegateBridge __Hotfix0_OnCreate; // 0x28
	private static DelegateBridge __Hotfix0_UpdateGameInfo; // 0x30
	private static DelegateBridge __Hotfix0_OnUIStateChanged; // 0x38
	private static DelegateBridge __Hotfix0_HookBattleSystemMenuSwitch; // 0x40
	private static DelegateBridge __Hotfix0__HookUITopBar; // 0x48
	private static DelegateBridge __Hotfix0_OnPhotoLibraryButtonClicked; // 0x50
	private static DelegateBridge __Hotfix0_CloseSystemMenuPanel; // 0x58
	private static DelegateBridge __Hotfix0_ClosePhotoLibraryPanel; // 0x60
	private static DelegateBridge __Hotfix0_FinishGameDirectly; // 0x68
	private static DelegateBridge __Hotfix0_FinishGameWhenTimeOut; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public Int32 PhotoTotalCnt { get; }

	// RVA: 0x1c5c1b8 VA: 0x75942741b8
	public Int32 get_PhotoTotalCnt() { }
	// RVA: 0x1c5e4e8 VA: 0x75942764e8
	public override Void OnGameInit(Options levelOptions) { }
	// RVA: 0x1c5e7c4 VA: 0x75942767c4
	public override Void OnInitStateMachine(UIStateMachine stateMachine) { }
	// RVA: 0x1c5e908 VA: 0x7594276908
	public override Void OnCreate(UIController uiController) { }
	// RVA: 0x1c5e9c8 VA: 0x75942769c8
	public override Void UpdateGameInfo() { }
	// RVA: 0x1c5eabc VA: 0x7594276abc
	public override Void OnUIStateChanged(IUIStateNode stateNode) { }
	// RVA: 0x1c5ec18 VA: 0x7594276c18
	public override Boolean HookBattleSystemMenuSwitch() { }
	// RVA: 0x1c5e648 VA: 0x7594276648
	private Void _HookUITopBar() { }
	// RVA: 0x1c5ecf4 VA: 0x7594276cf4
	public Void OnPhotoLibraryButtonClicked() { }
	// RVA: 0x1c5e300 VA: 0x7594276300
	public Void CloseSystemMenuPanel() { }
	// RVA: 0x1c5dcc4 VA: 0x7594275cc4
	public Void ClosePhotoLibraryPanel() { }
	// RVA: 0x1c5e3b0 VA: 0x75942763b0
	public Void FinishGameDirectly() { }
	// RVA: 0x1c5ce04 VA: 0x7594274e04
	public Void FinishGameWhenTimeOut() { }
	// RVA: 0x1c5ee10 VA: 0x7594276e10
	public Void .ctor() { }
	// RVA: 0x1c5eecc VA: 0x7594276ecc
	private static Void .cctor() { }
	// RVA: 0x1c5ef24 VA: 0x7594276f24
	private Void <>xLuaBaseProxy_OnGameInit(Options P0) { }
	// RVA: 0x1c5ef2c VA: 0x7594276f2c
	private Void <>xLuaBaseProxy_OnInitStateMachine(UIStateMachine P0) { }
	// RVA: 0x1c5ef34 VA: 0x7594276f34
	private Void <>xLuaBaseProxy_OnCreate(UIController P0) { }
	// RVA: 0x1c5ef3c VA: 0x7594276f3c
	private Void <>xLuaBaseProxy_UpdateGameInfo() { }
	// RVA: 0x1c5ef44 VA: 0x7594276f44
	private Void <>xLuaBaseProxy_OnUIStateChanged(IUIStateNode P0) { }
	// RVA: 0x1c5ef4c VA: 0x7594276f4c
	private Boolean <>xLuaBaseProxy_HookBattleSystemMenuSwitch() { }
}
```