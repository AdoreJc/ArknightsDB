# RoguelikeTopicMonthModeView

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `Text _textYear`

- `Text _textMonth`

- `Text _textName`

- `Image _bkgName`

- `Text _textDesc`

- `Image _bkgArchive`

- `Image _bkgAward`

- `Button _btnLeft`

- `Button _btnRight`

- `UIAtlasImage _monthBack`

- `EasyInstancePool _togglePool`

- `GameObject _pnlAwardReceived`

- `GameObject _pnlAwardNotReceived`

- `Image _imgIconBp`

- `RectTransform _itemIconHolder`

- `GameObject _pnlMore`

- `RoguelikeTopicMonthSquadCharPortraitView _charPortraitPrefab`

- `UIItemCard m_itemCard`

- `String m_cachedTopicId`

- `String m_cachedCurrMonthTeamId`

- `RoguelikeTopicMonthSquadModel m_cachedMonthSquadModel`

- `Boolean m_hasInited`


## Methods

- `Void _InitIfNot()`

- `Void _Render(RoguelikeTopicModeViewModel)`

- `Void _RenderToggleGroup(RoguelikeTopicMonthSquadViewModel)`

- `Void _LoadRewardItemIcon(ItemBundle)`

- `Void EventOnOpenArchive()`

- `Void EventOnOpenRewardDetail()`

- `Void EventOnBtnLeftClicked()`

- `Void EventOnBtnRightClicked()`

- `Void <>xLuaBaseProxy_OnValueChanged(RoguelikeTopicModeViewProperty)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicMonthModeView : RoguelikeTopicSubView
{
	private const Int32 CHAR_PORTRAIT_COUNT; // 0x0
	private const Single ITEM_CARD_SCALE; // 0x0
	private Text _textYear; // 0x28
	private Text _textMonth; // 0x30
	private Text _textName; // 0x38
	private Image _bkgName; // 0x40
	private Text _textDesc; // 0x48
	private Image _bkgArchive; // 0x50
	private Image _bkgAward; // 0x58
	private Button _btnLeft; // 0x60
	private Button _btnRight; // 0x68
	private UIAtlasImage _monthBack; // 0x70
	private EasyInstancePool _togglePool; // 0x78
	private GameObject _pnlAwardReceived; // 0x80
	private GameObject _pnlAwardNotReceived; // 0x88
	private Image _imgIconBp; // 0x90
	private RectTransform _itemIconHolder; // 0x98
	private GameObject _pnlMore; // 0xa0
	private RoguelikeTopicMonthSquadCharPortraitView _charPortraitPrefab; // 0xa8
	private RectTransform[] _charPortraitViewHolders; // 0xb0
	private RoguelikeTopicMonthSquadCharPortraitView[] m_charPortraitViews; // 0xb8
	private UIItemCard m_itemCard; // 0xc0
	private String m_cachedTopicId; // 0xc8
	private String m_cachedCurrMonthTeamId; // 0xd0
	private RoguelikeTopicMonthSquadModel m_cachedMonthSquadModel; // 0xd8
	private Boolean m_hasInited; // 0xe0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__Render; // 0x10
	private static DelegateBridge __Hotfix0__RenderToggleGroup; // 0x18
	private static DelegateBridge __Hotfix0__LoadRewardItemIcon; // 0x20
	private static DelegateBridge __Hotfix0_EventOnOpenArchive; // 0x28
	private static DelegateBridge __Hotfix0_EventOnOpenRewardDetail; // 0x30
	private static DelegateBridge __Hotfix0_EventOnBtnLeftClicked; // 0x38
	private static DelegateBridge __Hotfix0_EventOnBtnRightClicked; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x265266c VA: 0x7594c6a66c
	private Void _InitIfNot() { }
	// RVA: 0x2652834 VA: 0x7594c6a834
	public override Void OnValueChanged(RoguelikeTopicModeViewProperty property) { }
	// RVA: 0x26528f8 VA: 0x7594c6a8f8
	public Void _Render(RoguelikeTopicModeViewModel model) { }
	// RVA: 0x26538dc VA: 0x7594c6b8dc
	private Void _RenderToggleGroup(RoguelikeTopicMonthSquadViewModel monthSquadGroup) { }
	// RVA: 0x265302c VA: 0x7594c6b02c
	private Void _LoadRewardItemIcon(ItemBundle itemData) { }
	// RVA: 0x2653ac0 VA: 0x7594c6bac0
	public Void EventOnOpenArchive() { }
	// RVA: 0x2653c8c VA: 0x7594c6bc8c
	public Void EventOnOpenRewardDetail() { }
	// RVA: 0x2653d24 VA: 0x7594c6bd24
	public Void EventOnBtnLeftClicked() { }
	// RVA: 0x2653dc0 VA: 0x7594c6bdc0
	public Void EventOnBtnRightClicked() { }
	// RVA: 0x2653e5c VA: 0x7594c6be5c
	public Void .ctor() { }
	// RVA: 0x2653f08 VA: 0x7594c6bf08
	private Void <>xLuaBaseProxy_OnValueChanged(RoguelikeTopicModeViewProperty P0) { }
}
```