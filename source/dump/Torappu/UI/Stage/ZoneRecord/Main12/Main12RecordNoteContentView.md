# Main12RecordNoteContentView

**Namespace:** `Torappu.UI.Stage.ZoneRecord.Main12`


## Fields

- `GameObject _objUnlockTipsPart`

- `RectTransform _transUnlockTipsPart`

- `GameObject _objTitlePart`

- `RectTransform _transTitlePart`

- `GameObject _objSplitLinePart`

- `GameObject _objTxtPart`

- `GameObject _objEasyPart`

- `RectTransform _transEasyPart`

- `GameObject _objToughPart`

- `RectTransform _transToughPart`

- `GameObject _objToughSelectPart`

- `GameObject _objHardPart`

- `RectTransform _transHardPart`

- `Main12RecordNoteUnlockTipsItemView _noteUnlockTipsItemPrefab`

- `Text _txtTitle1`

- `Text _txtTitle2`

- `RectTransform _transTypingMask`

- `Image _imgEasy`

- `Image _imgTough`

- `Text _txtTips`

- `Text _txtContent`

- `Image _imgHard`

- `UIAnimationLocation _toughSelectAnim`

- `ScrollRect _scrollRectTxtContent`

- `CanvasGroup _canvasGroupTitlePart`

- `CanvasGroup _canvasGroupUnlockTipsPart`

- `CanvasGroup _canvasGroupEasyPart`

- `CanvasGroup _canvasGroupToughPart`

- `CanvasGroup _canvasGroupHardPart`

- `CanvasGroup _canvasGroupSplitPart`

- `Main12ZoneRecordController <controller>k__BackingField`

- `Boolean m_hasInited`

- `String m_cachedRecordId`

- `Main12RecordNoteUnlockTipsItemView m_noteUnlockTipsItem`

- `TweenWrapper m_enterShowTween`

- `DiffStatusUIStyle m_style`

- `AnimationSwitchTween m_toughSelectSwitchTween`


## Properties

- `Main12ZoneRecordController controller`


## Methods

- `Main12ZoneRecordController get_controller()`

- `Void set_controller(Main12ZoneRecordController)`

- `Void Render(ZoneRecordViewModel)`

- `Void _InitIfNot()`

- `Void _SetDiffImg(Image, String)`

- `DiffStatusUIStyle _ApplyUIStyleByStatus(ZoneRecordDiffStatus)`

- `DiffStatusUIStyle _TryGetStyleByStatus(ZoneRecordDiffStatus)`

- `Void _ResetEnterTween()`

- `Void _ShowContentEnterTween()`

- `Void _ResetTypingTxtMask()`

- `Void _ShowToughDetail(Boolean)`

- `Void ResetContentViewBeforeClose()`

- `Void EventOnToughDetailClick()`

- `Void EventOnToughDetailUnselect()`

- `Vector2 <_ShowContentEnterTween>b__56_0()`

- `Void <_ShowContentEnterTween>b__56_1(Vector2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.ZoneRecord.Main12
public class Main12RecordNoteContentView : MonoBehaviour, IHotfixable
{
	private List`1 _styles; // 0x18
	private GameObject _objUnlockTipsPart; // 0x20
	private RectTransform _transUnlockTipsPart; // 0x28
	private GameObject _objTitlePart; // 0x30
	private RectTransform _transTitlePart; // 0x38
	private GameObject _objSplitLinePart; // 0x40
	private GameObject _objTxtPart; // 0x48
	private GameObject _objEasyPart; // 0x50
	private RectTransform _transEasyPart; // 0x58
	private GameObject _objToughPart; // 0x60
	private RectTransform _transToughPart; // 0x68
	private GameObject _objToughSelectPart; // 0x70
	private GameObject _objHardPart; // 0x78
	private RectTransform _transHardPart; // 0x80
	private Main12RecordNoteUnlockTipsItemView _noteUnlockTipsItemPrefab; // 0x88
	private Text _txtTitle1; // 0x90
	private Text _txtTitle2; // 0x98
	private RectTransform _transTypingMask; // 0xa0
	private Image _imgEasy; // 0xa8
	private Image _imgTough; // 0xb0
	private Text _txtTips; // 0xb8
	private Text _txtContent; // 0xc0
	private Image _imgHard; // 0xc8
	private UIAnimationLocation _toughSelectAnim; // 0xd0
	private ScrollRect _scrollRectTxtContent; // 0xe0
	private CanvasGroup _canvasGroupTitlePart; // 0xe8
	private CanvasGroup _canvasGroupUnlockTipsPart; // 0xf0
	private CanvasGroup _canvasGroupEasyPart; // 0xf8
	private CanvasGroup _canvasGroupToughPart; // 0x100
	private CanvasGroup _canvasGroupHardPart; // 0x108
	private CanvasGroup _canvasGroupSplitPart; // 0x110
	private Main12ZoneRecordController <controller>k__BackingField; // 0x118
	private Boolean m_hasInited; // 0x120
	private String m_cachedRecordId; // 0x128
	private Main12RecordNoteUnlockTipsItemView m_noteUnlockTipsItem; // 0x130
	private TweenWrapper m_enterShowTween; // 0x138
	private DiffStatusUIStyle m_style; // 0x140
	private AnimationSwitchTween m_toughSelectSwitchTween; // 0x180
	private const Single TITLE_SHOW_DELAY; // 0x0
	private const Single TITLE_SHOW_DUR; // 0x0
	private const Single PIC_PART_SHOW_DUR; // 0x0
	private const Single DOWN_PART_SHOW_DELAY; // 0x0
	private const Single TYPING_TXT_SHOW_DUR; // 0x0
	private static readonly Vector2 TYPING_INIT_SIZE; // 0x0
	private static readonly Vector2 TYPING_FINAL_SIZE; // 0x8
	private static readonly DiffStatusUIStyle DEFAULT_STYLE; // 0x10
	private static DelegateBridge __Hotfix0_get_controller; // 0x50
	private static DelegateBridge __Hotfix0_set_controller; // 0x58
	private static DelegateBridge __Hotfix0_Render; // 0x60
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x68
	private static DelegateBridge __Hotfix0__SetDiffImg; // 0x70
	private static DelegateBridge __Hotfix0__ApplyUIStyleByStatus; // 0x78
	private static DelegateBridge __Hotfix0__TryGetStyleByStatus; // 0x80
	private static DelegateBridge __Hotfix0__ResetEnterTween; // 0x88
	private static DelegateBridge __Hotfix0__ShowContentEnterTween; // 0x90
	private static DelegateBridge __Hotfix0__ResetTypingTxtMask; // 0x98
	private static DelegateBridge __Hotfix0__ShowToughDetail; // 0xa0
	private static DelegateBridge __Hotfix0_ResetContentViewBeforeClose; // 0xa8
	private static DelegateBridge __Hotfix0_EventOnToughDetailClick; // 0xb0
	private static DelegateBridge __Hotfix0_EventOnToughDetailUnselect; // 0xb8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc0

	public Main12ZoneRecordController controller { get; set; }

	// RVA: 0x2fce9b0 VA: 0x75955e69b0
	public Main12ZoneRecordController get_controller() { }
	// RVA: 0x2fcea28 VA: 0x75955e6a28
	public Void set_controller(Main12ZoneRecordController value) { }
	// RVA: 0x2fceabc VA: 0x75955e6abc
	public Void Render(ZoneRecordViewModel viewModel) { }
	// RVA: 0x2fcefe8 VA: 0x75955e6fe8
	private Void _InitIfNot() { }
	// RVA: 0x2fcf778 VA: 0x75955e7778
	private Void _SetDiffImg(Image img, String picName) { }
	// RVA: 0x2fcf20c VA: 0x75955e720c
	private DiffStatusUIStyle _ApplyUIStyleByStatus(ZoneRecordDiffStatus status) { }
	// RVA: 0x2fcfc64 VA: 0x75955e7c64
	private DiffStatusUIStyle _TryGetStyleByStatus(ZoneRecordDiffStatus status) { }
	// RVA: 0x2fcf120 VA: 0x75955e7120
	private Void _ResetEnterTween() { }
	// RVA: 0x2fcf844 VA: 0x75955e7844
	private Void _ShowContentEnterTween() { }
	// RVA: 0x2fcfe08 VA: 0x75955e7e08
	private Void _ResetTypingTxtMask() { }
	// RVA: 0x2fcfec0 VA: 0x75955e7ec0
	private Void _ShowToughDetail(Boolean show) { }
	// RVA: 0x2fcff5c VA: 0x75955e7f5c
	public Void ResetContentViewBeforeClose() { }
	// RVA: 0x2fd0004 VA: 0x75955e8004
	public Void EventOnToughDetailClick() { }
	// RVA: 0x2fd0080 VA: 0x75955e8080
	public Void EventOnToughDetailUnselect() { }
	// RVA: 0x2fd00fc VA: 0x75955e80fc
	public Void .ctor() { }
	// RVA: 0x2fd01d0 VA: 0x75955e81d0
	private static Void .cctor() { }
	// RVA: 0x2fd0244 VA: 0x75955e8244
	private Vector2 <_ShowContentEnterTween>b__56_0() { }
	// RVA: 0x2fd0260 VA: 0x75955e8260
	private Void <_ShowContentEnterTween>b__56_1(Vector2 value) { }
}
```