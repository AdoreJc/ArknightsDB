# StoryReviewEntryState

**Namespace:** `Torappu.UI.StoryReview`


## Fields

- `TopMenuDynamicPrefabInstHolder _topmenuHolder`

- `StoryReviewEntryView _entryView`

- `Image _avtivityNewTip`

- `Image _miniNewTip`

- `StoryReviewStateBean m_stateBean`


## Methods

- `Void _InitNewTip()`

- `Boolean _CheckRewardsAvailable(StoryReviewEntryType)`

- `Boolean _CheckStoryAvailable(StoryReviewChapterViewModel)`

- `Void _OnJumpToActivityStoryState(StoryReviewStateBean)`

- `Void _OnJumpToMiniStoryState(MiniActReviewStateBean)`

- `Void EventOnActivityReviewClicked()`

- `Void EventOnMiniReviewClicked()`

- `Void <OnEnter>b__6_0(GameObject)`

- `Void <OnEnter>b__6_1()`

- `Void <RegisterToDataListener>b__8_0(IStateBean)`

- `Void <RegisterToDataListener>b__8_1(IStateBean)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext)`

- `IEnumerator <>xLuaBaseProxy_HideCoroutine(TransactionContext)`

- `Void <>xLuaBaseProxy_ShowImmediately(TransactionContext)`

- `Void <>xLuaBaseProxy_HideImmediately(TransactionContext)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.StoryReview
public class StoryReviewEntryState : PopupFloatState
{
	private TopMenuDynamicPrefabInstHolder _topmenuHolder; // 0x70
	private StoryReviewEntryView _entryView; // 0x78
	private Image _avtivityNewTip; // 0x80
	private Image _miniNewTip; // 0x88
	private StoryReviewStateBean m_stateBean; // 0x90
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x18
	private static DelegateBridge __Hotfix0__InitNewTip; // 0x20
	private static DelegateBridge __Hotfix0__CheckRewardsAvailable; // 0x28
	private static DelegateBridge __Hotfix0__CheckStoryAvailable; // 0x30
	private static DelegateBridge __Hotfix0__OnJumpToActivityStoryState; // 0x38
	private static DelegateBridge __Hotfix0__OnJumpToMiniStoryState; // 0x40
	private static DelegateBridge __Hotfix0_EventOnActivityReviewClicked; // 0x48
	private static DelegateBridge __Hotfix0_EventOnMiniReviewClicked; // 0x50
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x58
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x60
	private static DelegateBridge __Hotfix0_ShowImmediately; // 0x68
	private static DelegateBridge __Hotfix0_HideImmediately; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78


	// RVA: 0x2755828 VA: 0x7594d6d828
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2755890 VA: 0x7594d6d890
	protected override Void OnEnter() { }
	// RVA: 0x2755aac VA: 0x7594d6daac
	protected override Void OnResume() { }
	// RVA: 0x2755b50 VA: 0x7594d6db50
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x27559d4 VA: 0x7594d6d9d4
	private Void _InitNewTip() { }
	// RVA: 0x2755d44 VA: 0x7594d6dd44
	private Boolean _CheckRewardsAvailable(StoryReviewEntryType entryType) { }
	// RVA: 0x2755ee4 VA: 0x7594d6dee4
	private Boolean _CheckStoryAvailable(StoryReviewChapterViewModel viewModel) { }
	// RVA: 0x2756078 VA: 0x7594d6e078
	private Void _OnJumpToActivityStoryState(StoryReviewStateBean targetBean) { }
	// RVA: 0x2756158 VA: 0x7594d6e158
	private Void _OnJumpToMiniStoryState(MiniActReviewStateBean targetBean) { }
	// RVA: 0x2756280 VA: 0x7594d6e280
	public Void EventOnActivityReviewClicked() { }
	// RVA: 0x27564b4 VA: 0x7594d6e4b4
	public Void EventOnMiniReviewClicked() { }
	// RVA: 0x275665c VA: 0x7594d6e65c
	protected override IEnumerator ShowCoroutine(TransactionContext context) { }
	// RVA: 0x27567c4 VA: 0x7594d6e7c4
	protected override IEnumerator HideCoroutine(TransactionContext context) { }
	// RVA: 0x275693c VA: 0x7594d6e93c
	protected override Void ShowImmediately(TransactionContext context) { }
	// RVA: 0x2756a48 VA: 0x7594d6ea48
	protected override Void HideImmediately(TransactionContext context) { }
	// RVA: 0x2756b54 VA: 0x7594d6eb54
	public Void .ctor() { }
	// RVA: 0x2756c04 VA: 0x7594d6ec04
	private Void <OnEnter>b__6_0(GameObject gameObj) { }
	// RVA: 0x2756d00 VA: 0x7594d6ed00
	private Void <OnEnter>b__6_1() { }
	// RVA: 0x2756d20 VA: 0x7594d6ed20
	private Void <RegisterToDataListener>b__8_0(IStateBean targetBean) { }
	// RVA: 0x2756da0 VA: 0x7594d6eda0
	private Void <RegisterToDataListener>b__8_1(IStateBean targetBean) { }
	// RVA: 0x2756e20 VA: 0x7594d6ee20
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2756e28 VA: 0x7594d6ee28
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2756e30 VA: 0x7594d6ee30
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x2756e38 VA: 0x7594d6ee38
	private IEnumerator <>xLuaBaseProxy_ShowCoroutine(TransactionContext P0) { }
	// RVA: 0x2756e60 VA: 0x7594d6ee60
	private IEnumerator <>xLuaBaseProxy_HideCoroutine(TransactionContext P0) { }
	// RVA: 0x2756e88 VA: 0x7594d6ee88
	private Void <>xLuaBaseProxy_ShowImmediately(TransactionContext P0) { }
	// RVA: 0x2756eb0 VA: 0x7594d6eeb0
	private Void <>xLuaBaseProxy_HideImmediately(TransactionContext P0) { }
}
```