# UICharacterMenuState

**Namespace:** `Torappu.Battle.UI`


## Fields

- `UICharacterMenuPanel _characterMenu`

- `Tile m_rootTile`

- `IUICharacterMenuPanel m_displayedMenuPanel`

- `Boolean m_slowMotionIsSet`


## Properties

- `UICharacterInfoPanel characterInfo`

- `UICharacterMenuPanel characterMenu`

- `Character character`


## Methods

- `UICharacterInfoPanel get_characterInfo()`

- `UICharacterMenuPanel get_characterMenu()`

- `Character get_character()`

- `Void Show(Character)`

- `Void OnCancelled()`

- `Void _OnBottomMaskClicked(Object)`

- `Void ShowCharacterMenu(Character)`

- `Void HideCharacterMenu()`

- `Void _DoShowCharacterMenu(Character)`

- `Void _DoHideCharacterMenu()`

- `Boolean <>xLuaBaseProxy_get_enableSpeedSwitch()`

- `Boolean <>xLuaBaseProxy_get_enableShowRange()`

- `Boolean <>xLuaBaseProxy_get_enablePerspectiveCanvas()`

- `Void <>xLuaBaseProxy_OnInit(UIStateEnum, UIStateMachine)`

- `Void <>xLuaBaseProxy_OnEnter(Int32)`

- `Void <>xLuaBaseProxy_OnExit(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UICharacterMenuState : UIStateNode
{
	private UICharacterMenuPanel _characterMenu; // 0x20
	private Tile m_rootTile; // 0x28
	private ObjectPtr`1 m_character; // 0x30
	private IUICharacterMenuPanel m_displayedMenuPanel; // 0x40
	private Boolean m_slowMotionIsSet; // 0x48
	private static DelegateBridge __Hotfix0_get_characterInfo; // 0x0
	private static DelegateBridge __Hotfix0_get_uiState; // 0x8
	private static DelegateBridge __Hotfix0_get_enableSpeedSwitch; // 0x10
	private static DelegateBridge __Hotfix0_get_enableShowRange; // 0x18
	private static DelegateBridge __Hotfix0_get_enablePerspectiveCanvas; // 0x20
	private static DelegateBridge __Hotfix0_get_characterMenu; // 0x28
	private static DelegateBridge __Hotfix0_get_character; // 0x30
	private static DelegateBridge __Hotfix0_Show; // 0x38
	private static DelegateBridge __Hotfix0_OnCancelled; // 0x40
	private static DelegateBridge __Hotfix0__OnBottomMaskClicked; // 0x48
	private static DelegateBridge __Hotfix0_OnInit; // 0x50
	private static DelegateBridge __Hotfix0_OnEnter; // 0x58
	private static DelegateBridge __Hotfix0_OnTick; // 0x60
	private static DelegateBridge __Hotfix0_OnExit; // 0x68
	private static DelegateBridge __Hotfix0_ShowCharacterMenu; // 0x70
	private static DelegateBridge __Hotfix0_HideCharacterMenu; // 0x78
	private static DelegateBridge __Hotfix0__DoShowCharacterMenu; // 0x80
	private static DelegateBridge __Hotfix0__DoHideCharacterMenu; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90

	private UICharacterInfoPanel characterInfo { get; }
	public override UIStateEnum uiState { get; }
	public override Boolean enableSpeedSwitch { get; }
	public override Boolean enableShowRange { get; }
	public override Boolean enablePerspectiveCanvas { get; }
	public UICharacterMenuPanel characterMenu { get; }
	public Character character { get; }

	// RVA: 0x2058700 VA: 0x7594670700
	private UICharacterInfoPanel get_characterInfo() { }
	// RVA: 0x205878c VA: 0x759467078c
	public override UIStateEnum get_uiState() { }
	// RVA: 0x20587f4 VA: 0x75946707f4
	public override Boolean get_enableSpeedSwitch() { }
	// RVA: 0x2058858 VA: 0x7594670858
	public override Boolean get_enableShowRange() { }
	// RVA: 0x20588bc VA: 0x75946708bc
	public override Boolean get_enablePerspectiveCanvas() { }
	// RVA: 0x2058924 VA: 0x7594670924
	public UICharacterMenuPanel get_characterMenu() { }
	// RVA: 0x205898c VA: 0x759467098c
	public Character get_character() { }
	// RVA: 0x2058a0c VA: 0x7594670a0c
	public Void Show(Character character) { }
	// RVA: 0x2058b54 VA: 0x7594670b54
	public Void OnCancelled() { }
	// RVA: 0x2058bc0 VA: 0x7594670bc0
	private Void _OnBottomMaskClicked(Object arg) { }
	// RVA: 0x2058c88 VA: 0x7594670c88
	public override Void OnInit(UIStateEnum state, UIStateMachine stateMachine) { }
	// RVA: 0x2058dec VA: 0x7594670dec
	public override Void OnEnter(Int32 lastState) { }
	// RVA: 0x20591d4 VA: 0x75946711d4
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x20592b0 VA: 0x75946712b0
	public override Void OnExit(Int32 nextState) { }
	// RVA: 0x2059560 VA: 0x7594671560
	public Void ShowCharacterMenu(Character character) { }
	// RVA: 0x20595e0 VA: 0x75946715e0
	public Void HideCharacterMenu() { }
	// RVA: 0x205903c VA: 0x759467103c
	private Void _DoShowCharacterMenu(Character character) { }
	// RVA: 0x2059458 VA: 0x7594671458
	private Void _DoHideCharacterMenu() { }
	// RVA: 0x2059648 VA: 0x7594671648
	public Void .ctor() { }
	// RVA: 0x20596b8 VA: 0x75946716b8
	private Boolean <>xLuaBaseProxy_get_enableSpeedSwitch() { }
	// RVA: 0x20596c0 VA: 0x75946716c0
	private Boolean <>xLuaBaseProxy_get_enableShowRange() { }
	// RVA: 0x20596c8 VA: 0x75946716c8
	private Boolean <>xLuaBaseProxy_get_enablePerspectiveCanvas() { }
	// RVA: 0x20596d0 VA: 0x75946716d0
	private Void <>xLuaBaseProxy_OnInit(UIStateEnum P0, UIStateMachine P1) { }
	// RVA: 0x20596d8 VA: 0x75946716d8
	private Void <>xLuaBaseProxy_OnEnter(Int32 P0) { }
	// RVA: 0x20596e0 VA: 0x75946716e0
	private Void <>xLuaBaseProxy_OnExit(Int32 P0) { }
}
```