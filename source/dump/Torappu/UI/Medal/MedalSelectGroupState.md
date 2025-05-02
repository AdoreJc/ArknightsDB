# MedalSelectGroupState

**Namespace:** `Torappu.UI.Medal`


## Fields

- `MedalGroupListView _listView`

- `MedalListStateBean _stateBean`

- `RectTransform _topMenuHolder`

- `Text _textSelectedCount`

- `RectTransform _btnBack`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void _UpdateSelectCount()`

- `Void OnClickMedalEvent(MedalCommonViewModel)`

- `Void EventOnConfirmClicked()`

- `Void EventOnClearClicked()`

- `IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class MedalSelectGroupState : PopupFadeState
{
	private MedalGroupListView _listView; // 0x70
	private MedalListStateBean _stateBean; // 0x78
	private RectTransform _topMenuHolder; // 0x80
	private Text _textSelectedCount; // 0x88
	private RectTransform _btnBack; // 0x90
	private Boolean m_isInited; // 0x98
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x10
	private static DelegateBridge __Hotfix0_OnEnter; // 0x18
	private static DelegateBridge __Hotfix0__UpdateSelectCount; // 0x20
	private static DelegateBridge __Hotfix0_OnClickMedalEvent; // 0x28
	private static DelegateBridge __Hotfix0_EventOnConfirmClicked; // 0x30
	private static DelegateBridge __Hotfix0_EventOnClearClicked; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x2797f04 VA: 0x7594daff04
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2797f6c VA: 0x7594daff6c
	private Void _InitIfNot() { }
	// RVA: 0x2798060 VA: 0x7594db0060
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x279817c VA: 0x7594db017c
	protected override Void OnEnter() { }
	// RVA: 0x2798248 VA: 0x7594db0248
	private Void _UpdateSelectCount() { }
	// RVA: 0x2798358 VA: 0x7594db0358
	public Void OnClickMedalEvent(MedalCommonViewModel viewModel) { }
	// RVA: 0x27984d0 VA: 0x7594db04d0
	public Void EventOnConfirmClicked() { }
	// RVA: 0x2798558 VA: 0x7594db0558
	public Void EventOnClearClicked() { }
	// RVA: 0x27985e0 VA: 0x7594db05e0
	public Void .ctor() { }
	// RVA: 0x2798650 VA: 0x7594db0650
	private IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext P0) { }
	// RVA: 0x2798678 VA: 0x7594db0678
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```