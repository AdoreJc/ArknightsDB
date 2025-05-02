# CommonSquadHomeState

**Namespace:** `Torappu.UI`


## Fields

- `TopMenuDynamicPrefabInstHolder _topMenuHolder`

- `CommonSquadGroupController _squadGroupController`

- `SquadAssistCardView _assistCard`

- `TemplateCharSelectCardView _charCardPrefab`

- `Boolean m_isInited`

- `CommonSquadStateBean m_stateBean`

- `InputParam m_paramToSelectState`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `Void _InitIfNot()`

- `Void _OnInitTopMenu(GameObject)`

- `Void _OnTopMenuRoutedToOtherPage(UIRouteTarget, Object, Action`2)`

- `Void _PassDataToFriendAssist(IStateBean)`

- `Void _OnAssistSelectFinished(IStateBean)`

- `Void _GoToFriendAssist()`

- `Void _ClearFiendAssist()`

- `Void _DoStartBattle()`

- `Void _InvokedStartBattle()`

- `Void _OnStartBattleSuccess()`

- `Void _SaveCacheStageConfig()`

- `Param _CreateParamToStartBattle()`

- `Boolean _CheckIfStartBattleValid()`

- `Void _PassDataToCharSelect(IStateBean)`

- `Void _OnCharSelectFinished(IStateBean)`

- `CommonCharSelectCustomization _GenCharSelectCustomization()`

- `TemplateCharSelectCardViewModel _CreateCharSelectCardViewModel(Int32, TemplateCharSelectCharInputData, PlayerCharacter)`

- `Void _TryRefreshSquadsBackFromCharSelect_Common(CommonCharSelectStateBean)`

- `Void _ApplySquadFromCharSelectSingleMode(TemplateCharSelectCardViewModel, Int32, SquadViewModel)`

- `Void _ApplySquadFromCharSelectMultiMode(List`1, SquadViewModel)`

- `SquadItemStruct _FindInstInSquad(Int32, IList`1)`

- `Int32 _FindInstIndexInSquad(Int32, IList`1)`

- `Int32 _FindFirstEmptyMemberIndexInSquad(IList`1)`

- `Void _SaveSquadFormationIfNeeded(Action)`

- `Void _GoToCharSelect(SelectSquadParam)`

- `InputParam _ParseTemplateCharSelectInputParam(SelectSquadParam)`

- `Int32 _TryFetchCharSelectFocusInstId(SelectSquadParam)`

- `CommonSquadSquadCharSelectCharInputData _GenCharSelectInputData(CharacterCardViewModel)`

- `Void <_OnInitTopMenu>b__21_0()`

- `Void <_OnInitTopMenu>b__21_1()`

- `Void <_CheckIfStartBattleValid>b__33_0()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class CommonSquadHomeState : State, IValueMsgReceiver
{
	private TopMenuDynamicPrefabInstHolder _topMenuHolder; // 0x50
	private CommonSquadGroupController _squadGroupController; // 0x58
	private SquadAssistCardView _assistCard; // 0x60
	private TemplateCharSelectCardView _charCardPrefab; // 0x68
	private Boolean m_isInited; // 0x70
	private CommonSquadStateBean m_stateBean; // 0x78
	private InputParam m_paramToSelectState; // 0x80
	public const Int32 MSG_CHAR_SINGLE_FORMATION_CLICK; // 0x0
	public const Int32 MSG_CHAR_MULTI_FORMATION_CLICK; // 0x0
	public const Int32 MSG_ASSIST_BTN_CLICK; // 0x0
	public const Int32 MSG_ASSIST_CLEAR_CLICK; // 0x0
	public const Int32 MSG_START_BTN_CLICK; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x18
	private static DelegateBridge __Hotfix0_RegisterFromDataListener; // 0x20
	private static DelegateBridge __Hotfix0_OnMessage; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0__OnInitTopMenu; // 0x38
	private static DelegateBridge __Hotfix0__OnTopMenuRoutedToOtherPage; // 0x40
	private static DelegateBridge __Hotfix0__PassDataToFriendAssist; // 0x48
	private static DelegateBridge __Hotfix0__OnAssistSelectFinished; // 0x50
	private static DelegateBridge __Hotfix0__GoToFriendAssist; // 0x58
	private static DelegateBridge __Hotfix0__ClearFiendAssist; // 0x60
	private static DelegateBridge __Hotfix0__GenLockedStyle4CharRuneInvalid; // 0x68
	private static DelegateBridge __Hotfix0__DoStartBattle; // 0x70
	private static DelegateBridge __Hotfix0__InvokedStartBattle; // 0x78
	private static DelegateBridge __Hotfix0__OnStartBattleSuccess; // 0x80
	private static DelegateBridge __Hotfix0__SaveCacheStageConfig; // 0x88
	private static DelegateBridge __Hotfix0__CreateParamToStartBattle; // 0x90
	private static DelegateBridge __Hotfix0__CheckIfStartBattleValid; // 0x98
	private static DelegateBridge __Hotfix0__PassDataToCharSelect; // 0xa0
	private static DelegateBridge __Hotfix0__OnCharSelectFinished; // 0xa8
	private static DelegateBridge __Hotfix0__GenCharSelectCustomization; // 0xb0
	private static DelegateBridge __Hotfix0__CreateCharSelectCardViewModel; // 0xb8
	private static DelegateBridge __Hotfix0__TryRefreshSquadsBackFromCharSelect_Common; // 0xc0
	private static DelegateBridge __Hotfix0__ApplySquadFromCharSelectSingleMode; // 0xc8
	private static DelegateBridge __Hotfix0__ApplySquadFromCharSelectMultiMode; // 0xd0
	private static DelegateBridge __Hotfix0__FindInstInSquad; // 0xd8
	private static DelegateBridge __Hotfix0__FindInstIndexInSquad; // 0xe0
	private static DelegateBridge __Hotfix0__FindFirstEmptyMemberIndexInSquad; // 0xe8
	private static DelegateBridge __Hotfix0__SaveSquadFormationIfNeeded; // 0xf0
	private static DelegateBridge __Hotfix0__GoToCharSelect; // 0xf8
	private static DelegateBridge __Hotfix0__ParseTemplateCharSelectInputParam; // 0x100
	private static DelegateBridge __Hotfix0__TryFetchCharSelectFocusInstId; // 0x108
	private static DelegateBridge __Hotfix0__GenCharSelectInputDataList; // 0x110
	private static DelegateBridge __Hotfix0__GenCharSelectInputData; // 0x118
	private static DelegateBridge _c__Hotfix0_ctor; // 0x120


	// RVA: 0x213b28c VA: 0x759475328c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x213b2f4 VA: 0x75947532f4
	protected override Void OnEnter() { }
	// RVA: 0x213b580 VA: 0x7594753580
	protected override Void OnResume() { }
	// RVA: 0x213b61c VA: 0x759475361c
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x213b810 VA: 0x7594753810
	public override Dictionary`2 RegisterFromDataListener() { }
	// RVA: 0x213ba04 VA: 0x7594753a04
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x213b4a0 VA: 0x75947534a0
	private Void _InitIfNot() { }
	// RVA: 0x213c188 VA: 0x7594754188
	private Void _OnInitTopMenu(GameObject topMenuObj) { }
	// RVA: 0x213c34c VA: 0x759475434c
	private Void _OnTopMenuRoutedToOtherPage(UIRouteTarget routeTarget, Object param, Action`2 baseHandler) { }
	// RVA: 0x213c530 VA: 0x7594754530
	private Void _PassDataToFriendAssist(IStateBean stateBean) { }
	// RVA: 0x213c648 VA: 0x7594754648
	private Void _OnAssistSelectFinished(IStateBean stateBean) { }
	// RVA: 0x213bd00 VA: 0x7594753d00
	private Void _GoToFriendAssist() { }
	// RVA: 0x213bfe4 VA: 0x7594753fe4
	private Void _ClearFiendAssist() { }
	// RVA: 0x213c71c VA: 0x759475471c
	private static LockedStyle _GenLockedStyle4CharRuneInvalid() { }
	// RVA: 0x213c0b8 VA: 0x75947540b8
	private Void _DoStartBattle() { }
	// RVA: 0x213ca38 VA: 0x7594754a38
	private Void _InvokedStartBattle() { }
	// RVA: 0x213d234 VA: 0x7594755234
	private Void _OnStartBattleSuccess() { }
	// RVA: 0x213d29c VA: 0x759475529c
	private Void _SaveCacheStageConfig() { }
	// RVA: 0x213cb9c VA: 0x7594754b9c
	private Param _CreateParamToStartBattle() { }
	// RVA: 0x213c864 VA: 0x7594754864
	private Boolean _CheckIfStartBattleValid() { }
	// RVA: 0x213d36c VA: 0x759475536c
	private Void _PassDataToCharSelect(IStateBean stateBean) { }
	// RVA: 0x213d5c0 VA: 0x75947555c0
	private Void _OnCharSelectFinished(IStateBean stateBean) { }
	// RVA: 0x213d46c VA: 0x759475546c
	private CommonCharSelectCustomization _GenCharSelectCustomization() { }
	// RVA: 0x213d9b4 VA: 0x75947559b4
	private TemplateCharSelectCardViewModel _CreateCharSelectCardViewModel(Int32 instId, TemplateCharSelectCharInputData inputNullable, PlayerCharacter playerData) { }
	// RVA: 0x213d694 VA: 0x7594755694
	private Void _TryRefreshSquadsBackFromCharSelect_Common(CommonCharSelectStateBean selectStateBean) { }
	// RVA: 0x213de08 VA: 0x7594755e08
	private Void _ApplySquadFromCharSelectSingleMode(TemplateCharSelectCardViewModel target, Int32 singleTargetInstId, SquadViewModel squad) { }
	// RVA: 0x213db94 VA: 0x7594755b94
	private Void _ApplySquadFromCharSelectMultiMode(List`1 selectCardViewModels, SquadViewModel squad) { }
	// RVA: 0x213e3ec VA: 0x75947563ec
	private SquadItemStruct _FindInstInSquad(Int32 instId, IList`1 squad) { }
	// RVA: 0x213e0bc VA: 0x75947560bc
	private Int32 _FindInstIndexInSquad(Int32 instId, IList`1 squad) { }
	// RVA: 0x213e274 VA: 0x7594756274
	private Int32 _FindFirstEmptyMemberIndexInSquad(IList`1 squad) { }
	// RVA: 0x213c484 VA: 0x7594754484
	private Void _SaveSquadFormationIfNeeded(Action nextStep) { }
	// RVA: 0x213bb60 VA: 0x7594753b60
	private Void _GoToCharSelect(SelectSquadParam selectSquadParam) { }
	// RVA: 0x213e5bc VA: 0x75947565bc
	private InputParam _ParseTemplateCharSelectInputParam(SelectSquadParam selectSquadParam) { }
	// RVA: 0x213e720 VA: 0x7594756720
	private Int32 _TryFetchCharSelectFocusInstId(SelectSquadParam selectSquadParam) { }
	// RVA: 0x213e840 VA: 0x7594756840
	private List`1 _GenCharSelectInputDataList() { }
	// RVA: 0x213ea58 VA: 0x7594756a58
	private CommonSquadSquadCharSelectCharInputData _GenCharSelectInputData(CharacterCardViewModel cardViewModel) { }
	// RVA: 0x213eb58 VA: 0x7594756b58
	public Void .ctor() { }
	// RVA: 0x213ec08 VA: 0x7594756c08
	private Void <_OnInitTopMenu>b__21_0() { }
	// RVA: 0x213ec88 VA: 0x7594756c88
	private Void <_OnInitTopMenu>b__21_1() { }
	// RVA: 0x213eca8 VA: 0x7594756ca8
	private Void <_CheckIfStartBattleValid>b__33_0() { }
	// RVA: 0x213ecc8 VA: 0x7594756cc8
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x213ecd0 VA: 0x7594756cd0
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x213ecd8 VA: 0x7594756cd8
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x213ece0 VA: 0x7594756ce0
	private Dictionary`2 <>xLuaBaseProxy_RegisterFromDataListener() { }
}
```