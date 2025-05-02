# StageMixStoryOverallItemStateHandler

**Namespace:** `Torappu.UI.Stage.MixStory`


## Fields

- `OverallDisplayFeature m_displayFeature`

- `OverallDisplayFeature m_presentedFeature`

- `Single m_playingPosition`

- `Tween m_playTween`

- `OverallSortMode <sortMode>k__BackingField`


## Properties

- `OverallSortMode sortMode`

- `OverallDisplayFeature displayFeature`

- `OverallDisplayFeature presentedFeature`


## Methods

- `OverallSortMode get_sortMode()`

- `Void set_sortMode(OverallSortMode)`

- `OverallDisplayFeature get_displayFeature()`

- `OverallDisplayFeature get_presentedFeature()`

- `Void UpdateDisplayFeature(OverallDisplayFeature, Boolean)`

- `Void _KillPlayTweenIfExisted()`

- `Void _StartPlayTween()`

- `Single _PlayGetter()`

- `Void _PlaySetter(Single)`

- `Void _UpdatePresentingFeature()`

- `Tween GenerateSyncTweenForItem(UIAnimationLocation)`

- `Tween GenerateSyncTweenForPanel(OverallDisplayFeature, CanvasGroup)`

- `Tween _GenerateSyncTweenForActivePanel(CanvasGroup)`

- `Tween _GenerateSyncTweenForInactivePanel(CanvasGroup)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.MixStory
public class StageMixStoryOverallItemStateHandler : IHotfixable
{
	private readonly Single m_switchHalfTime; // 0x10
	private OverallDisplayFeature m_displayFeature; // 0x14
	private OverallDisplayFeature m_presentedFeature; // 0x18
	private Single m_playingPosition; // 0x1c
	private Tween m_playTween; // 0x20
	private OverallSortMode <sortMode>k__BackingField; // 0x28
	private static DelegateBridge __Hotfix0_get_sortMode; // 0x0
	private static DelegateBridge __Hotfix0_set_sortMode; // 0x8
	private static DelegateBridge __Hotfix0_get_displayFeature; // 0x10
	private static DelegateBridge __Hotfix0_get_presentedFeature; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20
	private static DelegateBridge __Hotfix0_UpdateDisplayFeature; // 0x28
	private static DelegateBridge __Hotfix0__KillPlayTweenIfExisted; // 0x30
	private static DelegateBridge __Hotfix0__StartPlayTween; // 0x38
	private static DelegateBridge __Hotfix0__PlayGetter; // 0x40
	private static DelegateBridge __Hotfix0__PlaySetter; // 0x48
	private static DelegateBridge __Hotfix0__UpdatePresentingFeature; // 0x50
	private static DelegateBridge __Hotfix0_GenerateSyncTweenForItem; // 0x58
	private static DelegateBridge __Hotfix0_GenerateSyncTweenForPanel; // 0x60
	private static DelegateBridge __Hotfix0__GenerateSyncTweenForActivePanel; // 0x68
	private static DelegateBridge __Hotfix0__GenerateSyncTweenForInactivePanel; // 0x70

	public OverallSortMode sortMode { get; set; }
	public OverallDisplayFeature displayFeature { get; }
	public OverallDisplayFeature presentedFeature { get; }

	// RVA: 0x2ffb75c VA: 0x759561375c
	public OverallSortMode get_sortMode() { }
	// RVA: 0x2ffb7c4 VA: 0x75956137c4
	public Void set_sortMode(OverallSortMode value) { }
	// RVA: 0x2ffaa80 VA: 0x7595612a80
	public OverallDisplayFeature get_displayFeature() { }
	// RVA: 0x2ffaa18 VA: 0x7595612a18
	public OverallDisplayFeature get_presentedFeature() { }
	// RVA: 0x2ffb840 VA: 0x7595613840
	public Void .ctor(Single switchHalfTime) { }
	// RVA: 0x2ffb8d0 VA: 0x75956138d0
	public Void UpdateDisplayFeature(OverallDisplayFeature feature, Boolean fastMode) { }
	// RVA: 0x2ffb9f0 VA: 0x75956139f0
	private Void _KillPlayTweenIfExisted() { }
	// RVA: 0x2ffba70 VA: 0x7595613a70
	private Void _StartPlayTween() { }
	// RVA: 0x2ffbd84 VA: 0x7595613d84
	private Single _PlayGetter() { }
	// RVA: 0x2ffbdec VA: 0x7595613dec
	private Void _PlaySetter(Single value) { }
	// RVA: 0x2ffbe68 VA: 0x7595613e68
	private Void _UpdatePresentingFeature() { }
	// RVA: 0x2ffa294 VA: 0x7595612294
	public Tween GenerateSyncTweenForItem(UIAnimationLocation location) { }
	// RVA: 0x2ffa92c VA: 0x759561292c
	public Tween GenerateSyncTweenForPanel(OverallDisplayFeature feature, CanvasGroup canvasGroup) { }
	// RVA: 0x2ffbed4 VA: 0x7595613ed4
	private Tween _GenerateSyncTweenForActivePanel(CanvasGroup canvasGroup) { }
	// RVA: 0x2ffc0b8 VA: 0x75956140b8
	private Tween _GenerateSyncTweenForInactivePanel(CanvasGroup canvasGroup) { }
}
```