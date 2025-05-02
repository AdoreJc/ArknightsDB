# SquadHomeState

**Namespace:** `Torappu.UI.Squad`


## Fields

- `SquadHomeStateBean _stateBean`

- `TopMenuDynamicPrefabInstHolder _topMenuHolder`

- `Animator _deleteState`

- `GameObject _panelNormalSquad`

- `GameObject _panelBattleSquad`

- `SquadGroupController _squadGroupController`

- `SquadHomePluginLoader _homePluginLoader`

- `Boolean m_deleteFlag`

- `Int32 m_editingSquadIndexCache`

- `SquadHomePlugin m_squadHomePlugin`

- `SquadCharSelectMaskPlugin m_charSelectMaskPluginPrefab`

- `DefaultCharSelectInput m_charSelectInputParam`


## Methods

- `Void OnEnable()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void GoToFriendAssistState()`

- `SquadGroupViewModel GetSquadGroupViewModel()`

- `Void EventOnSquadTabClick(Int32)`

- `Void EventOnSquadLeftClick(Int32)`

- `Void EventOnClearBtnClick()`

- `Void EventOnSingleFormatClick(Int32)`

- `Void EventOnRenameClick(Int32)`

- `Void EventOnMultiFormatClick()`

- `Void EventOnStartBattleClick()`

- `Void _OnInitTopMenu(GameObject)`

- `Void _OnTopMenuRoutedToOtherPage(UIRouteTarget, Object, Action`2)`

- `Void CleanAssist()`

- `Void _OnStartBattleSuccess()`

- `Void _DeleteCurrentSquad()`

- `Input _ParseSquadSelectParam(Boolean, Int32)`

- `Void _SaveSquadFormationIfNeeded(Action`1, Boolean)`

- `SquadFormationRequest _ParseSquadFormationRequest()`

- `Void GetSquadAssist()`

- `Param _CreateParamToStartBattle()`

- `String _GetRetroGroupIdForStartBattle(String)`

- `Void _InvokedStartBattle(Param)`

- `Void _OnResReadyToStartBattle(Param)`

- `Void _QuitSquad(SquadFormationResponse)`

- `Void _RaiseSavedSquadSignal()`

- `Void _AlertSquadInvalid()`

- `Void _SaveCacheStageConfig()`

- `Boolean _CheckIfStartBattleValid()`

- `Boolean _CheckIfStageCrossDays(Params)`

- `Void _ConfirmTipsAndDoStartBattle()`

- `Void _DoStartBattle()`

- `Void _TriggerSquadPluginResume()`

- `Void <RegisterToDataListener>b__28_0(IStateBean)`

- `Void <RegisterToDataListener>b__28_1(IStateBean)`

- `Void <RegisterToDataListener>b__28_2(IStateBean)`

- `Void <RegisterFromDataListener>b__30_0(IStateBean)`

- `Void <RegisterFromDataListener>b__30_1(IStateBean)`

- `Void <RegisterFromDataListener>b__30_2(IStateBean)`

- `Void <RegisterFromDataListener>b__30_3(IStateBean)`

- `Void <_OnInitTopMenu>b__48_0()`

- `Void <GetSquadAssist>b__58_0(GetFriendAssistCharListResponse)`

- `Void <_AlertSquadInvalid>b__65_0()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Squad
public class SquadHomeState : State, ISquadCharSelectContext, IValueMsgReceiver
{
	public const Int32 ON_MSG_REFRESH_DATA; // 0x0
	private SquadHomeStateBean _stateBean; // 0x50
	private TopMenuDynamicPrefabInstHolder _topMenuHolder; // 0x58
	private Animator _deleteState; // 0x60
	private GameObject _panelNormalSquad; // 0x68
	private GameObject _panelBattleSquad; // 0x70
	private SquadGroupController _squadGroupController; // 0x78
	private SquadHomePluginLoader _homePluginLoader; // 0x80
	private const String ANIMATORPARAM; // 0x0
	private Boolean m_deleteFlag; // 0x88
	private Int32 m_editingSquadIndexCache; // 0x8c
	private SquadHomePlugin m_squadHomePlugin; // 0x90
	private SquadCharSelectMaskPlugin m_charSelectMaskPluginPrefab; // 0x98
	private DefaultCharSelectInput m_charSelectInputParam; // 0xa0
	private List`1 m_tempListForExclusiveInstIds; // 0xe8
	private static DelegateBridge __Hotfix0_OnEnable; // 0x0
	private static DelegateBridge __Hotfix0_GenLockedStyle4CharAlreadyExist; // 0x8
	private static DelegateBridge __Hotfix0_GenLockedStyle4ExclusiveCharAlreadyExist; // 0x10
	private static DelegateBridge __Hotfix0_GenLockedStyle4CharRequired; // 0x18
	private static DelegateBridge __Hotfix0_OnMessage; // 0x20
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x28
	private static DelegateBridge __Hotfix0_OnEnter; // 0x30
	private static DelegateBridge __Hotfix0_OnResume; // 0x38
	private static DelegateBridge __Hotfix0_GoToFriendAssistState; // 0x40
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x48
	private static DelegateBridge __Hotfix0_UseEarlyFromDataListener; // 0x50
	private static DelegateBridge __Hotfix0_RegisterFromDataListener; // 0x58
	private static DelegateBridge __Hotfix0_GetTempListForExclusiveInstIds; // 0x60
	private static DelegateBridge __Hotfix0_GetSquadGroupViewModel; // 0x68
	private static DelegateBridge __Hotfix0_ApplySquadFromCharSelect; // 0x70
	private static DelegateBridge __Hotfix0__ApplySquadFromCharSelectSingleMode; // 0x78
	private static DelegateBridge __Hotfix0__ApplySquadFromCharSelectMultiMode; // 0x80
	private static DelegateBridge __Hotfix0_UpdateCharSelectedSkill; // 0x88
	private static DelegateBridge __Hotfix0_UpdateCharSelectedBranch; // 0x90
	private static DelegateBridge __Hotfix0_PlaySquadVoice; // 0x98
	private static DelegateBridge __Hotfix1_PlaySquadVoice; // 0xa0
	private static DelegateBridge __Hotfix2_PlaySquadVoice; // 0xa8
	private static DelegateBridge __Hotfix0_EventOnSquadTabClick; // 0xb0
	private static DelegateBridge __Hotfix0_EventOnSquadLeftClick; // 0xb8
	private static DelegateBridge __Hotfix0_EventOnClearBtnClick; // 0xc0
	private static DelegateBridge __Hotfix0_EventOnSingleFormatClick; // 0xc8
	private static DelegateBridge __Hotfix0_EventOnRenameClick; // 0xd0
	private static DelegateBridge __Hotfix0_EventOnMultiFormatClick; // 0xd8
	private static DelegateBridge __Hotfix0_EventOnStartBattleClick; // 0xe0
	private static DelegateBridge __Hotfix0__OnInitTopMenu; // 0xe8
	private static DelegateBridge __Hotfix0__OnTopMenuRoutedToOtherPage; // 0xf0
	private static DelegateBridge __Hotfix0_CleanAssist; // 0xf8
	private static DelegateBridge __Hotfix0__OnStartBattleSuccess; // 0x100
	private static DelegateBridge __Hotfix0_PickRandomCharacter; // 0x108
	private static DelegateBridge __Hotfix0__DeleteCurrentSquad; // 0x110
	private static DelegateBridge __Hotfix0__ParseSquadSelectParam; // 0x118
	private static DelegateBridge __Hotfix0__SaveSquadFormationIfNeeded; // 0x120
	private static DelegateBridge __Hotfix0__ParseSquadFormationRequest; // 0x128
	private static DelegateBridge __Hotfix0_SendAssistCharListRequest; // 0x130
	private static DelegateBridge __Hotfix0_GetSquadAssist; // 0x138
	private static DelegateBridge __Hotfix0__CreateParamToStartBattle; // 0x140
	private static DelegateBridge __Hotfix0__GetRetroGroupIdForStartBattle; // 0x148
	private static DelegateBridge __Hotfix0__InvokedStartBattle; // 0x150
	private static DelegateBridge __Hotfix0__OnResReadyToStartBattle; // 0x158
	private static DelegateBridge __Hotfix0__QuitSquad; // 0x160
	private static DelegateBridge __Hotfix0__RaiseSavedSquadSignal; // 0x168
	private static DelegateBridge __Hotfix0__AlertSquadInvalid; // 0x170
	private static DelegateBridge __Hotfix0__SaveCacheStageConfig; // 0x178
	private static DelegateBridge __Hotfix0__CheckIfStartBattleValid; // 0x180
	private static DelegateBridge __Hotfix0__CheckIfStageCrossDays; // 0x188
	private static DelegateBridge __Hotfix0__GetCurSquadMembers; // 0x190
	private static DelegateBridge __Hotfix0__ConfirmTipsAndDoStartBattle; // 0x198
	private static DelegateBridge __Hotfix0__DoStartBattle; // 0x1a0
	private static DelegateBridge __Hotfix0__TriggerSquadPluginResume; // 0x1a8
	private static DelegateBridge __Hotfix0__FindInstInSquad; // 0x1b0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x1b8


	// RVA: 0x237d4b8 VA: 0x75949954b8
	private Void OnEnable() { }
	// RVA: 0x237d548 VA: 0x7594995548
	public static LockedStyle GenLockedStyle4CharAlreadyExist() { }
	// RVA: 0x237d690 VA: 0x7594995690
	public static LockedStyle GenLockedStyle4ExclusiveCharAlreadyExist(String exclusiveInfo) { }
	// RVA: 0x237d7e8 VA: 0x75949957e8
	public static LockedStyle GenLockedStyle4CharRequired() { }
	// RVA: 0x237d930 VA: 0x7594995930
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x237da78 VA: 0x7594995a78
	public override IStateBean GetCacheBean() { }
	// RVA: 0x237dae0 VA: 0x7594995ae0
	protected override Void OnEnter() { }
	// RVA: 0x237e30c VA: 0x759499630c
	protected override Void OnResume() { }
	// RVA: 0x237e5a8 VA: 0x75949965a8
	public Void GoToFriendAssistState() { }
	// RVA: 0x237e6b4 VA: 0x75949966b4
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x237e918 VA: 0x7594996918
	public override Boolean UseEarlyFromDataListener(Type fromState) { }
	// RVA: 0x237e990 VA: 0x7594996990
	public override Dictionary`2 RegisterFromDataListener() { }
	// RVA: 0x237ec68 VA: 0x7594996c68
	public List`1 GetTempListForExclusiveInstIds() { }
	// RVA: 0x237ecd0 VA: 0x7594996cd0
	public SquadGroupViewModel GetSquadGroupViewModel() { }
	// RVA: 0x237ed58 VA: 0x7594996d58
	public static Void ApplySquadFromCharSelect(SquadGroupViewModel squadGroupModel, ICharSelectInput input, Output output) { }
	// RVA: 0x237f308 VA: 0x7594997308
	private static Void _ApplySquadFromCharSelectSingleMode(CharacterCardViewModel target, Int32 editIndex, SquadViewModel squad) { }
	// RVA: 0x237f680 VA: 0x7594997680
	private static Void _ApplySquadFromCharSelectMultiMode(IList`1 selectedChars, SquadViewModel squad) { }
	// RVA: 0x2380470 VA: 0x7594998470
	public static String UpdateCharSelectedSkill(Int32 instId, String prevSkill, IList`1 squad) { }
	// RVA: 0x23806f4 VA: 0x75949986f4
	public static String UpdateCharSelectedBranch(Int32 instId, String prevEquip, IList`1 squad) { }
	// RVA: 0x237fdcc VA: 0x7594997dcc
	public static Void PlaySquadVoice(VoiceQuery query, Int32 squadIndex) { }
	// RVA: 0x237fec8 VA: 0x7594997ec8
	public static Void PlaySquadVoice(IList`1 prevSquad, IList`1 newSquad) { }
	// RVA: 0x238091c VA: 0x759499891c
	public static Void PlaySquadVoice(IList`1 prevSquad, IList`1 newSquad) { }
	// RVA: 0x2380a08 VA: 0x7594998a08
	public Void EventOnSquadTabClick(Int32 index) { }
	// RVA: 0x2380d9c VA: 0x7594998d9c
	public Void EventOnSquadLeftClick(Int32 delta) { }
	// RVA: 0x2380f70 VA: 0x7594998f70
	public Void EventOnClearBtnClick() { }
	// RVA: 0x2381174 VA: 0x7594999174
	public Void EventOnSingleFormatClick(Int32 memberIndex) { }
	// RVA: 0x2381c38 VA: 0x7594999c38
	public Void EventOnRenameClick(Int32 squadIndex) { }
	// RVA: 0x2381d64 VA: 0x7594999d64
	public Void EventOnMultiFormatClick() { }
	// RVA: 0x238208c VA: 0x759499a08c
	public Void EventOnStartBattleClick() { }
	// RVA: 0x2382c54 VA: 0x759499ac54
	private Void _OnInitTopMenu(GameObject topMenuObj) { }
	// RVA: 0x2382df4 VA: 0x759499adf4
	private Void _OnTopMenuRoutedToOtherPage(UIRouteTarget routeTarget, Object param, Action`2 baseHandler) { }
	// RVA: 0x2382f48 VA: 0x759499af48
	public Void CleanAssist() { }
	// RVA: 0x2383014 VA: 0x759499b014
	private Void _OnStartBattleSuccess() { }
	// RVA: 0x23832f8 VA: 0x759499b2f8
	public static CharacterCardViewModel PickRandomCharacter(IList`1 squad) { }
	// RVA: 0x23835b4 VA: 0x759499b5b4
	private Void _DeleteCurrentSquad() { }
	// RVA: 0x238151c VA: 0x759499951c
	private Input _ParseSquadSelectParam(Boolean isSingleMode, Int32 memberIndex) { }
	// RVA: 0x2380b44 VA: 0x7594998b44
	private Void _SaveSquadFormationIfNeeded(Action`1 nextStep, Boolean mustGoNext) { }
	// RVA: 0x2383d34 VA: 0x759499bd34
	private SquadFormationRequest _ParseSquadFormationRequest() { }
	// RVA: 0x238447c VA: 0x759499c47c
	public static Void SendAssistCharListRequest(ProfessionCategory profession, Boolean refreshFlag, String squadId, Action`1 onProceed) { }
	// RVA: 0x23846fc VA: 0x759499c6fc
	public Void GetSquadAssist() { }
	// RVA: 0x23848a4 VA: 0x759499c8a4
	private Param _CreateParamToStartBattle() { }
	// RVA: 0x2385f60 VA: 0x759499df60
	private String _GetRetroGroupIdForStartBattle(String stageId) { }
	// RVA: 0x2386e28 VA: 0x759499ee28
	private Void _InvokedStartBattle(Param param) { }
	// RVA: 0x2386fb8 VA: 0x759499efb8
	private Void _OnResReadyToStartBattle(Param param) { }
	// RVA: 0x23870fc VA: 0x759499f0fc
	private Void _QuitSquad(SquadFormationResponse response) { }
	// RVA: 0x2387194 VA: 0x759499f194
	private Void _RaiseSavedSquadSignal() { }
	// RVA: 0x23871f8 VA: 0x759499f1f8
	private Void _AlertSquadInvalid() { }
	// RVA: 0x238307c VA: 0x759499b07c
	private Void _SaveCacheStageConfig() { }
	// RVA: 0x23872e8 VA: 0x759499f2e8
	private Boolean _CheckIfStartBattleValid() { }
	// RVA: 0x2387a50 VA: 0x759499fa50
	private Boolean _CheckIfStageCrossDays(Params squadParam) { }
	// RVA: 0x2387b18 VA: 0x759499fb18
	private SquadItemStruct[] _GetCurSquadMembers() { }
	// RVA: 0x2387c64 VA: 0x759499fc64
	private Void _ConfirmTipsAndDoStartBattle() { }
	// RVA: 0x2382b08 VA: 0x759499ab08
	private Void _DoStartBattle() { }
	// RVA: 0x237e428 VA: 0x7594996428
	private Void _TriggerSquadPluginResume() { }
	// RVA: 0x23802a8 VA: 0x75949982a8
	private static SquadItemStruct _FindInstInSquad(Int32 instId, IList`1 squad) { }
	// RVA: 0x2387d44 VA: 0x759499fd44
	public Void .ctor() { }
	// RVA: 0x2387e08 VA: 0x759499fe08
	private Void <RegisterToDataListener>b__28_0(IStateBean stateBean) { }
	// RVA: 0x2387f04 VA: 0x759499ff04
	private Void <RegisterToDataListener>b__28_1(IStateBean stateBean) { }
	// RVA: 0x23881cc VA: 0x75949a01cc
	private Void <RegisterToDataListener>b__28_2(IStateBean stateBean) { }
	// RVA: 0x2388624 VA: 0x75949a0624
	private Void <RegisterFromDataListener>b__30_0(IStateBean stateBean) { }
	// RVA: 0x2388790 VA: 0x75949a0790
	private Void <RegisterFromDataListener>b__30_1(IStateBean stateBean) { }
	// RVA: 0x2388af4 VA: 0x75949a0af4
	private Void <RegisterFromDataListener>b__30_2(IStateBean stateBean) { }
	// RVA: 0x2388b8c VA: 0x75949a0b8c
	private Void <RegisterFromDataListener>b__30_3(IStateBean friendAssistBean) { }
	// RVA: 0x2388d10 VA: 0x75949a0d10
	private Void <_OnInitTopMenu>b__48_0() { }
	// RVA: 0x2388ea8 VA: 0x75949a0ea8
	private Void <GetSquadAssist>b__58_0(GetFriendAssistCharListResponse response) { }
	// RVA: 0x2388f0c VA: 0x75949a0f0c
	private Void <_AlertSquadInvalid>b__65_0() { }
	// RVA: 0x2388f2c VA: 0x75949a0f2c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2388f34 VA: 0x75949a0f34
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2388f3c VA: 0x75949a0f3c
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x2388f44 VA: 0x75949a0f44
	private Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type P0) { }
	// RVA: 0x2388f4c VA: 0x75949a0f4c
	private Dictionary`2 <>xLuaBaseProxy_RegisterFromDataListener() { }
}
```