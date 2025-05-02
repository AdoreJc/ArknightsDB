# Act24sideMissionDetailState

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `Act24sideMissionDetailView _view`

- `UIAnimationLocation _anim`

- `RectTransform _backRect`

- `Act24sideMissionDetailStateBean m_stateBean`

- `TemplateActivityController m_cacheController`

- `Boolean m_isInited`

- `Tween m_entryTween`


## Methods

- `Void _RefreshData()`

- `Void _RefreshStageMeldingData()`

- `Void _RefreshEntryMissionData()`

- `Void _InitIfNot()`

- `Void BindController(TemplateActivityController)`

- `Void OnClickBackBtn()`

- `Void _OnClickLeftArrowBtn()`

- `Void _OnClickRightArrowBtn()`

- `Void _OnClickCompleteBtn(String)`

- `IEnumerator _ReceiveItemsCoroutine(List`1)`

- `IEnumerator <>n__0(TransactionContext)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideMissionDetailState : PopupFloatState, IBaseActStateHolder, IHotfixable
{
	private Act24sideMissionDetailView _view; // 0x70
	private UIAnimationLocation _anim; // 0x78
	private RectTransform _backRect; // 0x88
	private Act24sideMissionDetailStateBean m_stateBean; // 0x90
	private TemplateActivityController m_cacheController; // 0x98
	private Boolean m_isInited; // 0xa0
	private Tween m_entryTween; // 0xa8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x10
	private static DelegateBridge __Hotfix0__RefreshData; // 0x18
	private static DelegateBridge __Hotfix0__RefreshStageMeldingData; // 0x20
	private static DelegateBridge __Hotfix0__RefreshEntryMissionData; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0_BindController; // 0x38
	private static DelegateBridge __Hotfix0_OnClickBackBtn; // 0x40
	private static DelegateBridge __Hotfix0__OnClickLeftArrowBtn; // 0x48
	private static DelegateBridge __Hotfix0__OnClickRightArrowBtn; // 0x50
	private static DelegateBridge __Hotfix0__OnClickCompleteBtn; // 0x58
	private static DelegateBridge __Hotfix0__ReceiveItemsCoroutine; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68


	// RVA: 0x32b4ff0 VA: 0x75958ccff0
	public override IStateBean GetCacheBean() { }
	// RVA: 0x32b5058 VA: 0x75958cd058
	protected override Void OnEnter() { }
	// RVA: 0x32b54ac VA: 0x75958cd4ac
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x32b5640 VA: 0x75958cd640
	private Void _RefreshData() { }
	// RVA: 0x32b56ec VA: 0x75958cd6ec
	private Void _RefreshStageMeldingData() { }
	// RVA: 0x32b5828 VA: 0x75958cd828
	private Void _RefreshEntryMissionData() { }
	// RVA: 0x32b518c VA: 0x75958cd18c
	private Void _InitIfNot() { }
	// RVA: 0x32b59f8 VA: 0x75958cd9f8
	public Void BindController(TemplateActivityController controller) { }
	// RVA: 0x32b5a7c VA: 0x75958cda7c
	public Void OnClickBackBtn() { }
	// RVA: 0x32b5b90 VA: 0x75958cdb90
	private Void _OnClickLeftArrowBtn() { }
	// RVA: 0x32b5c60 VA: 0x75958cdc60
	private Void _OnClickRightArrowBtn() { }
	// RVA: 0x32b5d38 VA: 0x75958cdd38
	private Void _OnClickCompleteBtn(String missionId) { }
	// RVA: 0x32b6004 VA: 0x75958ce004
	private IEnumerator _ReceiveItemsCoroutine(List`1 rewardList) { }
	// RVA: 0x32b60fc VA: 0x75958ce0fc
	public Void .ctor() { }
	// RVA: 0x32b6254 VA: 0x75958ce254
	private IEnumerator <>n__0(TransactionContext context) { }
	// RVA: 0x32b627c VA: 0x75958ce27c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x32b6284 VA: 0x75958ce284
	private IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext P0) { }
}
```