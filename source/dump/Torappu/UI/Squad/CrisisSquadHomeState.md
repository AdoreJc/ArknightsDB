# CrisisSquadHomeState

**Namespace:** `Torappu.UI.Squad`


## Fields

- `PrefabInstHolder _topMenuContainer`

- `SquadAssistCardView _assistCard`

- `RuneSquadGroupController _squadGroupController`

- `SquadCharSelectMaskPlugin _charSelectMask`

- `CrisisSquadStateBean m_stateBean`

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

- `Void <RegisterToDataListener>b__15_0(IStateBean)`

- `Void <RegisterToDataListener>b__15_1(IStateBean)`

- `Void <RegisterFromDataListener>b__17_0(IStateBean)`

- `Void <_InitIfNot>b__19_0(GameObject)`

- `Void <_InitIfNot>b__19_1()`

- `Void <_InitIfNot>b__19_2()`

- `Void <EventOnAssistClicked>b__28_0(GetFriendAssistCharListResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Squad
public class CrisisSquadHomeState : State, IRuneSquadController, ISquadCharSelectContext
{
	private PrefabInstHolder _topMenuContainer; // 0x50
	private SquadAssistCardView _assistCard; // 0x58
	private RuneSquadGroupController _squadGroupController; // 0x60
	private SquadCharSelectMaskPlugin _charSelectMask; // 0x68
	private CrisisSquadStateBean m_stateBean; // 0x70
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


	// RVA: 0x2372e34 VA: 0x759498ae34
	protected override Void OnEnter() { }
	// RVA: 0x23730fc VA: 0x759498b0fc
	protected override Void OnResume() { }
	// RVA: 0x2373198 VA: 0x759498b198
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2373200 VA: 0x759498b200
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x23733f4 VA: 0x759498b3f4
	public override Boolean UseEarlyFromDataListener(Type fromState) { }
	// RVA: 0x237346c VA: 0x759498b46c
	public override Dictionary`2 RegisterFromDataListener() { }
	// RVA: 0x2373660 VA: 0x759498b660
	public static LockedStyle GenLockedStyle4CharInvalid() { }
	// RVA: 0x237301c VA: 0x759498b01c
	private Void _InitIfNot() { }
	// RVA: 0x23737a8 VA: 0x759498b7a8
	public Boolean CheckIfCharInstSelectable(Int32 instId) { }
	// RVA: 0x2373920 VA: 0x759498b920
	public Boolean CheckIfCharSelectable(CharQuery charQuery) { }
	// RVA: 0x23739e4 VA: 0x759498b9e4
	public List`1 GetTempListForExclusiveInstIds() { }
	// RVA: 0x2373a4c VA: 0x759498ba4c
	public SquadGroupViewModel GetSquadGroupViewModel() { }
	// RVA: 0x2373ad4 VA: 0x759498bad4
	private Void _OnSingleFormationClicked(Int32 index) { }
	// RVA: 0x2373c84 VA: 0x759498bc84
	private Void _OnTopMenuRoutedToOtherPage(UIRouteTarget routeTarget, Object param, Action`2 baseHandler) { }
	// RVA: 0x2373e70 VA: 0x759498be70
	public Void EventOnMultiFormationClicked() { }
	// RVA: 0x2373ef8 VA: 0x759498bef8
	public Void EventOnClearAssistClicked() { }
	// RVA: 0x2373fc4 VA: 0x759498bfc4
	public Void EventOnAssistClicked() { }
	// RVA: 0x2374278 VA: 0x759498c278
	public Void EventOnStartBattleClicked() { }
	// RVA: 0x2373b78 VA: 0x759498bb78
	private Void _GoToCharSelectState() { }
	// RVA: 0x237416c VA: 0x759498c16c
	private Void _GoToFriendAssistState() { }
	// RVA: 0x2374464 VA: 0x759498c464
	private Void _OnCharSelectFinished(IStateBean stateBean) { }
	// RVA: 0x2374638 VA: 0x759498c638
	private Input _ParseSquadSelectParam() { }
	// RVA: 0x2373dc4 VA: 0x759498bdc4
	private Void _SaveSquadFormationIfNeeded(Action nextStep) { }
	// RVA: 0x2374bcc VA: 0x759498cbcc
	private SquadItemStruct[] _GetCurSquadMembers() { }
	// RVA: 0x237431c VA: 0x759498c31c
	private Void _DoStartBattle() { }
	// RVA: 0x2374d18 VA: 0x759498cd18
	private Void _InvokedStartBattle() { }
	// RVA: 0x23753a4 VA: 0x759498d3a4
	public Void .ctor() { }
	// RVA: 0x23754a4 VA: 0x759498d4a4
	private Void <RegisterToDataListener>b__15_0(IStateBean stateBean) { }
	// RVA: 0x2375660 VA: 0x759498d660
	private Void <RegisterToDataListener>b__15_1(IStateBean stateBean) { }
	// RVA: 0x237573c VA: 0x759498d73c
	private Void <RegisterFromDataListener>b__17_0(IStateBean friendAssistBean) { }
	// RVA: 0x23757c8 VA: 0x759498d7c8
	private Void <_InitIfNot>b__19_0(GameObject gameObj) { }
	// RVA: 0x2375928 VA: 0x759498d928
	private Void <_InitIfNot>b__19_1() { }
	// RVA: 0x23759a8 VA: 0x759498d9a8
	private Void <_InitIfNot>b__19_2() { }
	// RVA: 0x23759c8 VA: 0x759498d9c8
	private Void <EventOnAssistClicked>b__28_0(GetFriendAssistCharListResponse response) { }
	// RVA: 0x2375a2c VA: 0x759498da2c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2375a34 VA: 0x759498da34
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2375a3c VA: 0x759498da3c
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x2375a44 VA: 0x759498da44
	private Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type P0) { }
	// RVA: 0x2375a4c VA: 0x759498da4c
	private Dictionary`2 <>xLuaBaseProxy_RegisterFromDataListener() { }
}
```