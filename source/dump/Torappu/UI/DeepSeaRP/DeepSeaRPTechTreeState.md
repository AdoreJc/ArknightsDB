# DeepSeaRPTechTreeState

**Namespace:** `Torappu.UI.DeepSeaRP`


## Fields

- `RectTransform _rectBack`

- `DeepSeaRPTechTreeView _view`

- `Boolean m_hasInited`

- `DeepSeaRPTechTreeStateBean m_stateBean`

- `Coroutine m_coSavedLogoShow`

- `Boolean m_isSavedShowing`


## Methods

- `Void _TryTriggerAVG()`

- `IEnumerator _TriggerAVGCoro()`

- `Void EventOnExit()`

- `Void _InitIfNot()`

- `Void _SaveEdits()`

- `Void _OnSaveCompleted()`

- `IEnumerator _CoShowSavedLogo()`

- `Void _StartCoShowSavedLogo()`

- `Void _ClearCoShowSavedLogo()`

- `Void _BreakSavedLogoShowing()`

- `Void _ActiveTechNode(String)`

- `Void _OnActiveTechNodeCompleted(String)`

- `Void _SetTechNode(String)`

- `Void _UnsetTechNode(String)`

- `Void _SwitchTechBranch(String)`

- `Void _TryChangeBranches(Action)`

- `Void _TryActiveTechTreeNode(String, Action`1)`

- `Void <EventOnExit>b__11_0()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.DeepSeaRP
public class DeepSeaRPTechTreeState : PopupFadeState
{
	private RectTransform _rectBack; // 0x70
	private DeepSeaRPTechTreeView _view; // 0x78
	private Boolean m_hasInited; // 0x80
	private DeepSeaRPTechTreeStateBean m_stateBean; // 0x88
	private const Single SAVED_LOGO_SHOWING_DUR; // 0x0
	private Coroutine m_coSavedLogoShow; // 0x90
	private Boolean m_isSavedShowing; // 0x98
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__TryTriggerAVG; // 0x10
	private static DelegateBridge __Hotfix0__TriggerAVGCoro; // 0x18
	private static DelegateBridge __Hotfix0_EventOnExit; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0__SaveEdits; // 0x30
	private static DelegateBridge __Hotfix0__OnSaveCompleted; // 0x38
	private static DelegateBridge __Hotfix0__CoShowSavedLogo; // 0x40
	private static DelegateBridge __Hotfix0__StartCoShowSavedLogo; // 0x48
	private static DelegateBridge __Hotfix0__ClearCoShowSavedLogo; // 0x50
	private static DelegateBridge __Hotfix0__BreakSavedLogoShowing; // 0x58
	private static DelegateBridge __Hotfix0__ActiveTechNode; // 0x60
	private static DelegateBridge __Hotfix0__OnActiveTechNodeCompleted; // 0x68
	private static DelegateBridge __Hotfix0__SetTechNode; // 0x70
	private static DelegateBridge __Hotfix0__UnsetTechNode; // 0x78
	private static DelegateBridge __Hotfix0__SwitchTechBranch; // 0x80
	private static DelegateBridge __Hotfix0__TryChangeBranches; // 0x88
	private static DelegateBridge __Hotfix0__TryActiveTechTreeNode; // 0x90
	private static DelegateBridge _c__Hotfix0_ctor; // 0x98


	// RVA: 0x29e1c54 VA: 0x7594ff9c54
	public override IStateBean GetCacheBean() { }
	// RVA: 0x29e1cbc VA: 0x7594ff9cbc
	protected override Void OnEnter() { }
	// RVA: 0x29e229c VA: 0x7594ffa29c
	private Void _TryTriggerAVG() { }
	// RVA: 0x29e24c0 VA: 0x7594ffa4c0
	private IEnumerator _TriggerAVGCoro() { }
	// RVA: 0x29e2584 VA: 0x7594ffa584
	public Void EventOnExit() { }
	// RVA: 0x29e1e18 VA: 0x7594ff9e18
	private Void _InitIfNot() { }
	// RVA: 0x29e2bb0 VA: 0x7594ffabb0
	private Void _SaveEdits() { }
	// RVA: 0x29e2c88 VA: 0x7594ffac88
	private Void _OnSaveCompleted() { }
	// RVA: 0x29e3280 VA: 0x7594ffb280
	private IEnumerator _CoShowSavedLogo() { }
	// RVA: 0x29e3198 VA: 0x7594ffb198
	private Void _StartCoShowSavedLogo() { }
	// RVA: 0x29e30a8 VA: 0x7594ffb0a8
	private Void _ClearCoShowSavedLogo() { }
	// RVA: 0x29e3354 VA: 0x7594ffb354
	private Void _BreakSavedLogoShowing() { }
	// RVA: 0x29e34bc VA: 0x7594ffb4bc
	private Void _ActiveTechNode(String techId) { }
	// RVA: 0x29e389c VA: 0x7594ffb89c
	private Void _OnActiveTechNodeCompleted(String techId) { }
	// RVA: 0x29e3aa4 VA: 0x7594ffbaa4
	private Void _SetTechNode(String techId) { }
	// RVA: 0x29e3cf8 VA: 0x7594ffbcf8
	private Void _UnsetTechNode(String techId) { }
	// RVA: 0x29e3dfc VA: 0x7594ffbdfc
	private Void _SwitchTechBranch(String techId) { }
	// RVA: 0x29e2d08 VA: 0x7594ffad08
	private Void _TryChangeBranches(Action onComplete) { }
	// RVA: 0x29e358c VA: 0x7594ffb58c
	private Void _TryActiveTechTreeNode(String treeId, Action`1 onComplete) { }
	// RVA: 0x29e43a0 VA: 0x7594ffc3a0
	public Void .ctor() { }
	// RVA: 0x29e44f8 VA: 0x7594ffc4f8
	private Void <EventOnExit>b__11_0() { }
	// RVA: 0x29e4518 VA: 0x7594ffc518
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```