# RoguelikeCommonOuterBuffSummaryView

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `Text _activeCountText`

- `Text _allCountText`

- `ScrollRect _scrollRect`

- `RoguelikeCommonOuterBuffSummaryMergeView _mergeView`

- `RoguelikeCommonOuterBuffSummaryRawTextView _rawTextView`

- `RoguelikeCommonOuterBuffSummaryDifficultyView _difficultyView`

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
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeCommonOuterBuffSummaryView : DataBinder`1
{
	private Text _activeCountText; // 0x20
	private Text _allCountText; // 0x28
	private ScrollRect _scrollRect; // 0x30
	private RoguelikeCommonOuterBuffSummaryMergeView _mergeView; // 0x38
	private RoguelikeCommonOuterBuffSummaryRawTextView _rawTextView; // 0x40
	private RoguelikeCommonOuterBuffSummaryDifficultyView _difficultyView; // 0x48
	private RectTransform _backBtnRect; // 0x50
	public Action onBackClick; // 0x58
	public const Single INACTIVE_SUMMARY_ALPHA; // 0x0
	private Boolean m_isInited; // 0x60
	private static DelegateBridge __Hotfix0_Reset; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0_OnBackClick; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x26604b4 VA: 0x7594c784b4
	public Void Reset() { }
	// RVA: 0x26656e8 VA: 0x7594c7d6e8
	public override Void OnValueChanged(RoguelikeCommonOuterBuffSummaryProperty property) { }
	// RVA: 0x2665958 VA: 0x7594c7d958
	public Void OnBackClick() { }
	// RVA: 0x266585c VA: 0x7594c7d85c
	private Void _InitIfNot() { }
	// RVA: 0x26659dc VA: 0x7594c7d9dc
	public Void .ctor() { }
}
```