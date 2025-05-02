# RoguelikeTopicBattlePassDetailState

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `RectTransform _backBtn`

- `UIAtlasImage _imgIcon`

- `GameObject _pnlPlaceholder`

- `GameObject _pnlBpPurchase`

- `GameObject _pnlBpPurchaseDisabled`

- `GameObject _pnlBpPurchaseEnabled`

- `GameObject _pnlBtnBpPurchaseEnabled`

- `GameObject _pnlBtnBpPurchaseDisabled`

- `Text _textPurchase`

- `UIAtlasImage _imgBtnPurchase`

- `Text _textMonthTeam`

- `UIAtlasImage _imgTeamIcon`

- `Text _textPromoteCaption`

- `Text _textNormalModeCaption`

- `StateBean m_stateBean`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void _UpdateStyle(RoguelikeTopicBattlePassStyle)`

- `Void _OnJumpToPurchaseState(IStateBean)`

- `Void _RenderView()`

- `Void OnBackClick()`

- `Void OnBpPurchaseClick()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicBattlePassDetailState : PopupFloatState
{
	private static readonly Color BP_PURCHASE_TEXT_COLOR_AVAILABLE; // 0x0
	private static readonly Color BP_PURCHASE_TEXT_COLOR_DISABLED; // 0x10
	private RectTransform _backBtn; // 0x70
	private UIAtlasImage _imgIcon; // 0x78
	private GameObject _pnlPlaceholder; // 0x80
	private GameObject _pnlBpPurchase; // 0x88
	private GameObject _pnlBpPurchaseDisabled; // 0x90
	private GameObject _pnlBpPurchaseEnabled; // 0x98
	private GameObject _pnlBtnBpPurchaseEnabled; // 0xa0
	private GameObject _pnlBtnBpPurchaseDisabled; // 0xa8
	private Text _textPurchase; // 0xb0
	private Text[] _textLabelDescList; // 0xb8
	private UIAtlasImage _imgBtnPurchase; // 0xc0
	private Text _textMonthTeam; // 0xc8
	private UIAtlasImage _imgTeamIcon; // 0xd0
	private Text _textPromoteCaption; // 0xd8
	private Text _textNormalModeCaption; // 0xe0
	private StateBean m_stateBean; // 0xe8
	private Boolean m_isInited; // 0xf0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x28
	private static DelegateBridge __Hotfix0_OnEnter; // 0x30
	private static DelegateBridge __Hotfix0__UpdateStyle; // 0x38
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x40
	private static DelegateBridge __Hotfix0__OnJumpToPurchaseState; // 0x48
	private static DelegateBridge __Hotfix0__RenderView; // 0x50
	private static DelegateBridge __Hotfix0_OnBackClick; // 0x58
	private static DelegateBridge __Hotfix0_OnBpPurchaseClick; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68


	// RVA: 0x26361bc VA: 0x7594c4e1bc
	private Void _InitIfNot() { }
	// RVA: 0x26362d4 VA: 0x7594c4e2d4
	public override IStateBean GetCacheBean() { }
	// RVA: 0x263634c VA: 0x7594c4e34c
	protected override Void OnEnter() { }
	// RVA: 0x26365f0 VA: 0x7594c4e5f0
	private Void _UpdateStyle(RoguelikeTopicBattlePassStyle topicStyle) { }
	// RVA: 0x26369f4 VA: 0x7594c4e9f4
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2636b7c VA: 0x7594c4eb7c
	private Void _OnJumpToPurchaseState(IStateBean stateBean) { }
	// RVA: 0x2636834 VA: 0x7594c4e834
	private Void _RenderView() { }
	// RVA: 0x2636d24 VA: 0x7594c4ed24
	public Void OnBackClick() { }
	// RVA: 0x2636da8 VA: 0x7594c4eda8
	public Void OnBpPurchaseClick() { }
	// RVA: 0x2637090 VA: 0x7594c4f090
	public Void .ctor() { }
	// RVA: 0x26371bc VA: 0x7594c4f1bc
	private static Void .cctor() { }
	// RVA: 0x263721c VA: 0x7594c4f21c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2637224 VA: 0x7594c4f224
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```