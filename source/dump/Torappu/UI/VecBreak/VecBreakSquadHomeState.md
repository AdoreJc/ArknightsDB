# VecBreakSquadHomeState

**Namespace:** `Torappu.UI.VecBreak`


## Fields

- `TopMenuDynamicPrefabInstHolder _topMenuHolder`

- `VecBreakSquadGroupController _squadGroupController`

- `SquadAssistCardView _assistCard`

- `TemplateCharSelectCardView _charCardPrefab`

- `Boolean m_isInited`

- `VecBreakSquadStateBean m_stateBean`

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

- `Void _PlaySquadVoiceFromSelectCardList(List`1)`

- `Void _SaveSquadFormationIfNeeded(Action)`

- `Void _GoToCharSelect(SelectSquadParam)`

- `InputParam _ParseTemplateCharSelectInputParam(SelectSquadParam)`

- `Int32 _TryFetchCharSelectFocusInstId(SelectSquadParam)`

- `CommonSquadSquadCharSelectCharInputData _GenCharSelectInputData(CharacterCardViewModel)`

- `Void <_OnInitTopMenu>b__22_0()`

- `Void <_OnInitTopMenu>b__22_1()`

- `Void <_CheckIfStartBattleValid>b__35_0()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VecBreak
public class VecBreakSquadHomeState : State, IValueMsgReceiver
{
	private TopMenuDynamicPrefabInstHolder _topMenuHolder; // 0x50
	private VecBreakSquadGroupController _squadGroupController; // 0x58
	private SquadAssistCardView _assistCard; // 0x60
	private TemplateCharSelectCardView _charCardPrefab; // 0x68
	private Boolean m_isInited; // 0x70
	private VecBreakSquadStateBean m_stateBean; // 0x78
	private InputParam m_paramToSelectState; // 0x80
	private const String SQUAD_ASSIST_CHAR_IN_DEFENSE_INVALID_COLOR; // 0x0
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
	private static DelegateBridge __Hotfix0__GenLockedStyle4CharInDefense; // 0x70
	private static DelegateBridge __Hotfix0__DoStartBattle; // 0x78
	private static DelegateBridge __Hotfix0__InvokedStartBattle; // 0x80
	private static DelegateBridge __Hotfix0__OnStartBattleSuccess; // 0x88
	private static DelegateBridge __Hotfix0__SaveCacheStageConfig; // 0x90
	private static DelegateBridge __Hotfix0__CreateParamToStartBattle; // 0x98
	private static DelegateBridge __Hotfix0__CheckIfStartBattleValid; // 0xa0
	private static DelegateBridge __Hotfix0__PassDataToCharSelect; // 0xa8
	private static DelegateBridge __Hotfix0__OnCharSelectFinished; // 0xb0
	private static DelegateBridge __Hotfix0__GenCharSelectCustomization; // 0xb8
	private static DelegateBridge __Hotfix0__CreateCharSelectCardViewModel; // 0xc0
	private static DelegateBridge __Hotfix0__TryRefreshSquadsBackFromCharSelect_Common; // 0xc8
	private static DelegateBridge __Hotfix0__ApplySquadFromCharSelectSingleMode; // 0xd0
	private static DelegateBridge __Hotfix0__ApplySquadFromCharSelectMultiMode; // 0xd8
	private static DelegateBridge __Hotfix0__FindInstInSquad; // 0xe0
	private static DelegateBridge __Hotfix0__FindInstIndexInSquad; // 0xe8
	private static DelegateBridge __Hotfix0__FindFirstEmptyMemberIndexInSquad; // 0xf0
	private static DelegateBridge __Hotfix0__PlaySquadVoiceFromSelectCardList; // 0xf8
	private static DelegateBridge __Hotfix0__SaveSquadFormationIfNeeded; // 0x100
	private static DelegateBridge __Hotfix0__GoToCharSelect; // 0x108
	private static DelegateBridge __Hotfix0__ParseTemplateCharSelectInputParam; // 0x110
	private static DelegateBridge __Hotfix0__TryFetchCharSelectFocusInstId; // 0x118
	private static DelegateBridge __Hotfix0__GenCharSelectInputDataList; // 0x120
	private static DelegateBridge __Hotfix0__GenCharSelectInputData; // 0x128
	private static DelegateBridge _c__Hotfix0_ctor; // 0x130


	// RVA: 0x22da0a4 VA: 0x75948f20a4
	public override IStateBean GetCacheBean() { }
	// RVA: 0x22da10c VA: 0x75948f210c
	protected override Void OnEnter() { }
	// RVA: 0x22da494 VA: 0x75948f2494
	protected override Void OnResume() { }
	// RVA: 0x22da594 VA: 0x75948f2594
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x22da788 VA: 0x75948f2788
	public override Dictionary`2 RegisterFromDataListener() { }
	// RVA: 0x22da97c VA: 0x75948f297c
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x22da2a4 VA: 0x75948f22a4
	private Void _InitIfNot() { }
	// RVA: 0x22db0e8 VA: 0x75948f30e8
	private Void _OnInitTopMenu(GameObject topMenuObj) { }
	// RVA: 0x22db2ac VA: 0x75948f32ac
	private Void _OnTopMenuRoutedToOtherPage(UIRouteTarget routeTarget, Object param, Action`2 baseHandler) { }
	// RVA: 0x22db494 VA: 0x75948f3494
	private Void _PassDataToFriendAssist(IStateBean stateBean) { }
	// RVA: 0x22db6b0 VA: 0x75948f36b0
	private Void _OnAssistSelectFinished(IStateBean stateBean) { }
	// RVA: 0x22dac78 VA: 0x75948f2c78
	private Void _GoToFriendAssist() { }
	// RVA: 0x22daf4c VA: 0x75948f2f4c
	private Void _ClearFiendAssist() { }
	// RVA: 0x22dba94 VA: 0x75948f3a94
	private static LockedStyle _GenLockedStyle4CharRuneInvalid() { }
	// RVA: 0x22dbbdc VA: 0x75948f3bdc
	private static LockedStyle _GenLockedStyle4CharInDefense() { }
	// RVA: 0x22db018 VA: 0x75948f3018
	private Void _DoStartBattle() { }
	// RVA: 0x22dbee8 VA: 0x75948f3ee8
	private Void _InvokedStartBattle() { }
	// RVA: 0x22dc5fc VA: 0x75948f45fc
	private Void _OnStartBattleSuccess() { }
	// RVA: 0x22dc664 VA: 0x75948f4664
	private Void _SaveCacheStageConfig() { }
	// RVA: 0x22dc054 VA: 0x75948f4054
	private Param _CreateParamToStartBattle() { }
	// RVA: 0x22dbd24 VA: 0x75948f3d24
	private Boolean _CheckIfStartBattleValid() { }
	// RVA: 0x22dd024 VA: 0x75948f5024
	private Void _PassDataToCharSelect(IStateBean stateBean) { }
	// RVA: 0x22dd278 VA: 0x75948f5278
	private Void _OnCharSelectFinished(IStateBean stateBean) { }
	// RVA: 0x22dd124 VA: 0x75948f5124
	private CommonCharSelectCustomization _GenCharSelectCustomization() { }
	// RVA: 0x22dd660 VA: 0x75948f5660
	private TemplateCharSelectCardViewModel _CreateCharSelectCardViewModel(Int32 instId, TemplateCharSelectCharInputData inputNullable, PlayerCharacter playerData) { }
	// RVA: 0x22dd34c VA: 0x75948f534c
	private Void _TryRefreshSquadsBackFromCharSelect_Common(CommonCharSelectStateBean selectStateBean) { }
	// RVA: 0x22ddbf4 VA: 0x75948f5bf4
	private Void _ApplySquadFromCharSelectSingleMode(TemplateCharSelectCardViewModel target, Int32 singleTargetInstId, SquadViewModel squad) { }
	// RVA: 0x22dd974 VA: 0x75948f5974
	private Void _ApplySquadFromCharSelectMultiMode(List`1 selectCardViewModels, SquadViewModel squad) { }
	// RVA: 0x22de608 VA: 0x75948f6608
	private SquadItemStruct _FindInstInSquad(Int32 instId, IList`1 squad) { }
	// RVA: 0x22de2d8 VA: 0x75948f62d8
	private Int32 _FindInstIndexInSquad(Int32 instId, IList`1 squad) { }
	// RVA: 0x22de490 VA: 0x75948f6490
	private Int32 _FindFirstEmptyMemberIndexInSquad(IList`1 squad) { }
	// RVA: 0x22de7d8 VA: 0x75948f67d8
	private Void _PlaySquadVoiceFromSelectCardList(List`1 selectCardViewModels) { }
	// RVA: 0x22db3ec VA: 0x75948f33ec
	private Void _SaveSquadFormationIfNeeded(Action nextStep) { }
	// RVA: 0x22daad8 VA: 0x75948f2ad8
	private Void _GoToCharSelect(SelectSquadParam selectSquadParam) { }
	// RVA: 0x22dea94 VA: 0x75948f6a94
	private InputParam _ParseTemplateCharSelectInputParam(SelectSquadParam selectSquadParam) { }
	// RVA: 0x22decdc VA: 0x75948f6cdc
	private Int32 _TryFetchCharSelectFocusInstId(SelectSquadParam selectSquadParam) { }
	// RVA: 0x22dedf8 VA: 0x75948f6df8
	private List`1 _GenCharSelectInputDataList() { }
	// RVA: 0x22df00c VA: 0x75948f700c
	private CommonSquadSquadCharSelectCharInputData _GenCharSelectInputData(CharacterCardViewModel cardViewModel) { }
	// RVA: 0x22df10c VA: 0x75948f710c
	public Void .ctor() { }
	// RVA: 0x22df268 VA: 0x75948f7268
	private Void <_OnInitTopMenu>b__22_0() { }
	// RVA: 0x22df2e8 VA: 0x75948f72e8
	private Void <_OnInitTopMenu>b__22_1() { }
	// RVA: 0x22df308 VA: 0x75948f7308
	private Void <_CheckIfStartBattleValid>b__35_0() { }
	// RVA: 0x22df328 VA: 0x75948f7328
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x22df330 VA: 0x75948f7330
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x22df338 VA: 0x75948f7338
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x22df340 VA: 0x75948f7340
	private Dictionary`2 <>xLuaBaseProxy_RegisterFromDataListener() { }
}
```