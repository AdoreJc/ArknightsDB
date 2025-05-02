# MissionArchivePlayer

**Namespace:** `Torappu.UI.MissionArchive`


## Fields

- `Text <subTitleText>k__BackingField`

- `CanvasGroup <subTitleGroup>k__BackingField`

- `CanvasGroup <hiddenPlayGroup>k__BackingField`

- `CanvasGroup <replayGroup>k__BackingField`

- `MissionArchiveExteriorPlayer <exteriorPlayer>k__BackingField`

- `String <audioFxOnPlayEnd>k__BackingField`

- `Boolean m_hasInited`

- `FadeSwitchTween m_hiddenPlaySwitchTween`

- `FadeSwitchTween m_replaySwitchTween`

- `Boolean m_isPlaying`

- `Tween m_playSequence`

- `Int32 m_playingIndex`


## Properties

- `Text subTitleText`

- `CanvasGroup subTitleGroup`

- `CanvasGroup hiddenPlayGroup`

- `CanvasGroup replayGroup`

- `MissionArchiveExteriorPlayer exteriorPlayer`

- `String audioFxOnPlayEnd`


## Methods

- `Text get_subTitleText()`

- `Void set_subTitleText(Text)`

- `CanvasGroup get_subTitleGroup()`

- `Void set_subTitleGroup(CanvasGroup)`

- `Void set_playGroups(List`1)`

- `CanvasGroup get_hiddenPlayGroup()`

- `Void set_hiddenPlayGroup(CanvasGroup)`

- `CanvasGroup get_replayGroup()`

- `Void set_replayGroup(CanvasGroup)`

- `MissionArchiveExteriorPlayer get_exteriorPlayer()`

- `Void set_exteriorPlayer(MissionArchiveExteriorPlayer)`

- `String get_audioFxOnPlayEnd()`

- `Void set_audioFxOnPlayEnd(String)`

- `Void Reset()`

- `Void Play(List`1, Boolean)`

- `Void Stop()`

- `Void _InitIfNot()`

- `Void _PlayClipIfCan()`

- `Void _StopInProgress()`

- `Void _StopSubtitleTweenIfNeed()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.MissionArchive
public class MissionArchivePlayer : IHotfixable
{
	private const Single SUB_TITLE_FADE_TIME; // 0x0
	private const Single SUB_TITLE_FALLBACK_DURATION; // 0x0
	private Text <subTitleText>k__BackingField; // 0x10
	private CanvasGroup <subTitleGroup>k__BackingField; // 0x18
	private List`1 <playGroups>k__BackingField; // 0x20
	private CanvasGroup <hiddenPlayGroup>k__BackingField; // 0x28
	private CanvasGroup <replayGroup>k__BackingField; // 0x30
	private MissionArchiveExteriorPlayer <exteriorPlayer>k__BackingField; // 0x38
	private String <audioFxOnPlayEnd>k__BackingField; // 0x40
	private Boolean m_hasInited; // 0x48
	private readonly List`1 m_playSwitchTweens; // 0x50
	private FadeSwitchTween m_hiddenPlaySwitchTween; // 0x58
	private FadeSwitchTween m_replaySwitchTween; // 0x60
	private Boolean m_isPlaying; // 0x68
	private Tween m_playSequence; // 0x70
	private readonly List`1 m_playingClips; // 0x78
	private Int32 m_playingIndex; // 0x80
	private static DelegateBridge __Hotfix0_get_subTitleText; // 0x0
	private static DelegateBridge __Hotfix0_set_subTitleText; // 0x8
	private static DelegateBridge __Hotfix0_get_subTitleGroup; // 0x10
	private static DelegateBridge __Hotfix0_set_subTitleGroup; // 0x18
	private static DelegateBridge __Hotfix0_get_playGroups; // 0x20
	private static DelegateBridge __Hotfix0_set_playGroups; // 0x28
	private static DelegateBridge __Hotfix0_get_hiddenPlayGroup; // 0x30
	private static DelegateBridge __Hotfix0_set_hiddenPlayGroup; // 0x38
	private static DelegateBridge __Hotfix0_get_replayGroup; // 0x40
	private static DelegateBridge __Hotfix0_set_replayGroup; // 0x48
	private static DelegateBridge __Hotfix0_get_exteriorPlayer; // 0x50
	private static DelegateBridge __Hotfix0_set_exteriorPlayer; // 0x58
	private static DelegateBridge __Hotfix0_get_audioFxOnPlayEnd; // 0x60
	private static DelegateBridge __Hotfix0_set_audioFxOnPlayEnd; // 0x68
	private static DelegateBridge __Hotfix0_Reset; // 0x70
	private static DelegateBridge __Hotfix0_Play; // 0x78
	private static DelegateBridge __Hotfix0_Stop; // 0x80
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x88
	private static DelegateBridge __Hotfix0__PlayClipIfCan; // 0x90
	private static DelegateBridge __Hotfix0__StopInProgress; // 0x98
	private static DelegateBridge __Hotfix0__StopSubtitleTweenIfNeed; // 0xa0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa8

	private Text subTitleText { get; set; }
	private CanvasGroup subTitleGroup { get; set; }
	private List`1 playGroups { get; set; }
	private CanvasGroup hiddenPlayGroup { get; set; }
	private CanvasGroup replayGroup { get; set; }
	private MissionArchiveExteriorPlayer exteriorPlayer { get; set; }
	private String audioFxOnPlayEnd { get; set; }

	// RVA: 0x272cfd0 VA: 0x7594d44fd0
	private Text get_subTitleText() { }
	// RVA: 0x272831c VA: 0x7594d4031c
	public Void set_subTitleText(Text value) { }
	// RVA: 0x272d038 VA: 0x7594d45038
	private CanvasGroup get_subTitleGroup() { }
	// RVA: 0x2728408 VA: 0x7594d40408
	public Void set_subTitleGroup(CanvasGroup value) { }
	// RVA: 0x272d0a0 VA: 0x7594d450a0
	private List`1 get_playGroups() { }
	// RVA: 0x27284f4 VA: 0x7594d404f4
	public Void set_playGroups(List`1 value) { }
	// RVA: 0x272d108 VA: 0x7594d45108
	private CanvasGroup get_hiddenPlayGroup() { }
	// RVA: 0x27285e0 VA: 0x7594d405e0
	public Void set_hiddenPlayGroup(CanvasGroup value) { }
	// RVA: 0x272d170 VA: 0x7594d45170
	private CanvasGroup get_replayGroup() { }
	// RVA: 0x27286cc VA: 0x7594d406cc
	public Void set_replayGroup(CanvasGroup value) { }
	// RVA: 0x272d1d8 VA: 0x7594d451d8
	private MissionArchiveExteriorPlayer get_exteriorPlayer() { }
	// RVA: 0x2728750 VA: 0x7594d40750
	public Void set_exteriorPlayer(MissionArchiveExteriorPlayer value) { }
	// RVA: 0x272d240 VA: 0x7594d45240
	private String get_audioFxOnPlayEnd() { }
	// RVA: 0x27287d4 VA: 0x7594d407d4
	public Void set_audioFxOnPlayEnd(String value) { }
	// RVA: 0x272a8ec VA: 0x7594d428ec
	public Void Reset() { }
	// RVA: 0x2729bc0 VA: 0x7594d41bc0
	public Void Play(List`1 clips, Boolean isHidden) { }
	// RVA: 0x2729014 VA: 0x7594d41014
	public Void Stop() { }
	// RVA: 0x272d2a8 VA: 0x7594d452a8
	private Void _InitIfNot() { }
	// RVA: 0x272d668 VA: 0x7594d45668
	private Void _PlayClipIfCan() { }
	// RVA: 0x272d92c VA: 0x7594d4592c
	private Void _StopInProgress() { }
	// RVA: 0x272d5d8 VA: 0x7594d455d8
	private Void _StopSubtitleTweenIfNeed() { }
	// RVA: 0x272a1e0 VA: 0x7594d421e0
	public Void .ctor() { }
}
```