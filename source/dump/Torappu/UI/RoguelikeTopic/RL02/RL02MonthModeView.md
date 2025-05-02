# RL02MonthModeView

**Namespace:** `Torappu.UI.RoguelikeTopic.RL02`


## Fields

- `GameObject _pnlAwardReceived`

- `GameObject _pnlAwardNotReceived`

- `RectTransform _itemIconHolder`

- `GameObject _pnlMore`

- `Image _imgIconBp`

- `EasyInstancePool _togglePool`

- `Button _btnLeft`

- `Button _btnRight`

- `UIDynImage _dynImgChar`

- `Image _rarityImg`

- `Image _professionImg`

- `Text _charName`

- `Text _textDesc`

- `Single _rewardItemScale`

- `UIAnimationLocation _animSwitch`

- `Boolean m_hasInited`

- `RoguelikeTopicModeViewModel m_cachedModeViewModel`

- `RoguelikeTopicMonthSquadModel m_cachedMonthSquadModel`

- `RoguelikeTopicMonthSquadTeamChar m_cachedMonthCharModel`

- `String m_cachedTopicId`

- `String m_cachedCurrMonthTeamId`

- `UIItemCard m_itemCard`

- `AutoPackSpriteHub m_charSpriteHub`

- `Tween m_tween`


## Methods

- `Void _Render(RoguelikeTopicModeViewModel)`

- `Void _UpdateMonthSquadView()`

- `Void _InitIfNot()`

- `Void _RenderToggleGroup(RoguelikeTopicMonthSquadViewModel)`

- `Void _LoadRewardItemIcon(ItemBundle)`

- `Void EventOnOpenArchive()`

- `Void EventOnOpenRewardDetail()`

- `Void EventOnBtnLeftClicked()`

- `Void EventOnBtnRightClicked()`

- `Void OnBtnCharProtraitClicked()`

- `Void <>xLuaBaseProxy_OnValueChanged(RoguelikeTopicModeViewProperty)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL02
public class RL02MonthModeView : RoguelikeTopicSubView
{
	private GameObject _pnlAwardReceived; // 0x28
	private GameObject _pnlAwardNotReceived; // 0x30
	private RectTransform _itemIconHolder; // 0x38
	private GameObject _pnlMore; // 0x40
	private Image _imgIconBp; // 0x48
	private EasyInstancePool _togglePool; // 0x50
	private Button _btnLeft; // 0x58
	private Button _btnRight; // 0x60
	private UIDynImage _dynImgChar; // 0x68
	private Image _rarityImg; // 0x70
	private Image _professionImg; // 0x78
	private Text _charName; // 0x80
	private Text _textDesc; // 0x88
	private Single _rewardItemScale; // 0x90
	private UIAnimationLocation _animSwitch; // 0x98
	private Boolean m_hasInited; // 0xa8
	private RoguelikeTopicModeViewModel m_cachedModeViewModel; // 0xb0
	private RoguelikeTopicMonthSquadModel m_cachedMonthSquadModel; // 0xb8
	private RoguelikeTopicMonthSquadTeamChar m_cachedMonthCharModel; // 0xc0
	private String m_cachedTopicId; // 0xc8
	private String m_cachedCurrMonthTeamId; // 0xd0
	private UIItemCard m_itemCard; // 0xd8
	private AutoPackSpriteHub m_charSpriteHub; // 0xe0
	private Tween m_tween; // 0xe8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__Render; // 0x8
	private static DelegateBridge __Hotfix0__UpdateMonthSquadView; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__RenderToggleGroup; // 0x20
	private static DelegateBridge __Hotfix0__LoadRewardItemIcon; // 0x28
	private static DelegateBridge __Hotfix0_EventOnOpenArchive; // 0x30
	private static DelegateBridge __Hotfix0_EventOnOpenRewardDetail; // 0x38
	private static DelegateBridge __Hotfix0_EventOnBtnLeftClicked; // 0x40
	private static DelegateBridge __Hotfix0_EventOnBtnRightClicked; // 0x48
	private static DelegateBridge __Hotfix0_OnBtnCharProtraitClicked; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x26b9444 VA: 0x7594cd1444
	public override Void OnValueChanged(RoguelikeTopicModeViewProperty property) { }
	// RVA: 0x26b94fc VA: 0x7594cd14fc
	private Void _Render(RoguelikeTopicModeViewModel modeViewModel) { }
	// RVA: 0x26b9958 VA: 0x7594cd1958
	private Void _UpdateMonthSquadView() { }
	// RVA: 0x26b986c VA: 0x7594cd186c
	private Void _InitIfNot() { }
	// RVA: 0x26b9d30 VA: 0x7594cd1d30
	private Void _RenderToggleGroup(RoguelikeTopicMonthSquadViewModel monthSquadGroup) { }
	// RVA: 0x26b9f1c VA: 0x7594cd1f1c
	private Void _LoadRewardItemIcon(ItemBundle itemData) { }
	// RVA: 0x26ba1b8 VA: 0x7594cd21b8
	public Void EventOnOpenArchive() { }
	// RVA: 0x26ba384 VA: 0x7594cd2384
	public Void EventOnOpenRewardDetail() { }
	// RVA: 0x26ba41c VA: 0x7594cd241c
	public Void EventOnBtnLeftClicked() { }
	// RVA: 0x26ba4b8 VA: 0x7594cd24b8
	public Void EventOnBtnRightClicked() { }
	// RVA: 0x26ba554 VA: 0x7594cd2554
	public Void OnBtnCharProtraitClicked() { }
	// RVA: 0x26ba66c VA: 0x7594cd266c
	public Void .ctor() { }
	// RVA: 0x26ba6e8 VA: 0x7594cd26e8
	private Void <>xLuaBaseProxy_OnValueChanged(RoguelikeTopicModeViewProperty P0) { }
}
```