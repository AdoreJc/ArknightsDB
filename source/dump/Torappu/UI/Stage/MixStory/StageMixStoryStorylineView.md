# StageMixStoryStorylineView

**Namespace:** `Torappu.UI.Stage.MixStory`


## Fields

- `UIDynImage _abbrIconImage`

- `Transform _focusEffectHolder`

- `GameObject _focusEffect`

- `Transform _trackPointHolder`

- `Single _size`

- `UIAnimationLocation _focusAnimation`

- `UIStateFinder m_finder`

- `Boolean m_isInited`

- `ILoadAsset m_iLoadAsset`

- `AnimationWrapper m_wrapper`

- `Single m_focusDuration`

- `UIAnimationTween m_focusTween`

- `GameObject m_focusEffectInstance`

- `GameObject m_trackPoint`

- `StageStorylineViewModel m_cachedModel`

- `Boolean m_focused`

- `String m_cachedAbbrIconId`


## Properties

- `UIAnimationLocation focusAnimation`


## Methods

- `UIAnimationLocation get_focusAnimation()`

- `Void OnClickEvent()`

- `Void _Render(StageStorylineViewModel, StageMixStoryStorylineItemSyncHandler)`

- `Void _InitIfNot()`

- `Void _UpdateFocusState(StageStorylineViewModel, StageMixStoryStorylineItemSyncHandler)`

- `Void _UpdateFocusEffectState(Boolean)`

- `Void _UpdateTrackPointState(StageStorylineViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.MixStory
public class StageMixStoryStorylineView : MonoBehaviour, IHotfixable
{
	private UIDynImage _abbrIconImage; // 0x18
	private List`1 _nameTexts; // 0x20
	private Transform _focusEffectHolder; // 0x28
	private GameObject _focusEffect; // 0x30
	private Transform _trackPointHolder; // 0x38
	private Single _size; // 0x40
	private UIAnimationLocation _focusAnimation; // 0x48
	private UIStateFinder m_finder; // 0x58
	private Boolean m_isInited; // 0x68
	private ILoadAsset m_iLoadAsset; // 0x70
	private AnimationWrapper m_wrapper; // 0x78
	private Single m_focusDuration; // 0x80
	private UIAnimationTween m_focusTween; // 0x88
	private GameObject m_focusEffectInstance; // 0x90
	private GameObject m_trackPoint; // 0x98
	private StageStorylineViewModel m_cachedModel; // 0xa0
	private Boolean m_focused; // 0xa8
	private String m_cachedAbbrIconId; // 0xb0
	private static DelegateBridge __Hotfix0_get_focusAnimation; // 0x0
	private static DelegateBridge __Hotfix0_OnClickEvent; // 0x8
	private static DelegateBridge __Hotfix0__Render; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__UpdateFocusState; // 0x20
	private static DelegateBridge __Hotfix0__UpdateFocusEffectState; // 0x28
	private static DelegateBridge __Hotfix0__UpdateTrackPointState; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public UIAnimationLocation focusAnimation { get; }

	// RVA: 0x2fe8b60 VA: 0x7595600b60
	public UIAnimationLocation get_focusAnimation() { }
	// RVA: 0x2fe8bc4 VA: 0x7595600bc4
	public Void OnClickEvent() { }
	// RVA: 0x2fe8d10 VA: 0x7595600d10
	private Void _Render(StageStorylineViewModel model, StageMixStoryStorylineItemSyncHandler handler) { }
	// RVA: 0x2fe8f54 VA: 0x7595600f54
	private Void _InitIfNot() { }
	// RVA: 0x2fe9050 VA: 0x7595601050
	private Void _UpdateFocusState(StageStorylineViewModel model, StageMixStoryStorylineItemSyncHandler handler) { }
	// RVA: 0x2fe946c VA: 0x759560146c
	private Void _UpdateFocusEffectState(Boolean focused) { }
	// RVA: 0x2fe9308 VA: 0x7595601308
	private Void _UpdateTrackPointState(StageStorylineViewModel model) { }
	// RVA: 0x2fe957c VA: 0x759560157c
	public Void .ctor() { }
}
```