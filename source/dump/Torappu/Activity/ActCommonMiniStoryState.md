# ActCommonMiniStoryState

**Namespace:** `Torappu.Activity`


## Fields

- `RectTransform _topMenuContainer`

- `ActCommonMiniStoryBinder _storyBinder`

- `GameObject _maskPanel`

- `Act10D5StoryUnlockConfirmView _unlockPanel`

- `Image _chapterTitleImage`

- `Image _chapterBg`

- `CommonTopMenu m_topMenu`

- `Boolean m_inited`

- `ActCommonMiniStoryStateBean m_stateBean`


## Methods

- `Void _InitIfNot()`

- `Void _OnStoryRead(String)`

- `Void _OnStoryReadSuc()`

- `Void _OnStoryClicked(String)`

- `Void _OnUnlockClicked(String)`

- `Void _OnStoryUnlock(StoryReviewViewModel)`

- `Void _OnStoryUnlocked()`

- `Void <_InitIfNot>b__11_0()`

- `Void <_OnStoryRead>b__12_0(ReadStoryResponse)`

- `Void <_OnStoryUnlock>b__16_0(UnlockReviewByCoinResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity
public class ActCommonMiniStoryState : PopupFadeState
{
	private RectTransform _topMenuContainer; // 0x70
	private ActCommonMiniStoryBinder _storyBinder; // 0x78
	private GameObject _maskPanel; // 0x80
	private Act10D5StoryUnlockConfirmView _unlockPanel; // 0x88
	private Image _chapterTitleImage; // 0x90
	private Image _chapterBg; // 0x98
	private CommonTopMenu m_topMenu; // 0xa0
	private Boolean m_inited; // 0xa8
	private ActCommonMiniStoryStateBean m_stateBean; // 0xb0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__OnStoryRead; // 0x18
	private static DelegateBridge __Hotfix0__OnStoryReadSuc; // 0x20
	private static DelegateBridge __Hotfix0__OnStoryClicked; // 0x28
	private static DelegateBridge __Hotfix0__OnUnlockClicked; // 0x30
	private static DelegateBridge __Hotfix0__OnStoryUnlock; // 0x38
	private static DelegateBridge __Hotfix0__OnStoryUnlocked; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x30c9f94 VA: 0x75956e1f94
	public override IStateBean GetCacheBean() { }
	// RVA: 0x30c9ffc VA: 0x75956e1ffc
	protected override Void OnEnter() { }
	// RVA: 0x30ca38c VA: 0x75956e238c
	private Void _InitIfNot() { }
	// RVA: 0x30ca824 VA: 0x75956e2824
	private Void _OnStoryRead(String storyId) { }
	// RVA: 0x30caa0c VA: 0x75956e2a0c
	private Void _OnStoryReadSuc() { }
	// RVA: 0x30cab88 VA: 0x75956e2b88
	private Void _OnStoryClicked(String storyId) { }
	// RVA: 0x30cad1c VA: 0x75956e2d1c
	private Void _OnUnlockClicked(String storyId) { }
	// RVA: 0x30cb06c VA: 0x75956e306c
	private Void _OnStoryUnlock(StoryReviewViewModel viewModel) { }
	// RVA: 0x30cb35c VA: 0x75956e335c
	private Void _OnStoryUnlocked() { }
	// RVA: 0x30cb420 VA: 0x75956e3420
	public Void .ctor() { }
	// RVA: 0x30cb578 VA: 0x75956e3578
	private Void <_InitIfNot>b__11_0() { }
	// RVA: 0x30cb580 VA: 0x75956e3580
	private Void <_OnStoryRead>b__12_0(ReadStoryResponse _) { }
	// RVA: 0x30cb584 VA: 0x75956e3584
	private Void <_OnStoryUnlock>b__16_0(UnlockReviewByCoinResponse _) { }
	// RVA: 0x30cb588 VA: 0x75956e3588
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```