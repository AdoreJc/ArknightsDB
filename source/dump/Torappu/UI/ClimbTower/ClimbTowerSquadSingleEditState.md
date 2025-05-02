# ClimbTowerSquadSingleEditState

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `ClimbTowerSquadSingleEditView _view`

- `CharSelectAttrController _attrController`

- `ClimbTowerMenuButton _menuButtonPrefab`

- `RectTransform _backBtnRt`

- `UIAnimationLocation _attrPanelEnterAnim`

- `ClimbTowerSquadSingleEditStateBean m_stateBean`

- `Boolean m_hasInited`

- `MenuAdapter m_menuAdapter`

- `AnimationSwitchTween m_attrEnterSwitchTween`


## Methods

- `Void _NavToEditState(IStateBean)`

- `Void _InitIfNot()`

- `Void _OnCharSelect(Int32)`

- `Void _OnProfessionClicked(ProfessionCategory)`

- `Void _OnConfirmBtnClicked()`

- `Void EventOnAttrTabClick(CharAttrTabType)`

- `Void EventOnSkillSelect(String)`

- `Void EventOnBranchSelect(String)`

- `IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext)`

- `Void <>xLuaBaseProxy_ShowImmediately(TransactionContext)`

- `IEnumerator <>xLuaBaseProxy_HideCoroutine(TransactionContext)`

- `Void <>xLuaBaseProxy_HideImmediately(TransactionContext)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerSquadSingleEditState : PopupFadeState
{
	private ClimbTowerSquadSingleEditView _view; // 0x70
	private CharSelectAttrController _attrController; // 0x78
	private CharSelectAttrTabItem[] _tabItems; // 0x80
	private ClimbTowerMenuButton _menuButtonPrefab; // 0x88
	private RectTransform _backBtnRt; // 0x90
	private UIAnimationLocation _attrPanelEnterAnim; // 0x98
	private ClimbTowerSquadSingleEditStateBean m_stateBean; // 0xa8
	private Boolean m_hasInited; // 0xb0
	private MenuAdapter m_menuAdapter; // 0xb8
	private AnimationSwitchTween m_attrEnterSwitchTween; // 0xc0
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x0
	private static DelegateBridge __Hotfix0_ShowImmediately; // 0x8
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x10
	private static DelegateBridge __Hotfix0_HideImmediately; // 0x18
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x20
	private static DelegateBridge __Hotfix0_OnEnter; // 0x28
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x30
	private static DelegateBridge __Hotfix0__NavToEditState; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x40
	private static DelegateBridge __Hotfix0__OnCharSelect; // 0x48
	private static DelegateBridge __Hotfix0__OnProfessionClicked; // 0x50
	private static DelegateBridge __Hotfix0__OnConfirmBtnClicked; // 0x58
	private static DelegateBridge __Hotfix0_EventOnAttrTabClick; // 0x60
	private static DelegateBridge __Hotfix0_EventOnSkillSelect; // 0x68
	private static DelegateBridge __Hotfix0_EventOnBranchSelect; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78


	// RVA: 0x2cc9b8c VA: 0x75952e1b8c
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x2cc9d04 VA: 0x75952e1d04
	protected override Void ShowImmediately(TransactionContext context) { }
	// RVA: 0x2cc9e1c VA: 0x75952e1e1c
	protected override IEnumerator HideCoroutine(TransactionContext context) { }
	// RVA: 0x2cc9f94 VA: 0x75952e1f94
	protected override Void HideImmediately(TransactionContext context) { }
	// RVA: 0x2cca0ac VA: 0x75952e20ac
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2cca114 VA: 0x75952e2114
	protected override Void OnEnter() { }
	// RVA: 0x2cca910 VA: 0x75952e2910
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2ccaa88 VA: 0x75952e2a88
	private Void _NavToEditState(IStateBean stateBean) { }
	// RVA: 0x2cca364 VA: 0x75952e2364
	private Void _InitIfNot() { }
	// RVA: 0x2ccac3c VA: 0x75952e2c3c
	private Void _OnCharSelect(Int32 cardId) { }
	// RVA: 0x2ccb108 VA: 0x75952e3108
	private Void _OnProfessionClicked(ProfessionCategory profession) { }
	// RVA: 0x2ccb24c VA: 0x75952e324c
	private Void _OnConfirmBtnClicked() { }
	// RVA: 0x2ccb568 VA: 0x75952e3568
	public Void EventOnAttrTabClick(CharAttrTabType tabType) { }
	// RVA: 0x2ccb654 VA: 0x75952e3654
	public Void EventOnSkillSelect(String skillId) { }
	// RVA: 0x2ccb970 VA: 0x75952e3970
	public Void EventOnBranchSelect(String equipId) { }
	// RVA: 0x2ccbc40 VA: 0x75952e3c40
	public Void .ctor() { }
	// RVA: 0x2ccbdd4 VA: 0x75952e3dd4
	private IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext P0) { }
	// RVA: 0x2ccbdfc VA: 0x75952e3dfc
	private Void <>xLuaBaseProxy_ShowImmediately(TransactionContext P0) { }
	// RVA: 0x2ccbe24 VA: 0x75952e3e24
	private IEnumerator <>xLuaBaseProxy_HideCoroutine(TransactionContext P0) { }
	// RVA: 0x2ccbe4c VA: 0x75952e3e4c
	private Void <>xLuaBaseProxy_HideImmediately(TransactionContext P0) { }
	// RVA: 0x2ccbe74 VA: 0x75952e3e74
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2ccbe7c VA: 0x75952e3e7c
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```