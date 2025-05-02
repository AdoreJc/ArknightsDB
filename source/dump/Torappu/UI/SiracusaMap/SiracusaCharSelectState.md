# SiracusaCharSelectState

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `TopMenuDynamicPrefabInstHolder _topMenuHolder`

- `SiracusaCharSelectView _view`

- `AnimationWrapper _enterAnimWrapper`

- `RectTransform _rectTopBlocker`

- `Boolean m_hasInited`

- `SiracusaCharSelectProperty m_charSelectProperty`

- `String m_groupId`


## Methods

- `Void _InitIfNot()`

- `Void _OnInitTopMenu(GameObject)`

- `Void _PlayEnterAnim()`

- `Void _OnCancel()`

- `Void _EventOnCharSelectChange(String)`

- `Void _EventOnQuitCharCard()`

- `Void _EventOnSelectCharCard(String)`

- `Void _EventOnReview(String)`

- `Void _SelectCharCard(String)`

- `Void _OnSelectCharCardResponse(Boolean, String)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_DealWithOtherStateBeforeTransStart(TransactionContext, Boolean)`

- `Void <>xLuaBaseProxy_DealWithOtherStateWenTransEnd(TransactionContext, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaCharSelectState : PopupFadeState, ISiracusaReplaceable
{
	private TopMenuDynamicPrefabInstHolder _topMenuHolder; // 0x70
	private SiracusaCharSelectView _view; // 0x78
	private AnimationWrapper _enterAnimWrapper; // 0x80
	private RectTransform _rectTopBlocker; // 0x88
	private Boolean m_hasInited; // 0x90
	private SiracusaCharSelectProperty m_charSelectProperty; // 0x98
	private String m_groupId; // 0xa0
	private const String ENTRY_ANIM; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x8
	private static DelegateBridge __Hotfix0_DealWithOtherStateBeforeTransStart; // 0x10
	private static DelegateBridge __Hotfix0_DealWithOtherStateWenTransEnd; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0__OnInitTopMenu; // 0x28
	private static DelegateBridge __Hotfix0__PlayEnterAnim; // 0x30
	private static DelegateBridge __Hotfix0__OnCancel; // 0x38
	private static DelegateBridge __Hotfix0__EventOnCharSelectChange; // 0x40
	private static DelegateBridge __Hotfix0__EventOnQuitCharCard; // 0x48
	private static DelegateBridge __Hotfix0__EventOnSelectCharCard; // 0x50
	private static DelegateBridge __Hotfix0__EventOnReview; // 0x58
	private static DelegateBridge __Hotfix0__SelectCharCard; // 0x60
	private static DelegateBridge __Hotfix0__OnSelectCharCardResponse; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70


	// RVA: 0x23eea68 VA: 0x7594a06a68
	protected override Void OnEnter() { }
	// RVA: 0x23ef5b4 VA: 0x7594a075b4
	public override IStateBean GetCacheBean() { }
	// RVA: 0x23ef618 VA: 0x7594a07618
	protected sealed override Void DealWithOtherStateBeforeTransStart(TransactionContext context, Boolean isFastMode) { }
	// RVA: 0x23ef770 VA: 0x7594a07770
	protected sealed override Void DealWithOtherStateWenTransEnd(TransactionContext context, Boolean isFastMode) { }
	// RVA: 0x23eec90 VA: 0x7594a06c90
	private Void _InitIfNot() { }
	// RVA: 0x23efad8 VA: 0x7594a07ad8
	private Void _OnInitTopMenu(GameObject inst) { }
	// RVA: 0x23ef4fc VA: 0x7594a074fc
	private Void _PlayEnterAnim() { }
	// RVA: 0x23efc20 VA: 0x7594a07c20
	private Void _OnCancel() { }
	// RVA: 0x23efdb0 VA: 0x7594a07db0
	private Void _EventOnCharSelectChange(String charCardId) { }
	// RVA: 0x23effa8 VA: 0x7594a07fa8
	private Void _EventOnQuitCharCard() { }
	// RVA: 0x23f02b8 VA: 0x7594a082b8
	private Void _EventOnSelectCharCard(String charCardId) { }
	// RVA: 0x23f0338 VA: 0x7594a08338
	private Void _EventOnReview(String charCardId) { }
	// RVA: 0x23f0014 VA: 0x7594a08014
	private Void _SelectCharCard(String charCardId) { }
	// RVA: 0x23f045c VA: 0x7594a0845c
	private Void _OnSelectCharCardResponse(Boolean isUnload, String charCardId) { }
	// RVA: 0x23f0804 VA: 0x7594a08804
	public Void .ctor() { }
	// RVA: 0x23f091c VA: 0x7594a0891c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x23f0924 VA: 0x7594a08924
	private Void <>xLuaBaseProxy_DealWithOtherStateBeforeTransStart(TransactionContext P0, Boolean P1) { }
	// RVA: 0x23f0950 VA: 0x7594a08950
	private Void <>xLuaBaseProxy_DealWithOtherStateWenTransEnd(TransactionContext P0, Boolean P1) { }
}
```