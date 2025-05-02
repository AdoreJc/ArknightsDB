# Act10D5StoryState

**Namespace:** `Torappu.Activity.Act10D5`


## Fields

- `RectTransform _topMenuContainer`

- `Act10D5StoryBinder _storyBinder`

- `GameObject _maskPanel`

- `Act10D5StoryUnlockConfirmView _unlockPanel`

- `CommonTopMenu m_topMenu`

- `Boolean m_inited`

- `Act10D5StoryStateBean m_stateBean`


## Methods

- `Void _InitIfNot()`

- `Void _OnStoryRead(String)`

- `Void _OnStoryReadSuc()`

- `Void _OnStoryClicked(String)`

- `Void _OnUnlockClicked(String)`

- `Void _OnStoryUnlock(StoryReviewViewModel)`

- `Void _OnStoryUnlocked()`

- `Void <_InitIfNot>b__9_0()`

- `Void <_OnStoryRead>b__10_0(ReadStoryResponse)`

- `Void <_OnStoryUnlock>b__14_0(UnlockReviewByCoinResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act10D5
public class Act10D5StoryState : PopupFadeState
{
	private RectTransform _topMenuContainer; // 0x70
	private Act10D5StoryBinder _storyBinder; // 0x78
	private GameObject _maskPanel; // 0x80
	private Act10D5StoryUnlockConfirmView _unlockPanel; // 0x88
	private CommonTopMenu m_topMenu; // 0x90
	private Boolean m_inited; // 0x98
	private Act10D5StoryStateBean m_stateBean; // 0xa0
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


	// RVA: 0x34833c0 VA: 0x7595a9b3c0
	public override IStateBean GetCacheBean() { }
	// RVA: 0x3483428 VA: 0x7595a9b428
	protected override Void OnEnter() { }
	// RVA: 0x3483678 VA: 0x7595a9b678
	private Void _InitIfNot() { }
	// RVA: 0x3483758 VA: 0x7595a9b758
	private Void _OnStoryRead(String storyId) { }
	// RVA: 0x3483940 VA: 0x7595a9b940
	private Void _OnStoryReadSuc() { }
	// RVA: 0x3483a08 VA: 0x7595a9ba08
	private Void _OnStoryClicked(String storyId) { }
	// RVA: 0x3483c38 VA: 0x7595a9bc38
	private Void _OnUnlockClicked(String storyId) { }
	// RVA: 0x3483e4c VA: 0x7595a9be4c
	private Void _OnStoryUnlock(StoryReviewViewModel viewModel) { }
	// RVA: 0x3484140 VA: 0x7595a9c140
	private Void _OnStoryUnlocked() { }
	// RVA: 0x3484208 VA: 0x7595a9c208
	public Void .ctor() { }
	// RVA: 0x34842b8 VA: 0x7595a9c2b8
	private Void <_InitIfNot>b__9_0() { }
	// RVA: 0x34842c0 VA: 0x7595a9c2c0
	private Void <_OnStoryRead>b__10_0(ReadStoryResponse _) { }
	// RVA: 0x34842c4 VA: 0x7595a9c2c4
	private Void <_OnStoryUnlock>b__14_0(UnlockReviewByCoinResponse _) { }
	// RVA: 0x34842c8 VA: 0x7595a9c2c8
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```