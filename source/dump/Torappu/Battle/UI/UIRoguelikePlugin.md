# UIRoguelikePlugin

**Namespace:** `Torappu.Battle.UI`


## Fields

- `UIAtlasObject _atlas`

- `UIAtlasImage _icon`

- `Text _title`

- `Single _fadeinDuration`

- `UIDiceToastPanel _toastDicePanelPrefab`

- `CanvasGroup m_canvasGroup`

- `UIDiceToastPanel m_diceToastPanel`


## Methods

- `Void OnPanelClick()`

- `Void <>xLuaBaseProxy_OnCreate(UIController)`

- `Void <>xLuaBaseProxy_OnGameInit(Options)`

- `Boolean <>xLuaBaseProxy_HookGameReadyStateSwitch()`

- `RectTransform <>xLuaBaseProxy_HookBattleFailedPanelInit()`

- `Boolean <>xLuaBaseProxy_HookConfirmFinish(Action)`

- `Boolean <>xLuaBaseProxy_HookBattleFailedPanelShow()`

- `Boolean <>xLuaBaseProxy_HookBattleFailedPanelHide()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIRoguelikePlugin : Plugin
{
	private UIAtlasObject _atlas; // 0x28
	private UIAtlasImage _icon; // 0x30
	private Text _title; // 0x38
	private List`1 _textHints; // 0x40
	private Single _fadeinDuration; // 0x48
	private UIDiceToastPanel _toastDicePanelPrefab; // 0x50
	private readonly Int32 HINT_COUNT; // 0x58
	private readonly String HINT_PREFIX; // 0x60
	private CanvasGroup m_canvasGroup; // 0x68
	private UIDiceToastPanel m_diceToastPanel; // 0x70
	private static DelegateBridge __Hotfix0_OnCreate; // 0x0
	private static DelegateBridge __Hotfix0_OnGameInit; // 0x8
	private static DelegateBridge __Hotfix0_HookGameReadyStateSwitch; // 0x10
	private static DelegateBridge __Hotfix0_HookBattleFailedPanelInit; // 0x18
	private static DelegateBridge __Hotfix0_HookConfirmFinish; // 0x20
	private static DelegateBridge __Hotfix0_HookBattleFailedPanelShow; // 0x28
	private static DelegateBridge __Hotfix0_HookBattleFailedPanelHide; // 0x30
	private static DelegateBridge __Hotfix0_OnPanelClick; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x20732b8 VA: 0x759468b2b8
	public override Void OnCreate(UIController uiController) { }
	// RVA: 0x20733f0 VA: 0x759468b3f0
	public override Void OnGameInit(Options levelOptions) { }
	// RVA: 0x20734e4 VA: 0x759468b4e4
	public override Boolean HookGameReadyStateSwitch() { }
	// RVA: 0x20735b8 VA: 0x759468b5b8
	public override RectTransform HookBattleFailedPanelInit() { }
	// RVA: 0x207368c VA: 0x759468b68c
	public override Boolean HookConfirmFinish(Action finishCallback) { }
	// RVA: 0x2073810 VA: 0x759468b810
	public override Boolean HookBattleFailedPanelShow() { }
	// RVA: 0x2073f0c VA: 0x759468bf0c
	public override Boolean HookBattleFailedPanelHide() { }
	// RVA: 0x2073f94 VA: 0x759468bf94
	public Void OnPanelClick() { }
	// RVA: 0x2074064 VA: 0x759468c064
	public Void .ctor() { }
	// RVA: 0x2074114 VA: 0x759468c114
	private Void <>xLuaBaseProxy_OnCreate(UIController P0) { }
	// RVA: 0x2074118 VA: 0x759468c118
	private Void <>xLuaBaseProxy_OnGameInit(Options P0) { }
	// RVA: 0x207411c VA: 0x759468c11c
	private Boolean <>xLuaBaseProxy_HookGameReadyStateSwitch() { }
	// RVA: 0x2074120 VA: 0x759468c120
	private RectTransform <>xLuaBaseProxy_HookBattleFailedPanelInit() { }
	// RVA: 0x2074124 VA: 0x759468c124
	private Boolean <>xLuaBaseProxy_HookConfirmFinish(Action P0) { }
	// RVA: 0x2074128 VA: 0x759468c128
	private Boolean <>xLuaBaseProxy_HookBattleFailedPanelShow() { }
	// RVA: 0x207412c VA: 0x759468c12c
	private Boolean <>xLuaBaseProxy_HookBattleFailedPanelHide() { }
}
```