# MissionArchivePlayView

**Namespace:** `Torappu.UI.MissionArchive`


## Fields

- `Image _bkgImage`

- `Image _lctImage`

- `CanvasGroup _rootGroup`

- `Single _fadeDuration`

- `UIAnimationLocation _entryAnimation`

- `Text _subtitleText`

- `CanvasGroup _subtitleGroup`

- `CanvasGroup _hiddenPlayGroup`

- `CanvasGroup _replayGroup`

- `Boolean m_hasInited`

- `Builder m_entryBuilder`

- `UIAnimationTween m_entryTween`

- `UIPageFinder m_finder`

- `String m_cachedNoramlTopicId`

- `String m_cachedNormalNodeId`

- `String m_cachedHiddenTopicId`

- `Action <replayEvent>k__BackingField`


## Properties

- `Text subtitleText`

- `CanvasGroup subtitleGroup`

- `CanvasGroup hiddenPlayGroup`

- `CanvasGroup replayGroup`

- `Action replayEvent`


## Methods

- `Text get_subtitleText()`

- `CanvasGroup get_subtitleGroup()`

- `CanvasGroup get_hiddenPlayGroup()`

- `CanvasGroup get_replayGroup()`

- `Action get_replayEvent()`

- `Void set_replayEvent(Action)`

- `Void OnReplayEvent()`

- `Void Reset()`

- `Tween GenerateShowTween()`

- `Tween GenerateHideTween()`

- `Void _InitIfNot()`

- `Sprite _LoadNodeBkg(String, String)`

- `Sprite _LoadNodeLct(String, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.MissionArchive
public class MissionArchivePlayView : DataBinder`1
{
	private const String BKG_SPRITE_KEY_FORMAT; // 0x0
	private const String LCT_SPRITE_KEY_FORMAT; // 0x0
	private Image _bkgImage; // 0x20
	private Image _lctImage; // 0x28
	private CanvasGroup _rootGroup; // 0x30
	private Single _fadeDuration; // 0x38
	private UIAnimationLocation _entryAnimation; // 0x40
	private Text _subtitleText; // 0x50
	private CanvasGroup _subtitleGroup; // 0x58
	private List`1 _playGroups; // 0x60
	private CanvasGroup _hiddenPlayGroup; // 0x68
	private CanvasGroup _replayGroup; // 0x70
	private GameObject[] _normalPanels; // 0x78
	private GameObject[] _hiddenPanels; // 0x80
	private Boolean m_hasInited; // 0x88
	private Builder m_entryBuilder; // 0x90
	private UIAnimationTween m_entryTween; // 0xb8
	private UIPageFinder m_finder; // 0xc0
	private String m_cachedNoramlTopicId; // 0xd0
	private String m_cachedNormalNodeId; // 0xd8
	private String m_cachedHiddenTopicId; // 0xe0
	private Action <replayEvent>k__BackingField; // 0xe8
	private static DelegateBridge __Hotfix0_get_subtitleText; // 0x0
	private static DelegateBridge __Hotfix0_get_subtitleGroup; // 0x8
	private static DelegateBridge __Hotfix0_get_playGroups; // 0x10
	private static DelegateBridge __Hotfix0_get_hiddenPlayGroup; // 0x18
	private static DelegateBridge __Hotfix0_get_replayGroup; // 0x20
	private static DelegateBridge __Hotfix0_get_replayEvent; // 0x28
	private static DelegateBridge __Hotfix0_set_replayEvent; // 0x30
	private static DelegateBridge __Hotfix0_OnReplayEvent; // 0x38
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x40
	private static DelegateBridge __Hotfix0_Reset; // 0x48
	private static DelegateBridge __Hotfix0_GenerateShowTween; // 0x50
	private static DelegateBridge __Hotfix0_GenerateHideTween; // 0x58
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x60
	private static DelegateBridge __Hotfix0__LoadNodeBkg; // 0x68
	private static DelegateBridge __Hotfix0__LoadNodeLct; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public Text subtitleText { get; }
	public CanvasGroup subtitleGroup { get; }
	public List`1 playGroups { get; }
	public CanvasGroup hiddenPlayGroup { get; }
	public CanvasGroup replayGroup { get; }
	private Action replayEvent { get; set; }

	// RVA: 0x27282b4 VA: 0x7594d402b4
	public Text get_subtitleText() { }
	// RVA: 0x27283a0 VA: 0x7594d403a0
	public CanvasGroup get_subtitleGroup() { }
	// RVA: 0x272848c VA: 0x7594d4048c
	public List`1 get_playGroups() { }
	// RVA: 0x2728578 VA: 0x7594d40578
	public CanvasGroup get_hiddenPlayGroup() { }
	// RVA: 0x2728664 VA: 0x7594d40664
	public CanvasGroup get_replayGroup() { }
	// RVA: 0x272db9c VA: 0x7594d45b9c
	private Action get_replayEvent() { }
	// RVA: 0x2728230 VA: 0x7594d40230
	public Void set_replayEvent(Action value) { }
	// RVA: 0x272dc04 VA: 0x7594d45c04
	public Void OnReplayEvent() { }
	// RVA: 0x272dca0 VA: 0x7594d45ca0
	public override Void OnValueChanged(MissionArchiveViewProperty property) { }
	// RVA: 0x2728b24 VA: 0x7594d40b24
	public Void Reset() { }
	// RVA: 0x272ab38 VA: 0x7594d42b38
	public Tween GenerateShowTween() { }
	// RVA: 0x272b1e0 VA: 0x7594d431e0
	public Tween GenerateHideTween() { }
	// RVA: 0x272df38 VA: 0x7594d45f38
	private Void _InitIfNot() { }
	// RVA: 0x272e038 VA: 0x7594d46038
	private Sprite _LoadNodeBkg(String topicId, String nodeId) { }
	// RVA: 0x272e124 VA: 0x7594d46124
	private Sprite _LoadNodeLct(String topicId, String nodeId) { }
	// RVA: 0x272e210 VA: 0x7594d46210
	public Void .ctor() { }
}
```