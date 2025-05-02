# TuningHomeState

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `TuningHomeFragGroupView _fragGroupView`

- `TuningHomeInvestGroupView _investView`

- `AnimationWrapper _animationWrapper`

- `RectTransform _topMenuContainer`

- `TuningHomeStateBean m_stateBean`

- `Boolean m_hasInited`

- `Tween m_entryAnim`

- `String m_cachedInvestId`


## Methods

- `Void _OnJumpToChatState(IStateBean)`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnProductBtnClicked()`

- `Void _OnStartInvestBtnClicked(ValueBundle)`

- `Void _OnUnlockInvestBtnClicked()`

- `Void _OnArchiveBtnClicked()`

- `Void _OnMajorInvestDetailBtnClicked()`

- `Void _InitIfNot()`

- `Void _OnBackBtnPressed()`

- `Void _PlayEntryAnim()`

- `Void _OnUnlockMajorInvestProceed(TuningStartMajorInvestResponse)`

- `Void _TryConsumeGuidebook()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningHomeState : PopupFadeState, IValueMsgReceiver, IHotfixable
{
	private const String ENTRY_ANIM_NAME; // 0x0
	private const String GUIDE_BOOK_SUB_SIGNAL; // 0x0
	public const Int32 ON_PRODUCT_BTN_CLICKED; // 0x0
	public const Int32 ON_START_INVEST_BTN_CLICKED; // 0x0
	public const Int32 ON_UNLOCK_MAJOR_INVEST_BTN_CLICKED; // 0x0
	public const Int32 ON_ARCHIVE_BTN_CLICKED; // 0x0
	public const Int32 ON_MAJOR_INVEST_DETAIL_BTN_CLICKED; // 0x0
	private TuningHomeFragGroupView _fragGroupView; // 0x70
	private TuningHomeInvestGroupView _investView; // 0x78
	private AnimationWrapper _animationWrapper; // 0x80
	private RectTransform _topMenuContainer; // 0x88
	private TuningHomeStateBean m_stateBean; // 0x90
	private Boolean m_hasInited; // 0x98
	private Tween m_entryAnim; // 0xa0
	private String m_cachedInvestId; // 0xa8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_OnResume; // 0x8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x10
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x18
	private static DelegateBridge __Hotfix0__OnJumpToChatState; // 0x20
	private static DelegateBridge __Hotfix0_OnMessage; // 0x28
	private static DelegateBridge __Hotfix0__OnProductBtnClicked; // 0x30
	private static DelegateBridge __Hotfix0__OnStartInvestBtnClicked; // 0x38
	private static DelegateBridge __Hotfix0__OnUnlockInvestBtnClicked; // 0x40
	private static DelegateBridge __Hotfix0__OnArchiveBtnClicked; // 0x48
	private static DelegateBridge __Hotfix0__OnMajorInvestDetailBtnClicked; // 0x50
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x58
	private static DelegateBridge __Hotfix0__OnBackBtnPressed; // 0x60
	private static DelegateBridge __Hotfix0__PlayEntryAnim; // 0x68
	private static DelegateBridge __Hotfix0__OnUnlockMajorInvestProceed; // 0x70
	private static DelegateBridge __Hotfix0__TryConsumeGuidebook; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80


	// RVA: 0x2328540 VA: 0x7594940540
	protected override Void OnEnter() { }
	// RVA: 0x2328a44 VA: 0x7594940a44
	protected override Void OnResume() { }
	// RVA: 0x2328bcc VA: 0x7594940bcc
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2328c34 VA: 0x7594940c34
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2328dac VA: 0x7594940dac
	private Void _OnJumpToChatState(IStateBean sb) { }
	// RVA: 0x2328e8c VA: 0x7594940e8c
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x2328fac VA: 0x7594940fac
	private Void _OnProductBtnClicked() { }
	// RVA: 0x2329134 VA: 0x7594941134
	private Void _OnStartInvestBtnClicked(ValueBundle msg) { }
	// RVA: 0x23294a0 VA: 0x75949414a0
	private Void _OnUnlockInvestBtnClicked() { }
	// RVA: 0x23296c0 VA: 0x75949416c0
	private Void _OnArchiveBtnClicked() { }
	// RVA: 0x23298f4 VA: 0x75949418f4
	private Void _OnMajorInvestDetailBtnClicked() { }
	// RVA: 0x232867c VA: 0x759494067c
	private Void _InitIfNot() { }
	// RVA: 0x2329a7c VA: 0x7594941a7c
	private Void _OnBackBtnPressed() { }
	// RVA: 0x2328894 VA: 0x7594940894
	private Void _PlayEntryAnim() { }
	// RVA: 0x2329b48 VA: 0x7594941b48
	private Void _OnUnlockMajorInvestProceed(TuningStartMajorInvestResponse response) { }
	// RVA: 0x2328b44 VA: 0x7594940b44
	private Void _TryConsumeGuidebook() { }
	// RVA: 0x2329c74 VA: 0x7594941c74
	public Void .ctor() { }
	// RVA: 0x2329e08 VA: 0x7594941e08
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2329e10 VA: 0x7594941e10
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2329e18 VA: 0x7594941e18
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```