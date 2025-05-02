# Act1ArcadeBadgeBookView

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `Text _ultimateGroupNameText`

- `Act1ArcadeBadgeBookItemHeadView _ultimateBadgeHeadView`

- `Act1ArcadeBadgeBookUltimateTailView _ultimateBadgeTailView`

- `ScrollRect _badgesContentScroll`

- `RectTransform _badgeContentRect`

- `HorizontalLayoutGroup _badgeContentLayout`

- `ContentSizeFitter _badgeContentFitter`

- `CanvasGroup _badgesContentGroup`

- `Single _contentFadeTime`

- `UIAnimationLocation _switchButtonAnimation`

- `UIAnimationLocation _ultimateBadgeSwitchAnimation`

- `Single _focusFullLengthDuration`

- `UIStateFinder m_stateFinder`

- `Boolean m_hasInited`

- `AnimationSwitchTween m_switchButtonTween`

- `AnimationSwitchTween m_ultimateBadgeTween`

- `Act1ArcadeBadgeBookViewModel m_cachedModel`

- `BadgeBookLayoutMode m_displayedLayoutMode`

- `Sequence m_switchSequence`


## Methods

- `Void OnOpenShareEvent()`

- `Void OnSwitchLayoutEvent()`

- `Void PlayFocusItem(Int32)`

- `Act1ArcadeBadgeBookShareModelCollector GenerateShareModelCollector()`

- `Void _InitIfNot()`

- `Void _SwitchContentGroup()`

- `Void _RefreshGroupViews()`

- `Bounds _CalculateRelativeBounds(Transform, RectTransform)`

- `Void <PlayFocusItem>b__24_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Act1ArcadeBadgeBookView : DataBinder`1
{
	private Text _ultimateGroupNameText; // 0x20
	private Act1ArcadeBadgeBookItemHeadView _ultimateBadgeHeadView; // 0x28
	private Act1ArcadeBadgeBookUltimateTailView _ultimateBadgeTailView; // 0x30
	private List`1 _badgeGroups; // 0x38
	private ScrollRect _badgesContentScroll; // 0x40
	private RectTransform _badgeContentRect; // 0x48
	private HorizontalLayoutGroup _badgeContentLayout; // 0x50
	private ContentSizeFitter _badgeContentFitter; // 0x58
	private CanvasGroup _badgesContentGroup; // 0x60
	private Single _contentFadeTime; // 0x68
	private UIAnimationLocation _switchButtonAnimation; // 0x70
	private UIAnimationLocation _ultimateBadgeSwitchAnimation; // 0x80
	private Single _focusFullLengthDuration; // 0x90
	private UIStateFinder m_stateFinder; // 0x98
	private Boolean m_hasInited; // 0xa8
	private AnimationSwitchTween m_switchButtonTween; // 0xb0
	private AnimationSwitchTween m_ultimateBadgeTween; // 0xb8
	private Act1ArcadeBadgeBookViewModel m_cachedModel; // 0xc0
	private BadgeBookLayoutMode m_displayedLayoutMode; // 0xc8
	private Sequence m_switchSequence; // 0xd0
	private Vector3[] m_cornerCache; // 0xd8
	private static DelegateBridge __Hotfix0_OnOpenShareEvent; // 0x0
	private static DelegateBridge __Hotfix0_OnSwitchLayoutEvent; // 0x8
	private static DelegateBridge __Hotfix0_PlayFocusItem; // 0x10
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x18
	private static DelegateBridge __Hotfix0_GenerateShareModelCollector; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0__SwitchContentGroup; // 0x30
	private static DelegateBridge __Hotfix0__RefreshGroupViews; // 0x38
	private static DelegateBridge __Hotfix0__CalculateRelativeBounds; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x33fa940 VA: 0x7595a12940
	public Void OnOpenShareEvent() { }
	// RVA: 0x33fa9f4 VA: 0x7595a129f4
	public Void OnSwitchLayoutEvent() { }
	// RVA: 0x33f9c24 VA: 0x7595a11c24
	public Void PlayFocusItem(Int32 index) { }
	// RVA: 0x33fad2c VA: 0x7595a12d2c
	public override Void OnValueChanged(Act1ArcadeBadgeBookProperty property) { }
	// RVA: 0x33f86ec VA: 0x7595a106ec
	public Act1ArcadeBadgeBookShareModelCollector GenerateShareModelCollector() { }
	// RVA: 0x33faf40 VA: 0x7595a12f40
	private Void _InitIfNot() { }
	// RVA: 0x33fb4d8 VA: 0x7595a134d8
	private Void _SwitchContentGroup() { }
	// RVA: 0x33fb224 VA: 0x7595a13224
	private Void _RefreshGroupViews() { }
	// RVA: 0x33faaa8 VA: 0x7595a12aa8
	private Bounds _CalculateRelativeBounds(Transform root, RectTransform child) { }
	// RVA: 0x33fbbf4 VA: 0x7595a13bf4
	public Void .ctor() { }
	// RVA: 0x33fbcbc VA: 0x7595a13cbc
	private Void <PlayFocusItem>b__24_0() { }
}
```