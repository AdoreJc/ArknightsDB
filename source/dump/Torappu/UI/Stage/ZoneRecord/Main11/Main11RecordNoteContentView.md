# Main11RecordNoteContentView

**Namespace:** `Torappu.UI.Stage.ZoneRecord.Main11`


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

- `Main11RecordNoteUnlockTipsItemView _noteUnlockTipsItemPrefab`

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

- `Main11ZoneRecordController <controller>k__BackingField`

- `Boolean m_hasInited`

- `String m_cachedRecordId`

- `Main11RecordNoteUnlockTipsItemView m_noteUnlockTipsItem`

- `TweenWrapper m_enterShowTween`

- `DiffStatusUIStyle m_style`

- `AnimationSwitchTween m_toughSelectSwitchTween`


## Properties

- `Main11ZoneRecordController controller`


## Methods

- `Main11ZoneRecordController get_controller()`

- `Void set_controller(Main11ZoneRecordController)`

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
// Namespace : Torappu.UI.Stage.ZoneRecord.Main11
public class Main11RecordNoteContentView : MonoBehaviour, IHotfixable
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
	private Main11RecordNoteUnlockTipsItemView _noteUnlockTipsItemPrefab; // 0x88
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
	private Main11ZoneRecordController <controller>k__BackingField; // 0x118
	private Boolean m_hasInited; // 0x120
	private String m_cachedRecordId; // 0x128
	private Main11RecordNoteUnlockTipsItemView m_noteUnlockTipsItem; // 0x130
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

	public Main11ZoneRecordController controller { get; set; }

	// RVA: 0x2fd6444 VA: 0x75955ee444
	public Main11ZoneRecordController get_controller() { }
	// RVA: 0x2fd64bc VA: 0x75955ee4bc
	public Void set_controller(Main11ZoneRecordController value) { }
	// RVA: 0x2fd6550 VA: 0x75955ee550
	public Void Render(ZoneRecordViewModel viewModel) { }
	// RVA: 0x2fd6a80 VA: 0x75955eea80
	private Void _InitIfNot() { }
	// RVA: 0x2fd6f98 VA: 0x75955eef98
	private Void _SetDiffImg(Image img, String picName) { }
	// RVA: 0x2fd6ca4 VA: 0x75955eeca4
	private DiffStatusUIStyle _ApplyUIStyleByStatus(ZoneRecordDiffStatus status) { }
	// RVA: 0x2fd7484 VA: 0x75955ef484
	private DiffStatusUIStyle _TryGetStyleByStatus(ZoneRecordDiffStatus status) { }
	// RVA: 0x2fd6bb8 VA: 0x75955eebb8
	private Void _ResetEnterTween() { }
	// RVA: 0x2fd7064 VA: 0x75955ef064
	private Void _ShowContentEnterTween() { }
	// RVA: 0x2fd7628 VA: 0x75955ef628
	private Void _ResetTypingTxtMask() { }
	// RVA: 0x2fd76e0 VA: 0x75955ef6e0
	private Void _ShowToughDetail(Boolean show) { }
	// RVA: 0x2fd777c VA: 0x75955ef77c
	public Void ResetContentViewBeforeClose() { }
	// RVA: 0x2fd7824 VA: 0x75955ef824
	public Void EventOnToughDetailClick() { }
	// RVA: 0x2fd78a0 VA: 0x75955ef8a0
	public Void EventOnToughDetailUnselect() { }
	// RVA: 0x2fd791c VA: 0x75955ef91c
	public Void .ctor() { }
	// RVA: 0x2fd79f0 VA: 0x75955ef9f0
	private static Void .cctor() { }
	// RVA: 0x2fd7a64 VA: 0x75955efa64
	private Vector2 <_ShowContentEnterTween>b__56_0() { }
	// RVA: 0x2fd7a80 VA: 0x75955efa80
	private Void <_ShowContentEnterTween>b__56_1(Vector2 value) { }
}
```