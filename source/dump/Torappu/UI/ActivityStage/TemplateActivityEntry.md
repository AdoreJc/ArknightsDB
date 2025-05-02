# TemplateActivityEntry

**Namespace:** `Torappu.UI.ActivityStage`


## Fields

- `RectTransform _topMenuContainer`

- `TemplateActivityEntryTutorialHandler _tutorialHandler`

- `CommonTopMenu m_topMenu`

- `Boolean m_isAnimPlaying`

- `Int32 m_runningAnimCount`

- `Boolean m_isBindToParent`


## Properties

- `Boolean isAnimPlaying`


## Methods

- `Void Awake()`

- `Void _UpdateBindToParentStatus()`

- `Boolean get_isAnimPlaying()`

- `Void _CheckAllFinish()`

- `Void _DescreasePlayingCount()`

- `Void _SampleAllAnimClipAtBegin()`

- `IEnumerator _PlayTargetAnim(Boolean, EntryAnim)`

- `Void _PlayWithAnim(Boolean)`

- `Boolean _TryTriggerAVG()`

- `Void _OnVideoStoryCompleted(Story)`

- `Void _TryStartAnim()`

- `Void _TryTrigTutorial()`

- `Void _TryRegisterGOAndRaiseSignal()`

- `Void EventOnMedalClicked()`

- `Void EventOnUngroupedMedalClicked()`

- `Void EventOnZoneClicked(String)`

- `Void _RealEventOnZoneClicked(String)`

- `Void EventOnReplayEntryAVG()`

- `Void EventOnShopClicked()`

- `Void EventOnReplicateClicked()`

- `Void _InitTopMenu()`

- `Void <_PlayTargetAnim>b__20_0()`

- `Void <>xLuaBaseProxy_OnLoaded()`

- `Void <>xLuaBaseProxy_OnBindToParent()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActivityStage
public class TemplateActivityEntry : TemplateActivitySingleComponent, IHotfixable
{
	public const Single ANIM_SMOOTH_DELAY; // 0x0
	private RectTransform _topMenuContainer; // 0x30
	private List`1 _animList; // 0x38
	private List`1 _onAnimEndList; // 0x40
	private GameObject[] _enableWhenBinded; // 0x48
	private TemplateActivityEntryTutorialHandler _tutorialHandler; // 0x50
	private CommonTopMenu m_topMenu; // 0x58
	private Boolean m_isAnimPlaying; // 0x60
	private Int32 m_runningAnimCount; // 0x64
	private Boolean m_isBindToParent; // 0x68
	private static DelegateBridge __Hotfix0_Awake; // 0x0
	private static DelegateBridge __Hotfix0__UpdateBindToParentStatus; // 0x8
	private static DelegateBridge __Hotfix0_OnLoaded; // 0x10
	private static DelegateBridge __Hotfix0_OnBindToParent; // 0x18
	private static DelegateBridge __Hotfix0_get_isAnimPlaying; // 0x20
	private static DelegateBridge __Hotfix0__CheckAllFinish; // 0x28
	private static DelegateBridge __Hotfix0__DescreasePlayingCount; // 0x30
	private static DelegateBridge __Hotfix0__SampleAllAnimClipAtBegin; // 0x38
	private static DelegateBridge __Hotfix0__PlayTargetAnim; // 0x40
	private static DelegateBridge __Hotfix0__PlayWithAnim; // 0x48
	private static DelegateBridge __Hotfix0__TryTriggerAVG; // 0x50
	private static DelegateBridge __Hotfix0__OnVideoStoryCompleted; // 0x58
	private static DelegateBridge __Hotfix0__TryStartAnim; // 0x60
	private static DelegateBridge __Hotfix0__TryTrigTutorial; // 0x68
	private static DelegateBridge __Hotfix0__TryRegisterGOAndRaiseSignal; // 0x70
	private static DelegateBridge __Hotfix0_EventOnMedalClicked; // 0x78
	private static DelegateBridge __Hotfix0_EventOnUngroupedMedalClicked; // 0x80
	private static DelegateBridge __Hotfix0_EventOnZoneClicked; // 0x88
	private static DelegateBridge __Hotfix0__RealEventOnZoneClicked; // 0x90
	private static DelegateBridge __Hotfix0_EventOnReplayEntryAVG; // 0x98
	private static DelegateBridge __Hotfix0_EventOnShopClicked; // 0xa0
	private static DelegateBridge __Hotfix0_EventOnReplicateClicked; // 0xa8
	private static DelegateBridge __Hotfix0__InitTopMenu; // 0xb0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb8

	public Boolean isAnimPlaying { get; }

	// RVA: 0x30a2494 VA: 0x75956ba494
	private Void Awake() { }
	// RVA: 0x30a24fc VA: 0x75956ba4fc
	private Void _UpdateBindToParentStatus() { }
	// RVA: 0x30a25cc VA: 0x75956ba5cc
	protected override Void OnLoaded() { }
	// RVA: 0x30a2ca0 VA: 0x75956baca0
	protected override Void OnBindToParent() { }
	// RVA: 0x30a1c04 VA: 0x75956b9c04
	public Boolean get_isAnimPlaying() { }
	// RVA: 0x30a2d1c VA: 0x75956bad1c
	private Void _CheckAllFinish() { }
	// RVA: 0x30a303c VA: 0x75956bb03c
	private Void _DescreasePlayingCount() { }
	// RVA: 0x30a27f8 VA: 0x75956ba7f8
	private Void _SampleAllAnimClipAtBegin() { }
	// RVA: 0x30a30b0 VA: 0x75956bb0b0
	private IEnumerator _PlayTargetAnim(Boolean isSkip, EntryAnim anim) { }
	// RVA: 0x30a31b8 VA: 0x75956bb1b8
	private Void _PlayWithAnim(Boolean isSkip) { }
	// RVA: 0x30a2910 VA: 0x75956ba910
	private Boolean _TryTriggerAVG() { }
	// RVA: 0x30a3304 VA: 0x75956bb304
	private Void _OnVideoStoryCompleted(Story _) { }
	// RVA: 0x30a2c24 VA: 0x75956bac24
	private Void _TryStartAnim() { }
	// RVA: 0x30a2ab8 VA: 0x75956baab8
	private Void _TryTrigTutorial() { }
	// RVA: 0x30a2ebc VA: 0x75956baebc
	private Void _TryRegisterGOAndRaiseSignal() { }
	// RVA: 0x30a3544 VA: 0x75956bb544
	public Void EventOnMedalClicked() { }
	// RVA: 0x30a3704 VA: 0x75956bb704
	public Void EventOnUngroupedMedalClicked() { }
	// RVA: 0x30a3838 VA: 0x75956bb838
	public Void EventOnZoneClicked(String zoneId) { }
	// RVA: 0x30a3984 VA: 0x75956bb984
	private Void _RealEventOnZoneClicked(String zoneId) { }
	// RVA: 0x30a3a34 VA: 0x75956bba34
	public Void EventOnReplayEntryAVG() { }
	// RVA: 0x30a3c1c VA: 0x75956bbc1c
	public Void EventOnShopClicked() { }
	// RVA: 0x30a3d8c VA: 0x75956bbd8c
	public Void EventOnReplicateClicked() { }
	// RVA: 0x30a2670 VA: 0x75956ba670
	private Void _InitTopMenu() { }
	// RVA: 0x30a3e70 VA: 0x75956bbe70
	public Void .ctor() { }
	// RVA: 0x30a3f4c VA: 0x75956bbf4c
	private Void <_PlayTargetAnim>b__20_0() { }
	// RVA: 0x30a3f50 VA: 0x75956bbf50
	private Void <>xLuaBaseProxy_OnLoaded() { }
	// RVA: 0x30a3f58 VA: 0x75956bbf58
	private Void <>xLuaBaseProxy_OnBindToParent() { }
}
```