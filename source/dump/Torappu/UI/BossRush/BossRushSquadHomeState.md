# BossRushSquadHomeState

**Namespace:** `Torappu.UI.BossRush`


## Fields

- `TopMenuDynamicPrefabInstHolder _topMenuHolder`

- `BossRushSquadGroupController _squadGroupController`

- `SquadAssistCardView _assistCard`

- `SquadHomePluginLoader _homePluginLoader`

- `Image _startBattleImg`

- `Boolean m_isInited`

- `BossRushSquadStateBean m_stateBean`

- `CharSelectStateBeanInput m_charSelectStateBeanInput`

- `SquadHomePlugin m_squadHomePlugin`

- `SquadCharSelectMaskPlugin m_charSelectMaskPluginPrefab`


## Methods

- `SquadGroupViewModel GetSquadGroupViewModel()`

- `Boolean CheckIfCharSelectable(CharQuery)`

- `Void _InitIfNot()`

- `Void _OnInitTopMenu(GameObject)`

- `Void _OnTopMenuRoutedToOtherPage(UIRouteTarget, Object, Action`2)`

- `Void _DoStartBattle()`

- `Boolean _TryShowTipForStartBattle()`

- `Void _ConfirmTipsAndDoStartBattle()`

- `Boolean _CheckIfStartBattleValid()`

- `Void _InvokedStartBattle()`

- `Param _CreateParamToStartBattle()`

- `Void _OnStartBattleSuccess()`

- `Void _SaveCacheStageConfig()`

- `Void _RefreshStartBtnBg()`

- `Void _GoToFriendAssist()`

- `Void _PassDataToFriendAssist(IStateBean)`

- `Void _ClearFiendAssist()`

- `Void _OnAssistSelectFinished(IStateBean)`

- `Void _GoToCharSelect(Boolean, Int32)`

- `Void _PassDataToCharSelect(IStateBean)`

- `CharSelectStateBeanInput _ParseSquadSelectParam(Boolean, Int32)`

- `Void _OnCharSelectFinished(IStateBean)`

- `Boolean _CheckCharInstSelectable(Int32, String)`

- `Void _InitSquadPlugin()`

- `Void _TriggerSquadPluginResume()`

- `PluginInputParams _CreatePluginParam()`

- `Void _SwitchSquad(Int32, Boolean, Boolean)`

- `Void _SaveSquadFormationIfNeeded(Action)`

- `Void _EventOnSquadTabClick(Int32)`

- `Void EventOnSquadLeftRightClick(Int32)`

- `Void _EventOnSingleFormationClicked(Int32)`

- `Void EventOnMultiFormationClicked()`

- `Void EventOnAssistBtnClick()`

- `Void EventOnAssistClearClick()`

- `Void EventOnStartBtnClick()`

- `Void <_OnInitTopMenu>b__24_0()`

- `Void <_OnInitTopMenu>b__24_1()`

- `Void <_CheckIfStartBattleValid>b__29_0()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BossRush
public class BossRushSquadHomeState : State, IRuneSquadController, ISquadCharSelectContext
{
	private TopMenuDynamicPrefabInstHolder _topMenuHolder; // 0x50
	private BossRushSquadGroupController _squadGroupController; // 0x58
	private SquadAssistCardView _assistCard; // 0x60
	private SquadHomePluginLoader _homePluginLoader; // 0x68
	private Image _startBattleImg; // 0x70
	private Boolean m_isInited; // 0x78
	private BossRushSquadStateBean m_stateBean; // 0x80
	private CharSelectStateBeanInput m_charSelectStateBeanInput; // 0x88
	private List`1 m_tempListForExclusiveInstIds; // 0xe0
	private SquadHomePlugin m_squadHomePlugin; // 0xe8
	private SquadCharSelectMaskPlugin m_charSelectMaskPluginPrefab; // 0xf0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x18
	private static DelegateBridge __Hotfix0_UseEarlyFromDataListener; // 0x20
	private static DelegateBridge __Hotfix0_RegisterFromDataListener; // 0x28
	private static DelegateBridge __Hotfix0_GetTempListForExclusiveInstIds; // 0x30
	private static DelegateBridge __Hotfix0_GetSquadGroupViewModel; // 0x38
	private static DelegateBridge __Hotfix0_CheckIfCharSelectable; // 0x40
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x48
	private static DelegateBridge __Hotfix0__OnInitTopMenu; // 0x50
	private static DelegateBridge __Hotfix0__OnTopMenuRoutedToOtherPage; // 0x58
	private static DelegateBridge __Hotfix0__DoStartBattle; // 0x60
	private static DelegateBridge __Hotfix0__TryShowTipForStartBattle; // 0x68
	private static DelegateBridge __Hotfix0__ConfirmTipsAndDoStartBattle; // 0x70
	private static DelegateBridge __Hotfix0__CheckIfStartBattleValid; // 0x78
	private static DelegateBridge __Hotfix0__InvokedStartBattle; // 0x80
	private static DelegateBridge __Hotfix0__CreateParamToStartBattle; // 0x88
	private static DelegateBridge __Hotfix0__OnStartBattleSuccess; // 0x90
	private static DelegateBridge __Hotfix0__SaveCacheStageConfig; // 0x98
	private static DelegateBridge __Hotfix0__RefreshStartBtnBg; // 0xa0
	private static DelegateBridge __Hotfix0__GoToFriendAssist; // 0xa8
	private static DelegateBridge __Hotfix0__PassDataToFriendAssist; // 0xb0
	private static DelegateBridge __Hotfix0__ClearFiendAssist; // 0xb8
	private static DelegateBridge __Hotfix0__OnAssistSelectFinished; // 0xc0
	private static DelegateBridge __Hotfix0__GoToCharSelect; // 0xc8
	private static DelegateBridge __Hotfix0__PassDataToCharSelect; // 0xd0
	private static DelegateBridge __Hotfix0__ParseSquadSelectParam; // 0xd8
	private static DelegateBridge __Hotfix0__OnCharSelectFinished; // 0xe0
	private static DelegateBridge __Hotfix0__CheckCharInstSelectable; // 0xe8
	private static DelegateBridge __Hotfix0_GenLockedStyle4CharInvalid; // 0xf0
	private static DelegateBridge __Hotfix0__InitSquadPlugin; // 0xf8
	private static DelegateBridge __Hotfix0__TriggerSquadPluginResume; // 0x100
	private static DelegateBridge __Hotfix0__CreatePluginParam; // 0x108
	private static DelegateBridge __Hotfix0__SwitchSquad; // 0x110
	private static DelegateBridge __Hotfix0__SaveSquadFormationIfNeeded; // 0x118
	private static DelegateBridge __Hotfix0__GetCurSquadMembers; // 0x120
	private static DelegateBridge __Hotfix0__EventOnSquadTabClick; // 0x128
	private static DelegateBridge __Hotfix0_EventOnSquadLeftRightClick; // 0x130
	private static DelegateBridge __Hotfix0__EventOnSingleFormationClicked; // 0x138
	private static DelegateBridge __Hotfix0_EventOnMultiFormationClicked; // 0x140
	private static DelegateBridge __Hotfix0_EventOnAssistBtnClick; // 0x148
	private static DelegateBridge __Hotfix0_EventOnAssistClearClick; // 0x150
	private static DelegateBridge __Hotfix0_EventOnStartBtnClick; // 0x158
	private static DelegateBridge _c__Hotfix0_ctor; // 0x160


	// RVA: 0x2e65b78 VA: 0x759547db78
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2e65be0 VA: 0x759547dbe0
	protected override Void OnEnter() { }
	// RVA: 0x2e662bc VA: 0x759547e2bc
	protected override Void OnResume() { }
	// RVA: 0x2e66434 VA: 0x759547e434
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2e66628 VA: 0x759547e628
	public override Boolean UseEarlyFromDataListener(Type fromState) { }
	// RVA: 0x2e666a0 VA: 0x759547e6a0
	public override Dictionary`2 RegisterFromDataListener() { }
	// RVA: 0x2e66894 VA: 0x759547e894
	public List`1 GetTempListForExclusiveInstIds() { }
	// RVA: 0x2e668fc VA: 0x759547e8fc
	public SquadGroupViewModel GetSquadGroupViewModel() { }
	// RVA: 0x2e66984 VA: 0x759547e984
	public Boolean CheckIfCharSelectable(CharQuery charQuery) { }
	// RVA: 0x2e65e18 VA: 0x759547de18
	private Void _InitIfNot() { }
	// RVA: 0x2e66b0c VA: 0x759547eb0c
	private Void _OnInitTopMenu(GameObject topMenuObj) { }
	// RVA: 0x2e66cd0 VA: 0x759547ecd0
	private Void _OnTopMenuRoutedToOtherPage(UIRouteTarget routeTarget, Object param, Action`2 baseHandler) { }
	// RVA: 0x2e66eb8 VA: 0x759547eeb8
	private Void _DoStartBattle() { }
	// RVA: 0x2e67528 VA: 0x759547f528
	private Boolean _TryShowTipForStartBattle() { }
	// RVA: 0x2e67bdc VA: 0x759547fbdc
	private Void _ConfirmTipsAndDoStartBattle() { }
	// RVA: 0x2e66fc4 VA: 0x759547efc4
	private Boolean _CheckIfStartBattleValid() { }
	// RVA: 0x2e6811c VA: 0x759548011c
	private Void _InvokedStartBattle() { }
	// RVA: 0x2e68288 VA: 0x7595480288
	private Param _CreateParamToStartBattle() { }
	// RVA: 0x2e691a0 VA: 0x75954811a0
	private Void _OnStartBattleSuccess() { }
	// RVA: 0x2e69208 VA: 0x7595481208
	private Void _SaveCacheStageConfig() { }
	// RVA: 0x2e661a4 VA: 0x759547e1a4
	private Void _RefreshStartBtnBg() { }
	// RVA: 0x2e69308 VA: 0x7595481308
	private Void _GoToFriendAssist() { }
	// RVA: 0x2e6976c VA: 0x759548176c
	private Void _PassDataToFriendAssist(IStateBean stateBean) { }
	// RVA: 0x2e699ac VA: 0x75954819ac
	private Void _ClearFiendAssist() { }
	// RVA: 0x2e69a78 VA: 0x7595481a78
	private Void _OnAssistSelectFinished(IStateBean stateBean) { }
	// RVA: 0x2e69c54 VA: 0x7595481c54
	private Void _GoToCharSelect(Boolean isSingleMode, Int32 memberIndex) { }
	// RVA: 0x2e6a64c VA: 0x759548264c
	private Void _PassDataToCharSelect(IStateBean stateBean) { }
	// RVA: 0x2e69e24 VA: 0x7595481e24
	private CharSelectStateBeanInput _ParseSquadSelectParam(Boolean isSingleMode, Int32 memberIndex) { }
	// RVA: 0x2e6aa4c VA: 0x7595482a4c
	private Void _OnCharSelectFinished(IStateBean stateBean) { }
	// RVA: 0x2e6ac1c VA: 0x7595482c1c
	private Boolean _CheckCharInstSelectable(Int32 instId, String teamId) { }
	// RVA: 0x2e6ae18 VA: 0x7595482e18
	private static LockedStyle GenLockedStyle4CharInvalid() { }
	// RVA: 0x2e66058 VA: 0x759547e058
	private Void _InitSquadPlugin() { }
	// RVA: 0x2e663b8 VA: 0x759547e3b8
	private Void _TriggerSquadPluginResume() { }
	// RVA: 0x2e6af60 VA: 0x7595482f60
	private PluginInputParams _CreatePluginParam() { }
	// RVA: 0x2e6aff0 VA: 0x7595482ff0
	private Void _SwitchSquad(Int32 index, Boolean isTabClick, Boolean needCache) { }
	// RVA: 0x2e66e10 VA: 0x759547ee10
	private Void _SaveSquadFormationIfNeeded(Action nextStep) { }
	// RVA: 0x2e6b814 VA: 0x7595483814
	private SquadItemStruct[] _GetCurSquadMembers() { }
	// RVA: 0x2e6b938 VA: 0x7595483938
	private Void _EventOnSquadTabClick(Int32 index) { }
	// RVA: 0x2e6b9c0 VA: 0x75954839c0
	public Void EventOnSquadLeftRightClick(Int32 delta) { }
	// RVA: 0x2e6ba64 VA: 0x7595483a64
	private Void _EventOnSingleFormationClicked(Int32 memberIndex) { }
	// RVA: 0x2e6bb04 VA: 0x7595483b04
	public Void EventOnMultiFormationClicked() { }
	// RVA: 0x2e6bb8c VA: 0x7595483b8c
	public Void EventOnAssistBtnClick() { }
	// RVA: 0x2e6bc0c VA: 0x7595483c0c
	public Void EventOnAssistClearClick() { }
	// RVA: 0x2e6bc8c VA: 0x7595483c8c
	public Void EventOnStartBtnClick() { }
	// RVA: 0x2e6bd18 VA: 0x7595483d18
	public Void .ctor() { }
	// RVA: 0x2e6bf08 VA: 0x7595483f08
	private Void <_OnInitTopMenu>b__24_0() { }
	// RVA: 0x2e6bf88 VA: 0x7595483f88
	private Void <_OnInitTopMenu>b__24_1() { }
	// RVA: 0x2e6bfa8 VA: 0x7595483fa8
	private Void <_CheckIfStartBattleValid>b__29_0() { }
	// RVA: 0x2e6bfc8 VA: 0x7595483fc8
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2e6bfd0 VA: 0x7595483fd0
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2e6bfd8 VA: 0x7595483fd8
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x2e6bfe0 VA: 0x7595483fe0
	private Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type P0) { }
	// RVA: 0x2e6bfe8 VA: 0x7595483fe8
	private Dictionary`2 <>xLuaBaseProxy_RegisterFromDataListener() { }
}
```