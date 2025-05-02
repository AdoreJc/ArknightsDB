# Rl03OuterBuffSummaryView

**Namespace:** `Torappu.UI.RoguelikeTopic.RL03`


## Fields

- `Text _activeCount`

- `ScrollRect _scrollRect`

- `Rl03OuterBuffSummaryMergeView _mergeView`

- `Rl03OuterBuffSummaryRawTextView _rawTextView`

- `Rl03OuterBuffSummaryDifficultyView _difficultyView`

- `RectTransform _backBtnRect`

- `Action onBackClick`

- `Boolean m_isInited`


## Methods

- `Void Reset()`

- `Void OnBackClick()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL03
public class Rl03OuterBuffSummaryView : DataBinder`1, IHotfixable
{
	private Text _activeCount; // 0x20
	private ScrollRect _scrollRect; // 0x28
	private Rl03OuterBuffSummaryMergeView _mergeView; // 0x30
	private Rl03OuterBuffSummaryRawTextView _rawTextView; // 0x38
	private Rl03OuterBuffSummaryDifficultyView _difficultyView; // 0x40
	private RectTransform _backBtnRect; // 0x48
	public Action onBackClick; // 0x50
	public const Single INACTIVE_SUMMARY_ALPHA; // 0x0
	private Boolean m_isInited; // 0x58
	private static DelegateBridge __Hotfix0_Reset; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0_OnBackClick; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x26a9ce0 VA: 0x7594cc1ce0
	public Void Reset() { }
	// RVA: 0x26aeb14 VA: 0x7594cc6b14
	public override Void OnValueChanged(Rl03OuterBuffSummaryProperty property) { }
	// RVA: 0x26aedd0 VA: 0x7594cc6dd0
	public Void OnBackClick() { }
	// RVA: 0x26aecd4 VA: 0x7594cc6cd4
	private Void _InitIfNot() { }
	// RVA: 0x26aee54 VA: 0x7594cc6e54
	public Void .ctor() { }
}
```