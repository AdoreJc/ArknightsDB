# RoguelikeFocusState

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RectTransform _panelTopMenu`

- `RectTransform _panelRaycastBlock`

- `Transform _container`

- `RoguelikeFocusView m_view`

- `Boolean m_inited`

- `ShowSwitchTween m_showSwitchTween`

- `MenuAdapter m_menuAdapter`

- `ForwardOutTransition m_forwardOutTrans`

- `GameObject m_effectPrefab`

- `GameObject m_effectInst`


## Methods

- `RoguelikeFocusView _InitFocusView(String)`

- `Void _InitIfNot()`

- `Void _SetEffectVisible(Boolean)`

- `Boolean CustomSetActive(Boolean)`

- `Void EventOnConfirmClicked()`

- `Void _OnFocusingNode(RoguelikeDungeonNode, RoguelikeDungeonController, IStateEngine)`

- `Void _OnFragmentModule(RoguelikeDungeonNode, RoguelikeDungeonController, IStateEngine)`

- `Void _OnFragmentDialogConfirm(RoguelikeDungeonNode, Boolean, Boolean)`

- `Void _OnFocusingNodeImpl(RoguelikeDungeonNode, RoguelikeDungeonController, IStateEngine)`

- `Void _OnCheckCostSingleton(RoguelikeDungeonNode, RoguelikeDungeonController)`

- `Void _OnSendConfirmRequest(RoguelikeDungeonNode, RoguelikeDungeonController)`

- `Void EventOnEnemyBookClicked()`

- `Void EventOnRollNodeClicked()`

- `Boolean _OnRollNodeConfirm()`

- `Void _EventOnBackClicked()`

- `Void _RefreshInfo()`

- `Void _ConfigureWidgets()`

- `Void <_RefreshInfo>b__41_0(BaseEventData)`

- `IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext)`

- `IEnumerator <>xLuaBaseProxy_HideCoroutine(TransactionContext)`

- `Void <>xLuaBaseProxy_ShowImmediately(TransactionContext)`

- `Void <>xLuaBaseProxy_HideImmediately(TransactionContext)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnPause()`

- `Void <>xLuaBaseProxy_OnExit()`

- `ITransAction <>xLuaBaseProxy_PickDynamicTransAction(State, TransitionType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeFocusState : PopupFadeState, IPopupCustomActive
{
	private const Single FADE_IN_FOCUS_TIME; // 0x0
	private const Single FADE_IN_DELAY; // 0x0
	private const Single SHOW_DURATION; // 0x0
	private RectTransform _panelTopMenu; // 0x70
	private RectTransform _panelRaycastBlock; // 0x78
	private Transform _container; // 0x80
	private RoguelikeFocusView m_view; // 0x88
	private Boolean m_inited; // 0x90
	private ShowSwitchTween m_showSwitchTween; // 0x98
	private MenuAdapter m_menuAdapter; // 0xa0
	private ForwardOutTransition m_forwardOutTrans; // 0xa8
	private GameObject m_effectPrefab; // 0xb0
	private GameObject m_effectInst; // 0xb8
	private static DelegateBridge __Hotfix0__InitFocusView; // 0x0
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x8
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x10
	private static DelegateBridge __Hotfix0_ShowImmediately; // 0x18
	private static DelegateBridge __Hotfix0_HideImmediately; // 0x20
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0_OnEnter; // 0x38
	private static DelegateBridge __Hotfix0_OnResume; // 0x40
	private static DelegateBridge __Hotfix0_OnPause; // 0x48
	private static DelegateBridge __Hotfix0_OnExit; // 0x50
	private static DelegateBridge __Hotfix0_PickDynamicTransAction; // 0x58
	private static DelegateBridge __Hotfix0__SetEffectVisible; // 0x60
	private static DelegateBridge __Hotfix0_CustomSetActive; // 0x68
	private static DelegateBridge __Hotfix0_EventOnConfirmClicked; // 0x70
	private static DelegateBridge __Hotfix0__OnFocusingNode; // 0x78
	private static DelegateBridge __Hotfix0__OnFragmentModule; // 0x80
	private static DelegateBridge __Hotfix0__OnFragmentDialogConfirm; // 0x88
	private static DelegateBridge __Hotfix0__OnFocusingNodeImpl; // 0x90
	private static DelegateBridge __Hotfix0__OnCheckCostSingleton; // 0x98
	private static DelegateBridge __Hotfix0__OnSendConfirmRequest; // 0xa0
	private static DelegateBridge __Hotfix0_EventOnEnemyBookClicked; // 0xa8
	private static DelegateBridge __Hotfix0_EventOnRollNodeClicked; // 0xb0
	private static DelegateBridge __Hotfix0__OnRollNodeConfirm; // 0xb8
	private static DelegateBridge __Hotfix0__EventOnBackClicked; // 0xc0
	private static DelegateBridge __Hotfix0__RefreshInfo; // 0xc8
	private static DelegateBridge __Hotfix0__ConfigureWidgets; // 0xd0
	private static DelegateBridge __Hotfix0__MakeEnemyHandBookList; // 0xd8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xe0


	// RVA: 0x2a031e0 VA: 0x759501b1e0
	private RoguelikeFocusView _InitFocusView(String topicId) { }
	// RVA: 0x2a0325c VA: 0x759501b25c
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x2a033ac VA: 0x759501b3ac
	protected override IEnumerator HideCoroutine(TransactionContext context) { }
	// RVA: 0x2a034fc VA: 0x759501b4fc
	protected override Void ShowImmediately(TransactionContext context) { }
	// RVA: 0x2a03614 VA: 0x759501b614
	protected override Void HideImmediately(TransactionContext context) { }
	// RVA: 0x2a0372c VA: 0x759501b72c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2a03790 VA: 0x759501b790
	private Void _InitIfNot() { }
	// RVA: 0x2a03b78 VA: 0x759501bb78
	protected override Void OnEnter() { }
	// RVA: 0x2a0406c VA: 0x759501c06c
	protected override Void OnResume() { }
	// RVA: 0x2a04244 VA: 0x759501c244
	protected override Void OnPause() { }
	// RVA: 0x2a042bc VA: 0x759501c2bc
	protected override Void OnExit() { }
	// RVA: 0x2a04334 VA: 0x759501c334
	public override ITransAction PickDynamicTransAction(State otherState, TransitionType transType) { }
	// RVA: 0x2a03cf8 VA: 0x759501bcf8
	private Void _SetEffectVisible(Boolean isVisible) { }
	// RVA: 0x2a04430 VA: 0x759501c430
	public Boolean CustomSetActive(Boolean active) { }
	// RVA: 0x2a044d4 VA: 0x759501c4d4
	public Void EventOnConfirmClicked() { }
	// RVA: 0x2a04754 VA: 0x759501c754
	private Void _OnFocusingNode(RoguelikeDungeonNode focusNode, RoguelikeDungeonController controller, IStateEngine stateEngine) { }
	// RVA: 0x2a04840 VA: 0x759501c840
	private Void _OnFragmentModule(RoguelikeDungeonNode focusNode, RoguelikeDungeonController controller, IStateEngine stateEngine) { }
	// RVA: 0x2a05108 VA: 0x759501d108
	private Void _OnFragmentDialogConfirm(RoguelikeDungeonNode focusNode, Boolean isHeavy, Boolean isOverLoad) { }
	// RVA: 0x2a04b8c VA: 0x759501cb8c
	private Void _OnFocusingNodeImpl(RoguelikeDungeonNode focusNode, RoguelikeDungeonController controller, IStateEngine stateEngine) { }
	// RVA: 0x2a04d1c VA: 0x759501cd1c
	private Void _OnCheckCostSingleton(RoguelikeDungeonNode focusNode, RoguelikeDungeonController controller) { }
	// RVA: 0x2a054e8 VA: 0x759501d4e8
	private Void _OnSendConfirmRequest(RoguelikeDungeonNode focusNode, RoguelikeDungeonController controller) { }
	// RVA: 0x2a05828 VA: 0x759501d828
	public Void EventOnEnemyBookClicked() { }
	// RVA: 0x2a05ef4 VA: 0x759501def4
	public Void EventOnRollNodeClicked() { }
	// RVA: 0x2a0623c VA: 0x759501e23c
	public Boolean _OnRollNodeConfirm() { }
	// RVA: 0x2a067a0 VA: 0x759501e7a0
	private Void _EventOnBackClicked() { }
	// RVA: 0x2a03dc8 VA: 0x759501bdc8
	private Void _RefreshInfo() { }
	// RVA: 0x2a04104 VA: 0x759501c104
	private Void _ConfigureWidgets() { }
	// RVA: 0x2a0592c VA: 0x759501d92c
	private List`1 _MakeEnemyHandBookList() { }
	// RVA: 0x2a06a04 VA: 0x759501ea04
	public Void .ctor() { }
	// RVA: 0x2a06a74 VA: 0x759501ea74
	private Void <_RefreshInfo>b__41_0(BaseEventData data) { }
	// RVA: 0x2a06a78 VA: 0x759501ea78
	private IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext P0) { }
	// RVA: 0x2a06aa0 VA: 0x759501eaa0
	private IEnumerator <>xLuaBaseProxy_HideCoroutine(TransactionContext P0) { }
	// RVA: 0x2a06ac8 VA: 0x759501eac8
	private Void <>xLuaBaseProxy_ShowImmediately(TransactionContext P0) { }
	// RVA: 0x2a06af0 VA: 0x759501eaf0
	private Void <>xLuaBaseProxy_HideImmediately(TransactionContext P0) { }
	// RVA: 0x2a06b18 VA: 0x759501eb18
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2a06b20 VA: 0x759501eb20
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2a06b28 VA: 0x759501eb28
	private Void <>xLuaBaseProxy_OnPause() { }
	// RVA: 0x2a06b30 VA: 0x759501eb30
	private Void <>xLuaBaseProxy_OnExit() { }
	// RVA: 0x2a06b38 VA: 0x759501eb38
	private ITransAction <>xLuaBaseProxy_PickDynamicTransAction(State P0, TransitionType P1) { }
}
```