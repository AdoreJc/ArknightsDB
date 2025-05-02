# RuneSquadHomeState

**Namespace:** `Torappu.UI.Squad`


## Fields

- `PrefabInstHolder _topMenuContainer`

- `SquadAssistCardView _assistCard`

- `RuneSquadGroupController _squadGroupController`

- `SquadCharSelectMaskPlugin _charSelectMask`

- `RuneSquadHomeStateBeanV1 m_stateBean`

- `CharSelectContext m_charSelectContext`

- `Boolean m_isInited`

- `DefaultCharSelectInput m_charSelectInputParam`


## Methods

- `Void _InitIfNot()`

- `Boolean CheckIfCharInstSelectable(Int32)`

- `Boolean CheckIfCharSelectable(CharQuery)`

- `SquadGroupViewModel GetSquadGroupViewModel()`

- `Void _OnSingleFormationClicked(Int32)`

- `Void _OnTopMenuRoutedToOtherPage(UIRouteTarget, Object, Action`2)`

- `Void EventOnMultiFormationClicked()`

- `Void EventOnClearAssistClicked()`

- `Void EventOnAssistClicked()`

- `Void EventOnStartBattleClicked()`

- `Void _GoToCharSelectState()`

- `Void _GoToFriendAssistState()`

- `Void _OnCharSelectFinished(IStateBean)`

- `Input _ParseSquadSelectParam()`

- `Void _SaveSquadFormationIfNeeded(Action)`

- `Void _DoStartBattle()`

- `Void _InvokedStartBattle()`

- `Void <RegisterToDataListener>b__16_0(IStateBean)`

- `Void <RegisterToDataListener>b__16_1(IStateBean)`

- `Void <RegisterFromDataListener>b__18_0(IStateBean)`

- `Void <_InitIfNot>b__20_0(GameObject)`

- `Void <_InitIfNot>b__20_1()`

- `Void <_InitIfNot>b__20_2()`

- `Void <EventOnAssistClicked>b__29_0(GetFriendAssistCharListResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Squad
public class RuneSquadHomeState : State, IRuneSquadController, ISquadCharSelectContext
{
	private PrefabInstHolder _topMenuContainer; // 0x50
	private SquadAssistCardView _assistCard; // 0x58
	private RuneSquadGroupController _squadGroupController; // 0x60
	private SquadCharSelectMaskPlugin _charSelectMask; // 0x68
	private RuneSquadHomeStateBeanV1 m_stateBean; // 0x70
	private CharSelectContext m_charSelectContext; // 0x78
	private Boolean m_isInited; // 0x80
	private DefaultCharSelectInput m_charSelectInputParam; // 0x88
	private List`1 m_tempListForExclusiveInstIds; // 0xd0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_OnResume; // 0x8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x10
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x18
	private static DelegateBridge __Hotfix0_UseEarlyFromDataListener; // 0x20
	private static DelegateBridge __Hotfix0_RegisterFromDataListener; // 0x28
	private static DelegateBridge __Hotfix0_GenLockedStyle4CharInvalid; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x38
	private static DelegateBridge __Hotfix0_CheckIfCharInstSelectable; // 0x40
	private static DelegateBridge __Hotfix0_CheckIfCharSelectable; // 0x48
	private static DelegateBridge __Hotfix0_GetTempListForExclusiveInstIds; // 0x50
	private static DelegateBridge __Hotfix0_GetSquadGroupViewModel; // 0x58
	private static DelegateBridge __Hotfix0__OnSingleFormationClicked; // 0x60
	private static DelegateBridge __Hotfix0__OnTopMenuRoutedToOtherPage; // 0x68
	private static DelegateBridge __Hotfix0_EventOnMultiFormationClicked; // 0x70
	private static DelegateBridge __Hotfix0_EventOnClearAssistClicked; // 0x78
	private static DelegateBridge __Hotfix0_EventOnAssistClicked; // 0x80
	private static DelegateBridge __Hotfix0_EventOnStartBattleClicked; // 0x88
	private static DelegateBridge __Hotfix0__GoToCharSelectState; // 0x90
	private static DelegateBridge __Hotfix0__GoToFriendAssistState; // 0x98
	private static DelegateBridge __Hotfix0__OnCharSelectFinished; // 0xa0
	private static DelegateBridge __Hotfix0__ParseSquadSelectParam; // 0xa8
	private static DelegateBridge __Hotfix0__SaveSquadFormationIfNeeded; // 0xb0
	private static DelegateBridge __Hotfix0__GetCurSquadMembers; // 0xb8
	private static DelegateBridge __Hotfix0__DoStartBattle; // 0xc0
	private static DelegateBridge __Hotfix0__InvokedStartBattle; // 0xc8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xd0


	// RVA: 0x23764fc VA: 0x759498e4fc
	protected override Void OnEnter() { }
	// RVA: 0x23767c4 VA: 0x759498e7c4
	protected override Void OnResume() { }
	// RVA: 0x2376860 VA: 0x759498e860
	public override IStateBean GetCacheBean() { }
	// RVA: 0x23768c8 VA: 0x759498e8c8
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2376abc VA: 0x759498eabc
	public override Boolean UseEarlyFromDataListener(Type fromState) { }
	// RVA: 0x2376b34 VA: 0x759498eb34
	public override Dictionary`2 RegisterFromDataListener() { }
	// RVA: 0x2376d28 VA: 0x759498ed28
	public static LockedStyle GenLockedStyle4CharInvalid() { }
	// RVA: 0x23766e4 VA: 0x759498e6e4
	private Void _InitIfNot() { }
	// RVA: 0x2376e70 VA: 0x759498ee70
	public Boolean CheckIfCharInstSelectable(Int32 instId) { }
	// RVA: 0x2376fe8 VA: 0x759498efe8
	public Boolean CheckIfCharSelectable(CharQuery charQuery) { }
	// RVA: 0x23770ac VA: 0x759498f0ac
	public List`1 GetTempListForExclusiveInstIds() { }
	// RVA: 0x2377114 VA: 0x759498f114
	public SquadGroupViewModel GetSquadGroupViewModel() { }
	// RVA: 0x237719c VA: 0x759498f19c
	private Void _OnSingleFormationClicked(Int32 index) { }
	// RVA: 0x237734c VA: 0x759498f34c
	private Void _OnTopMenuRoutedToOtherPage(UIRouteTarget routeTarget, Object param, Action`2 baseHandler) { }
	// RVA: 0x2377538 VA: 0x759498f538
	public Void EventOnMultiFormationClicked() { }
	// RVA: 0x23775c0 VA: 0x759498f5c0
	public Void EventOnClearAssistClicked() { }
	// RVA: 0x237768c VA: 0x759498f68c
	public Void EventOnAssistClicked() { }
	// RVA: 0x2377940 VA: 0x759498f940
	public Void EventOnStartBattleClicked() { }
	// RVA: 0x2377240 VA: 0x759498f240
	private Void _GoToCharSelectState() { }
	// RVA: 0x2377834 VA: 0x759498f834
	private Void _GoToFriendAssistState() { }
	// RVA: 0x2377b2c VA: 0x759498fb2c
	private Void _OnCharSelectFinished(IStateBean stateBean) { }
	// RVA: 0x2377d00 VA: 0x759498fd00
	private Input _ParseSquadSelectParam() { }
	// RVA: 0x237748c VA: 0x759498f48c
	private Void _SaveSquadFormationIfNeeded(Action nextStep) { }
	// RVA: 0x23781e8 VA: 0x75949901e8
	private SquadItemStruct[] _GetCurSquadMembers() { }
	// RVA: 0x23779e4 VA: 0x759498f9e4
	private Void _DoStartBattle() { }
	// RVA: 0x2378334 VA: 0x7594990334
	private Void _InvokedStartBattle() { }
	// RVA: 0x23789a8 VA: 0x75949909a8
	public Void .ctor() { }
	// RVA: 0x2378aa8 VA: 0x7594990aa8
	private Void <RegisterToDataListener>b__16_0(IStateBean stateBean) { }
	// RVA: 0x2378c64 VA: 0x7594990c64
	private Void <RegisterToDataListener>b__16_1(IStateBean stateBean) { }
	// RVA: 0x2378d40 VA: 0x7594990d40
	private Void <RegisterFromDataListener>b__18_0(IStateBean friendAssistBean) { }
	// RVA: 0x2378dcc VA: 0x7594990dcc
	private Void <_InitIfNot>b__20_0(GameObject gameObj) { }
	// RVA: 0x2378f2c VA: 0x7594990f2c
	private Void <_InitIfNot>b__20_1() { }
	// RVA: 0x2378fac VA: 0x7594990fac
	private Void <_InitIfNot>b__20_2() { }
	// RVA: 0x2378fcc VA: 0x7594990fcc
	private Void <EventOnAssistClicked>b__29_0(GetFriendAssistCharListResponse response) { }
	// RVA: 0x2379030 VA: 0x7594991030
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2379038 VA: 0x7594991038
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2379040 VA: 0x7594991040
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x2379048 VA: 0x7594991048
	private Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type P0) { }
	// RVA: 0x2379050 VA: 0x7594991050
	private Dictionary`2 <>xLuaBaseProxy_RegisterFromDataListener() { }
}
```