# Act1LockSquadHomeState

**Namespace:** `Torappu.Activity.Act1Lock.UI`


## Fields

- `SquadCharSelectMaskPlugin _charSelectMaskPluginPrefab`

- `RectTransform _topMenuContainer`

- `Animator _deleteState`

- `Act1LockSquadGroupController _squadGroupController`

- `Act1LockAssistCardView _assistCard`

- `Image _startBattleImg`

- `Image _finRegionImg`

- `Image _interlockRegionImg`

- `Boolean m_isInited`

- `Act1LockSquadStateBean m_stateBean`

- `CharSelectContext m_charSelectContext`

- `Boolean m_deleteFlag`

- `DefaultCharSelectInput m_charSelectInputParam`


## Methods

- `Void _InitIfNot()`

- `Void _RenderRegion()`

- `Void _OnTopMenuRoutedToOtherPage(UIRouteTarget, Object, Action`2)`

- `Void _SaveSquadFormationIfNeeded(Action`1, Boolean, Boolean)`

- `Void _SaveSquadIfNeededBeforeStartBattle(Action`1)`

- `Act1LockSetSquadRequest _ParseSquadFormationRequest()`

- `Boolean _CheckIfStartBattleValid()`

- `Void _AlertSquadInvalid()`

- `Void _OnSlotClicked(Int32)`

- `Void _DeleteCurrentSquad()`

- `Void _DoStartBattle()`

- `Void _InvokedStartBattle(Act1LockSetSquadResponse)`

- `Void _OnStartBattleSuccess()`

- `Void _SaveCacheStageConfig()`

- `Input _ParseSquadSelectParam()`

- `Void _OnCharSelectFinished(IStateBean)`

- `Void _OnAssistSelectFinished(IStateBean)`

- `Void EventOnMultiFormatClick()`

- `Void EventOnClearBtnClick()`

- `Void EventOnAssistBtnClick()`

- `Void EventOnAssistClearClick()`

- `Void EventOnStartBtnClick()`

- `Boolean CheckCharInstSelectable(Int32)`

- `SquadGroupViewModel GetSquadGroupViewModel()`

- `Boolean CheckIfCharSelectable(CharQuery)`

- `Void <RegisterToDataListener>b__22_0(IStateBean)`

- `Void <RegisterToDataListener>b__22_1(IStateBean)`

- `Void <_InitIfNot>b__25_0()`

- `Void <_InitIfNot>b__25_1(Act1LockSetSquadResponse)`

- `Void <_AlertSquadInvalid>b__32_0()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Lock.UI
public class Act1LockSquadHomeState : State, IRuneSquadController, ISquadCharSelectContext
{
	private const String ANIMATORPARAM; // 0x0
	private SquadCharSelectMaskPlugin _charSelectMaskPluginPrefab; // 0x50
	private RectTransform _topMenuContainer; // 0x58
	private Animator _deleteState; // 0x60
	private Act1LockSquadGroupController _squadGroupController; // 0x68
	private Act1LockAssistCardView _assistCard; // 0x70
	private Image _startBattleImg; // 0x78
	private Image _finRegionImg; // 0x80
	private Image _interlockRegionImg; // 0x88
	private Sprite[] _interlockRegionSprites; // 0x90
	private Boolean m_isInited; // 0x98
	private Act1LockSquadStateBean m_stateBean; // 0xa0
	private CharSelectContext m_charSelectContext; // 0xa8
	private Boolean m_deleteFlag; // 0xb0
	private DefaultCharSelectInput m_charSelectInputParam; // 0xb8
	private List`1 m_tempListForExclusiveInstIds; // 0x100
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x18
	private static DelegateBridge __Hotfix0_UseEarlyFromDataListener; // 0x20
	private static DelegateBridge __Hotfix0_RegisterFromDataListener; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0__RenderRegion; // 0x38
	private static DelegateBridge __Hotfix0__OnTopMenuRoutedToOtherPage; // 0x40
	private static DelegateBridge __Hotfix0__SaveSquadFormationIfNeeded; // 0x48
	private static DelegateBridge __Hotfix0__SaveSquadIfNeededBeforeStartBattle; // 0x50
	private static DelegateBridge __Hotfix0__ParseSquadFormationRequest; // 0x58
	private static DelegateBridge __Hotfix0__CheckIfStartBattleValid; // 0x60
	private static DelegateBridge __Hotfix0__AlertSquadInvalid; // 0x68
	private static DelegateBridge __Hotfix0__OnSlotClicked; // 0x70
	private static DelegateBridge __Hotfix0__DeleteCurrentSquad; // 0x78
	private static DelegateBridge __Hotfix0__DoStartBattle; // 0x80
	private static DelegateBridge __Hotfix0__InvokedStartBattle; // 0x88
	private static DelegateBridge __Hotfix0__PickRandomCharacter; // 0x90
	private static DelegateBridge __Hotfix0__OnStartBattleSuccess; // 0x98
	private static DelegateBridge __Hotfix0__SaveCacheStageConfig; // 0xa0
	private static DelegateBridge __Hotfix0__ParseSquadSelectParam; // 0xa8
	private static DelegateBridge __Hotfix0__GetCurSquadMembers; // 0xb0
	private static DelegateBridge __Hotfix0__OnCharSelectFinished; // 0xb8
	private static DelegateBridge __Hotfix0__OnAssistSelectFinished; // 0xc0
	private static DelegateBridge __Hotfix0_EventOnMultiFormatClick; // 0xc8
	private static DelegateBridge __Hotfix0_EventOnClearBtnClick; // 0xd0
	private static DelegateBridge __Hotfix0_EventOnAssistBtnClick; // 0xd8
	private static DelegateBridge __Hotfix0_EventOnAssistClearClick; // 0xe0
	private static DelegateBridge __Hotfix0_EventOnStartBtnClick; // 0xe8
	private static DelegateBridge __Hotfix0_CheckCharInstSelectable; // 0xf0
	private static DelegateBridge __Hotfix0_GetTempListForExclusiveInstIds; // 0xf8
	private static DelegateBridge __Hotfix0_GetSquadGroupViewModel; // 0x100
	private static DelegateBridge __Hotfix0_CheckIfCharSelectable; // 0x108
	private static DelegateBridge _c__Hotfix0_ctor; // 0x110


	// RVA: 0x33a2b04 VA: 0x75959bab04
	public override IStateBean GetCacheBean() { }
	// RVA: 0x33a2b6c VA: 0x75959bab6c
	protected override Void OnEnter() { }
	// RVA: 0x33a3030 VA: 0x75959bb030
	protected override Void OnResume() { }
	// RVA: 0x33a30cc VA: 0x75959bb0cc
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x33a32c0 VA: 0x75959bb2c0
	public override Boolean UseEarlyFromDataListener(Type fromState) { }
	// RVA: 0x33a3338 VA: 0x75959bb338
	public override Dictionary`2 RegisterFromDataListener() { }
	// RVA: 0x33a2c60 VA: 0x75959bac60
	private Void _InitIfNot() { }
	// RVA: 0x33a2ef8 VA: 0x75959baef8
	private Void _RenderRegion() { }
	// RVA: 0x33a352c VA: 0x75959bb52c
	private Void _OnTopMenuRoutedToOtherPage(UIRouteTarget routeTarget, Object param, Action`2 baseHandler) { }
	// RVA: 0x33a3674 VA: 0x75959bb674
	private Void _SaveSquadFormationIfNeeded(Action`1 nextStep, Boolean mustGoNext, Boolean checkImmutable) { }
	// RVA: 0x33a3cf0 VA: 0x75959bbcf0
	private Void _SaveSquadIfNeededBeforeStartBattle(Action`1 nextStep) { }
	// RVA: 0x33a38e8 VA: 0x75959bb8e8
	private Act1LockSetSquadRequest _ParseSquadFormationRequest() { }
	// RVA: 0x33a3d78 VA: 0x75959bbd78
	private Boolean _CheckIfStartBattleValid() { }
	// RVA: 0x33a3f9c VA: 0x75959bbf9c
	private Void _AlertSquadInvalid() { }
	// RVA: 0x33a408c VA: 0x75959bc08c
	private Void _OnSlotClicked(Int32 index) { }
	// RVA: 0x33a41c4 VA: 0x75959bc1c4
	private Void _DeleteCurrentSquad() { }
	// RVA: 0x33a43ac VA: 0x75959bc3ac
	private Void _DoStartBattle() { }
	// RVA: 0x33a447c VA: 0x75959bc47c
	private Void _InvokedStartBattle(Act1LockSetSquadResponse squadResponse) { }
	// RVA: 0x33a4c5c VA: 0x75959bcc5c
	private static CharacterCardViewModel _PickRandomCharacter(SquadItemStruct[] squad) { }
	// RVA: 0x33a4e90 VA: 0x75959bce90
	private Void _OnStartBattleSuccess() { }
	// RVA: 0x33a4ef8 VA: 0x75959bcef8
	private Void _SaveCacheStageConfig() { }
	// RVA: 0x33a5110 VA: 0x75959bd110
	private Input _ParseSquadSelectParam() { }
	// RVA: 0x33a55ec VA: 0x75959bd5ec
	private SquadItemStruct[] _GetCurSquadMembers() { }
	// RVA: 0x33a5738 VA: 0x75959bd738
	private Void _OnCharSelectFinished(IStateBean stateBean) { }
	// RVA: 0x33a58fc VA: 0x75959bd8fc
	private Void _OnAssistSelectFinished(IStateBean stateBean) { }
	// RVA: 0x33a5a58 VA: 0x75959bda58
	public Void EventOnMultiFormatClick() { }
	// RVA: 0x33a5c20 VA: 0x75959bdc20
	public Void EventOnClearBtnClick() { }
	// RVA: 0x33a5e30 VA: 0x75959bde30
	public Void EventOnAssistBtnClick() { }
	// RVA: 0x33a5fd4 VA: 0x75959bdfd4
	public Void EventOnAssistClearClick() { }
	// RVA: 0x33a60ac VA: 0x75959be0ac
	public Void EventOnStartBtnClick() { }
	// RVA: 0x33a612c VA: 0x75959be12c
	public Boolean CheckCharInstSelectable(Int32 instId) { }
	// RVA: 0x33a61b8 VA: 0x75959be1b8
	public List`1 GetTempListForExclusiveInstIds() { }
	// RVA: 0x33a6220 VA: 0x75959be220
	public SquadGroupViewModel GetSquadGroupViewModel() { }
	// RVA: 0x33a62a8 VA: 0x75959be2a8
	public Boolean CheckIfCharSelectable(CharQuery charQuery) { }
	// RVA: 0x33a636c VA: 0x75959be36c
	public Void .ctor() { }
	// RVA: 0x33a646c VA: 0x75959be46c
	private Void <RegisterToDataListener>b__22_0(IStateBean stateBean) { }
	// RVA: 0x33a6628 VA: 0x75959be628
	private Void <RegisterToDataListener>b__22_1(IStateBean stateBean) { }
	// RVA: 0x33a66f4 VA: 0x75959be6f4
	private Void <_InitIfNot>b__25_0() { }
	// RVA: 0x33a677c VA: 0x75959be77c
	private Void <_InitIfNot>b__25_1(Act1LockSetSquadResponse response) { }
	// RVA: 0x33a679c VA: 0x75959be79c
	private Void <_AlertSquadInvalid>b__32_0() { }
	// RVA: 0x33a67bc VA: 0x75959be7bc
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x33a67c4 VA: 0x75959be7c4
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x33a67cc VA: 0x75959be7cc
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x33a67d4 VA: 0x75959be7d4
	private Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type P0) { }
	// RVA: 0x33a67dc VA: 0x75959be7dc
	private Dictionary`2 <>xLuaBaseProxy_RegisterFromDataListener() { }
}
```