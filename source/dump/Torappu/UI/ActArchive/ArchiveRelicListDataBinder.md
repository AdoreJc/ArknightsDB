# ArchiveRelicListDataBinder

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `ArchiveRelicRecycleAdapter _adapter`

- `LoopVerticalScrollRect _scrollRect`

- `Text _textTitle`

- `Image _imgItem`

- `Text _textUsage`

- `Text _textDesc`

- `Text _textOrderId`

- `Color _attainedColor`

- `Color _unattainedColor`

- `Text _textLockedTitle`

- `GameObject _lockedBg`

- `GameObject _emptyPanel`

- `Text _emptyText`

- `CanvasGroup _textGroup`

- `Text _difficultyDescText`

- `GameObject _switchPanel`

- `SimpleLayoutContent _switchSpotContent`

- `ArchiveRelicController m_controller`

- `Boolean m_hasInited`

- `FilterRule m_cachedRule`

- `Adapter m_spotAdapter`

- `Int32 m_cachedSelectedDifficultyCount`

- `Int32 m_cachedSelectedDifficultyIndex`

- `Int32 m_cachedDefaultDifficultyIndex`

- `Int32 m_cachedSelectLine`

- `ArchiveRelicController <controller>k__BackingField`


## Properties

- `ArchiveRelicController controller`


## Methods

- `ArchiveRelicController get_controller()`

- `Void set_controller(ArchiveRelicController)`

- `Void _InitIfNot()`

- `Void _RenderDetail(ArchiveRelicModel)`

- `Void _RenderNormalDetail(RelicItemModel)`

- `Void _RenderDifficultyDetail(RelicItemModel, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveRelicListDataBinder : DataBinder`1
{
	private const String LOCKED_RELIC_DETAIL_TITLE; // 0x0
	private ArchiveRelicRecycleAdapter _adapter; // 0x20
	private LoopVerticalScrollRect _scrollRect; // 0x28
	private Text _textTitle; // 0x30
	private Image _imgItem; // 0x38
	private Text _textUsage; // 0x40
	private Text _textDesc; // 0x48
	private Text _textOrderId; // 0x50
	private Color _attainedColor; // 0x58
	private Color _unattainedColor; // 0x68
	private Text _textLockedTitle; // 0x78
	private GameObject _lockedBg; // 0x80
	private GameObject _emptyPanel; // 0x88
	private Text _emptyText; // 0x90
	private CanvasGroup _textGroup; // 0x98
	private Text _difficultyDescText; // 0xa0
	private GameObject _switchPanel; // 0xa8
	private SimpleLayoutContent _switchSpotContent; // 0xb0
	private List`1 _sortRuleList; // 0xb8
	private ArchiveRelicController m_controller; // 0xc0
	private Boolean m_hasInited; // 0xc8
	private FilterRule m_cachedRule; // 0xcc
	private Adapter m_spotAdapter; // 0xd0
	private Int32 m_cachedSelectedDifficultyCount; // 0xd8
	private Int32 m_cachedSelectedDifficultyIndex; // 0xdc
	private Int32 m_cachedDefaultDifficultyIndex; // 0xe0
	private Int32 m_cachedSelectLine; // 0xe4
	private ArchiveRelicController <controller>k__BackingField; // 0xe8
	private static DelegateBridge __Hotfix0_get_controller; // 0x0
	private static DelegateBridge __Hotfix0_set_controller; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x18
	private static DelegateBridge __Hotfix0__RenderDetail; // 0x20
	private static DelegateBridge __Hotfix0__RenderNormalDetail; // 0x28
	private static DelegateBridge __Hotfix0__RenderDifficultyDetail; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	private ArchiveRelicController controller { get; set; }

	// RVA: 0x307827c VA: 0x759569027c
	private ArchiveRelicController get_controller() { }
	// RVA: 0x3077e48 VA: 0x759568fe48
	public Void set_controller(ArchiveRelicController value) { }
	// RVA: 0x30782e4 VA: 0x75956902e4
	private Void _InitIfNot() { }
	// RVA: 0x3078538 VA: 0x7595690538
	public override Void OnValueChanged(RelicProperty property) { }
	// RVA: 0x3078ed0 VA: 0x7595690ed0
	private Void _RenderDetail(ArchiveRelicModel model) { }
	// RVA: 0x3079650 VA: 0x7595691650
	private Void _RenderNormalDetail(RelicItemModel detailItem) { }
	// RVA: 0x3079184 VA: 0x7595691184
	private Void _RenderDifficultyDetail(RelicItemModel rootRelic, Int32 index) { }
	// RVA: 0x3079b7c VA: 0x7595691b7c
	public Void .ctor() { }
}
```