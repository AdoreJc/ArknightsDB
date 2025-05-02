# Act1VAutoChessChessShopState

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Act1VAutoChessChessShopMainView _mainView`

- `Boolean m_inited`

- `Act1VAutoChessChessShopStateBean m_stateBean`

- `UICompDialogMgr m_dialogMgr`

- `InputParam m_inputParamsToCharSelectState`

- `Act1VAutoChessCharShopChessData m_diyCharShopChessDataToCharSelectState`

- `String m_needVoiceChar`

- `Act1VAutoChessFriendAssistPlugin m_friendAssistPlugin`

- `FocusInput m_detailCharListFocusInput`


## Methods

- `Void _RegisterFromCommonFriendAssistState(IStateBean)`

- `Void _RegisterToCommonFriendAssistState(IStateBean)`

- `Void _RegisterToCharSelectState(IStateBean)`

- `Void _RegisterFromCharSelectState(IStateBean)`

- `Void _RegisterFromQuickAssistState(IStateBean)`

- `Void _InitIfNot()`

- `Void _OnReturnClick()`

- `Act1VAutoChessFriendAssistPlugin _GetFriendAssistPlugin()`

- `Void _SendSetChessPoolDiyCharsRequest(List`1, Int32)`

- `Void _OnSetChessPoolDiyCharsSuc(Act1VAutoChessSetChessPoolDiyCharResponse)`

- `Void _PlayCharVoice(Act1VAutoChessChessShopViewModel)`

- `Void _CheckVoiceChar(TemplateCharSelectMainViewModel)`

- `Boolean _AlreadyInSquad(Int32)`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnDiyItemCardClick(String, Int32)`

- `Void _OnChessCharItemCardClick(String, Int32)`

- `Void _OnChessCharItemCardClickInCharList(String, Int32, Act1VAutoChessChessShopViewModel)`

- `Void _OnChessCharItemCardClickInCharDetailList(String, Int32, Act1VAutoChessChessShopViewModel)`

- `Void _OnChessCharItemCancelClick(String)`

- `Void _OnChessCharItemCancelSuc(Act1VAutoChessRemoveChessPoolCharResponse)`

- `Void _OnChessTrapItemCardClick(String)`

- `Void _OnMenuLevelItemClick(ValueBundle)`

- `Void _OnFocusFinishedForDiyCharCardTutorial()`

- `Void _OnConfirmQuickSkillAndModuleClick()`

- `Void _OnConfirmMultiCharSkillAndModuleSuc(Act1VAutoChessSetChessPoolDeployResponse)`

- `Void _OnConfirmMultiCharSkillAndModule()`

- `Void _OnMultiQuickEditCharSkillItemClick(ValueBundle)`

- `Void _OnMultiQuickEditCharModuleItemClick(ValueBundle)`

- `Void _OnConfirmCharDetailClick()`

- `Void _OnConfirmSingleCharSkillAndModuleSuc(Act1VAutoChessSetChessPoolDeployResponse)`

- `Void _OnMenuShopTypeSwitchClick(Act1VAutoChessShopStatus)`

- `Void _SwitchToCharList()`

- `Void _SwitchToTrapList()`

- `Void _OnTopAssistBtnClick()`

- `Void _OnTopQuickSetBtnClick()`

- `Void _OnTopSwitchEditToggleClick(Act1VAutoChessShopQuickEditType)`

- `Void _OnDetailAssist()`

- `Void _OnDetailBack()`

- `Void _OnSelectEquip(String)`

- `Void _OnSelectSkill(String)`

- `Void _OnSwichGold(Boolean)`

- `Act1VAutoChessChessShopViewModel _EnsureDetail()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessChessShopState : PopupFadeState, IValueMsgReceiver
{
	private Act1VAutoChessChessShopMainView _mainView; // 0x70
	private Boolean m_inited; // 0x78
	private Act1VAutoChessChessShopStateBean m_stateBean; // 0x80
	private UICompDialogMgr m_dialogMgr; // 0x88
	private InputParam m_inputParamsToCharSelectState; // 0x90
	private Act1VAutoChessCharShopChessData m_diyCharShopChessDataToCharSelectState; // 0x98
	private String m_needVoiceChar; // 0xa0
	private Act1VAutoChessFriendAssistPlugin m_friendAssistPlugin; // 0xa8
	private FocusInput m_detailCharListFocusInput; // 0xb0
	public const Int32 MSG_DIY_ITEM_CARD_CLICK; // 0x0
	public const Int32 MSG_CHAR_CHESS_ITEM_CARD_CLICK; // 0x0
	public const Int32 MSG_CHAR_CHESS_ITEM_CANCEL_CLICK; // 0x0
	public const Int32 MSG_TRAP_CHESS_ITEM_CARD_CLICK; // 0x0
	public const Int32 MSG_MENU_LEVEL_ITEM_CLICK; // 0x0
	public const Int32 MSG_MENU_CONFIRM_QUICK_SKILL_AND_MODULE_CLICK; // 0x0
	public const Int32 MSG_MENU_CONFIRM_CHAR_DETAIL_CLICK; // 0x0
	public const Int32 MSG_MENU_SHOP_TYPE_SWITCH_CLICK; // 0x0
	public const Int32 MSG_TOP_ASSIST_BTN_CLICK; // 0x0
	public const Int32 MSG_TOP_QUICK_SET_CLICK; // 0x0
	public const Int32 MSG_TOP_SWITCH_EDIT_TYPE_TOGGLE_CLICK; // 0x0
	public const Int32 MSG_DETAIL_SET_GOLD; // 0x0
	public const Int32 MSG_DETAIL_SET_SKILL; // 0x0
	public const Int32 MSG_DETAIL_SET_BRANCH; // 0x0
	public const Int32 MSG_DETAIL_BACK; // 0x0
	public const Int32 MSG_DETAIL_ASSIST; // 0x0
	public const Int32 MSG_MULTI_QUICK_EDIT_CHAR_SKILL_ITEM_CLICK; // 0x0
	public const Int32 MSG_MULTI_QUICK_EDIT_CHAR_MODULE_ITEM_CLICK; // 0x0
	public const Int32 MSG_TOP_MENU_RETURN_CLICK; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x10
	private static DelegateBridge __Hotfix0_RegisterFromDataListener; // 0x18
	private static DelegateBridge __Hotfix0__RegisterFromCommonFriendAssistState; // 0x20
	private static DelegateBridge __Hotfix0__RegisterToCommonFriendAssistState; // 0x28
	private static DelegateBridge __Hotfix0__RegisterToCharSelectState; // 0x30
	private static DelegateBridge __Hotfix0__RegisterFromCharSelectState; // 0x38
	private static DelegateBridge __Hotfix0__RegisterFromQuickAssistState; // 0x40
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x48
	private static DelegateBridge __Hotfix0__OnReturnClick; // 0x50
	private static DelegateBridge __Hotfix0__GetFriendAssistPlugin; // 0x58
	private static DelegateBridge __Hotfix0__SendSetChessPoolDiyCharsRequest; // 0x60
	private static DelegateBridge __Hotfix0__TryGetDiyCharDeployInfo; // 0x68
	private static DelegateBridge __Hotfix0__OnSetChessPoolDiyCharsSuc; // 0x70
	private static DelegateBridge __Hotfix0__PlayCharVoice; // 0x78
	private static DelegateBridge __Hotfix0__CheckVoiceChar; // 0x80
	private static DelegateBridge __Hotfix0__AlreadyInSquad; // 0x88
	private static DelegateBridge __Hotfix0_OnMessage; // 0x90
	private static DelegateBridge __Hotfix0__OnDiyItemCardClick; // 0x98
	private static DelegateBridge __Hotfix0__OnChessCharItemCardClick; // 0xa0
	private static DelegateBridge __Hotfix0__OnChessCharItemCardClickInCharList; // 0xa8
	private static DelegateBridge __Hotfix0__OnChessCharItemCardClickInCharDetailList; // 0xb0
	private static DelegateBridge __Hotfix0__OnChessCharItemCancelClick; // 0xb8
	private static DelegateBridge __Hotfix0__OnChessCharItemCancelSuc; // 0xc0
	private static DelegateBridge __Hotfix0__OnChessTrapItemCardClick; // 0xc8
	private static DelegateBridge __Hotfix0__OnMenuLevelItemClick; // 0xd0
	private static DelegateBridge __Hotfix0__OnFocusFinishedForDiyCharCardTutorial; // 0xd8
	private static DelegateBridge __Hotfix0__OnConfirmQuickSkillAndModuleClick; // 0xe0
	private static DelegateBridge __Hotfix0__OnConfirmMultiCharSkillAndModuleSuc; // 0xe8
	private static DelegateBridge __Hotfix0__OnConfirmMultiCharSkillAndModule; // 0xf0
	private static DelegateBridge __Hotfix0__OnMultiQuickEditCharSkillItemClick; // 0xf8
	private static DelegateBridge __Hotfix0__OnMultiQuickEditCharModuleItemClick; // 0x100
	private static DelegateBridge __Hotfix0__OnConfirmCharDetailClick; // 0x108
	private static DelegateBridge __Hotfix0__OnConfirmSingleCharSkillAndModuleSuc; // 0x110
	private static DelegateBridge __Hotfix0__OnMenuShopTypeSwitchClick; // 0x118
	private static DelegateBridge __Hotfix0__SwitchToCharList; // 0x120
	private static DelegateBridge __Hotfix0__SwitchToTrapList; // 0x128
	private static DelegateBridge __Hotfix0__OnTopAssistBtnClick; // 0x130
	private static DelegateBridge __Hotfix0__OnTopQuickSetBtnClick; // 0x138
	private static DelegateBridge __Hotfix0__OnTopSwitchEditToggleClick; // 0x140
	private static DelegateBridge __Hotfix0__OnDetailAssist; // 0x148
	private static DelegateBridge __Hotfix0__OnDetailBack; // 0x150
	private static DelegateBridge __Hotfix0__OnSelectEquip; // 0x158
	private static DelegateBridge __Hotfix0__OnSelectSkill; // 0x160
	private static DelegateBridge __Hotfix0__OnSwichGold; // 0x168
	private static DelegateBridge __Hotfix0__EnsureDetail; // 0x170
	private static DelegateBridge _c__Hotfix0_ctor; // 0x178


	// RVA: 0x330d300 VA: 0x7595925300
	public override IStateBean GetCacheBean() { }
	// RVA: 0x330d368 VA: 0x7595925368
	protected override Void OnEnter() { }
	// RVA: 0x330d774 VA: 0x7595925774
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x330d968 VA: 0x7595925968
	public override Dictionary`2 RegisterFromDataListener() { }
	// RVA: 0x330dbcc VA: 0x7595925bcc
	private Void _RegisterFromCommonFriendAssistState(IStateBean stateBean) { }
	// RVA: 0x330dd44 VA: 0x7595925d44
	private Void _RegisterToCommonFriendAssistState(IStateBean stateBean) { }
	// RVA: 0x330de24 VA: 0x7595925e24
	private Void _RegisterToCharSelectState(IStateBean stateBean) { }
	// RVA: 0x330df28 VA: 0x7595925f28
	private Void _RegisterFromCharSelectState(IStateBean stateBean) { }
	// RVA: 0x330e5d0 VA: 0x75959265d0
	private Void _RegisterFromQuickAssistState(IStateBean stateBean) { }
	// RVA: 0x330d518 VA: 0x7595925518
	private Void _InitIfNot() { }
	// RVA: 0x330e9b4 VA: 0x75959269b4
	private Void _OnReturnClick() { }
	// RVA: 0x330ebec VA: 0x7595926bec
	private Act1VAutoChessFriendAssistPlugin _GetFriendAssistPlugin() { }
	// RVA: 0x330e0cc VA: 0x75959260cc
	private Void _SendSetChessPoolDiyCharsRequest(List`1 selectList, Int32 chessLv) { }
	// RVA: 0x330ecfc VA: 0x7595926cfc
	private Dictionary`2 _TryGetDiyCharDeployInfo(List`1 selectList, Int32 chessLv) { }
	// RVA: 0x330f3a0 VA: 0x75959273a0
	private Void _OnSetChessPoolDiyCharsSuc(Act1VAutoChessSetChessPoolDiyCharResponse resp) { }
	// RVA: 0x330f4cc VA: 0x75959274cc
	private Void _PlayCharVoice(Act1VAutoChessChessShopViewModel viewModel) { }
	// RVA: 0x330e340 VA: 0x7595926340
	private Void _CheckVoiceChar(TemplateCharSelectMainViewModel selectMainViewModel) { }
	// RVA: 0x330f5fc VA: 0x75959275fc
	private Boolean _AlreadyInSquad(Int32 instId) { }
	// RVA: 0x330f708 VA: 0x7595927708
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x330f9ac VA: 0x75959279ac
	private Void _OnDiyItemCardClick(String chessId, Int32 chessLv) { }
	// RVA: 0x330fd00 VA: 0x7595927d00
	private Void _OnChessCharItemCardClick(String chessId, Int32 chessLv) { }
	// RVA: 0x3311a64 VA: 0x7595929a64
	private Void _OnChessCharItemCardClickInCharList(String chessId, Int32 chessLv, Act1VAutoChessChessShopViewModel viewModel) { }
	// RVA: 0x3311be4 VA: 0x7595929be4
	private Void _OnChessCharItemCardClickInCharDetailList(String chessId, Int32 chessLv, Act1VAutoChessChessShopViewModel viewModel) { }
	// RVA: 0x330fe40 VA: 0x7595927e40
	private Void _OnChessCharItemCancelClick(String chessId) { }
	// RVA: 0x3311d64 VA: 0x7595929d64
	private Void _OnChessCharItemCancelSuc(Act1VAutoChessRemoveChessPoolCharResponse response) { }
	// RVA: 0x3310120 VA: 0x7595928120
	private Void _OnChessTrapItemCardClick(String chessId) { }
	// RVA: 0x33102e8 VA: 0x75959282e8
	private Void _OnMenuLevelItemClick(ValueBundle msg) { }
	// RVA: 0x3311e84 VA: 0x7595929e84
	private Void _OnFocusFinishedForDiyCharCardTutorial() { }
	// RVA: 0x3310568 VA: 0x7595928568
	private Void _OnConfirmQuickSkillAndModuleClick() { }
	// RVA: 0x33120f0 VA: 0x759592a0f0
	private Void _OnConfirmMultiCharSkillAndModuleSuc(Act1VAutoChessSetChessPoolDeployResponse response) { }
	// RVA: 0x3311fc4 VA: 0x7595929fc4
	private Void _OnConfirmMultiCharSkillAndModule() { }
	// RVA: 0x33116ac VA: 0x75959296ac
	private Void _OnMultiQuickEditCharSkillItemClick(ValueBundle msg) { }
	// RVA: 0x3311888 VA: 0x7595929888
	private Void _OnMultiQuickEditCharModuleItemClick(ValueBundle msg) { }
	// RVA: 0x33107fc VA: 0x75959287fc
	private Void _OnConfirmCharDetailClick() { }
	// RVA: 0x331216c VA: 0x759592a16c
	private Void _OnConfirmSingleCharSkillAndModuleSuc(Act1VAutoChessSetChessPoolDeployResponse response) { }
	// RVA: 0x3310a64 VA: 0x7595928a64
	private Void _OnMenuShopTypeSwitchClick(Act1VAutoChessShopStatus toShopStatus) { }
	// RVA: 0x33122a8 VA: 0x759592a2a8
	private Void _SwitchToCharList() { }
	// RVA: 0x33123c4 VA: 0x759592a3c4
	private Void _SwitchToTrapList() { }
	// RVA: 0x3310b14 VA: 0x7595928b14
	private Void _OnTopAssistBtnClick() { }
	// RVA: 0x3310d04 VA: 0x7595928d04
	private Void _OnTopQuickSetBtnClick() { }
	// RVA: 0x3310e98 VA: 0x7595928e98
	private Void _OnTopSwitchEditToggleClick(Act1VAutoChessShopQuickEditType quickEditType) { }
	// RVA: 0x3311458 VA: 0x7595929458
	private Void _OnDetailAssist() { }
	// RVA: 0x3311344 VA: 0x7595929344
	private Void _OnDetailBack() { }
	// RVA: 0x33111fc VA: 0x75959291fc
	private Void _OnSelectEquip(String equipId) { }
	// RVA: 0x33110b4 VA: 0x75959290b4
	private Void _OnSelectSkill(String skillId) { }
	// RVA: 0x3310fd8 VA: 0x7595928fd8
	private Void _OnSwichGold(Boolean isGold) { }
	// RVA: 0x3312598 VA: 0x759592a598
	private Act1VAutoChessChessShopViewModel _EnsureDetail() { }
	// RVA: 0x3312640 VA: 0x759592a640
	public Void .ctor() { }
	// RVA: 0x3312728 VA: 0x759592a728
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x3312730 VA: 0x759592a730
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x3312738 VA: 0x759592a738
	private Dictionary`2 <>xLuaBaseProxy_RegisterFromDataListener() { }
}
```