# RoguelikeSquadState

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Boolean m_inited`

- `Input m_cacheInput`

- `RoguelikeSquadStateBean m_squadStateBean`

- `RoguelikeSquadView _squadView`

- `Animator _deleteState`

- `GameObject _startBattleButton`

- `RectTransform _panelTopMenu`

- `UIGuidebookTrigger _guideBookTrigger`

- `RoguelikeCommonTopMenu m_topMenu`

- `RoguelikeMenuAdapter m_menuAdapter`

- `Boolean m_deleteFlag`


## Methods

- `Void OnSelectEmptyPos(Int32)`

- `Void OnSelectSkill(Int32, String)`

- `Void OnSelectExistChar(Int32)`

- `Void OnChangeAllChar()`

- `Void OnClearOnSelect()`

- `Void EventOnBackClicked()`

- `Void _EventOnStartBattle()`

- `Void EventOnStartBattleClicked()`

- `Void EventOnClearBtnClick()`

- `Void EventOnMultiFormatClick()`

- `Void _InitIfNot()`

- `Void _StartBattle()`

- `Boolean _EnsureSpChar(RoguelikeCharCardViewModel, List`1)`

- `Void DealWithFromStateBean(IStateBean)`

- `Void <_EventOnStartBattle>b__26_0()`

- `Void <_InitIfNot>b__31_0()`

- `Void <_InitIfNot>b__31_1()`

- `Void <RegisterToDataListener>b__33_0(IStateBean)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeSquadState : PopupFadeState
{
	private Boolean m_inited; // 0x70
	private Input m_cacheInput; // 0x78
	private RoguelikeSquadStateBean m_squadStateBean; // 0x80
	private const Int32 CACHE_CONST_MAX; // 0x0
	private const String ANIMATORPARAM; // 0x0
	private RoguelikeSquadView _squadView; // 0x88
	private Animator _deleteState; // 0x90
	private GameObject _startBattleButton; // 0x98
	private RectTransform _panelTopMenu; // 0xa0
	private UIGuidebookTrigger _guideBookTrigger; // 0xa8
	private RoguelikeCommonTopMenu m_topMenu; // 0xb0
	private RoguelikeMenuAdapter m_menuAdapter; // 0xb8
	private List`1 m_pluginContexts; // 0xc0
	private Boolean m_deleteFlag; // 0xc8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_LoadAllCharList; // 0x10
	private static DelegateBridge __Hotfix0_OnSelectEmptyPos; // 0x18
	private static DelegateBridge __Hotfix0_OnSelectSkill; // 0x20
	private static DelegateBridge __Hotfix0_OnSelectExistChar; // 0x28
	private static DelegateBridge __Hotfix0_OnChangeAllChar; // 0x30
	private static DelegateBridge __Hotfix0_OnClearOnSelect; // 0x38
	private static DelegateBridge __Hotfix0_EventOnBackClicked; // 0x40
	private static DelegateBridge __Hotfix0__EventOnStartBattle; // 0x48
	private static DelegateBridge __Hotfix0_EventOnStartBattleClicked; // 0x50
	private static DelegateBridge __Hotfix0_EventOnClearBtnClick; // 0x58
	private static DelegateBridge __Hotfix0_EventOnMultiFormatClick; // 0x60
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x68
	private static DelegateBridge __Hotfix0__StartBattle; // 0x70
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x78
	private static DelegateBridge __Hotfix0__EnsureSpChar; // 0x80
	private static DelegateBridge __Hotfix0_DealWithFromStateBean; // 0x88
	private static DelegateBridge __Hotfix0_UseEarlyFromDataListener; // 0x90
	private static DelegateBridge __Hotfix0_RegisterFromDataListener; // 0x98
	private static DelegateBridge __Hotfix0__PlaySquadVoice; // 0xa0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa8


	// RVA: 0x2af28f8 VA: 0x759510a8f8
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2af2960 VA: 0x759510a960
	protected override Void OnEnter() { }
	// RVA: 0x2af359c VA: 0x759510b59c
	public List`1 LoadAllCharList() { }
	// RVA: 0x2af3cfc VA: 0x759510bcfc
	public Void OnSelectEmptyPos(Int32 index) { }
	// RVA: 0x2af4080 VA: 0x759510c080
	public Void OnSelectSkill(Int32 instId, String skillId) { }
	// RVA: 0x2af42cc VA: 0x759510c2cc
	public Void OnSelectExistChar(Int32 instId) { }
	// RVA: 0x2af46e0 VA: 0x759510c6e0
	public Void OnChangeAllChar() { }
	// RVA: 0x2af4a40 VA: 0x759510ca40
	public Void OnClearOnSelect() { }
	// RVA: 0x2af4b44 VA: 0x759510cb44
	public Void EventOnBackClicked() { }
	// RVA: 0x2af4bb0 VA: 0x759510cbb0
	private Void _EventOnStartBattle() { }
	// RVA: 0x2af5744 VA: 0x759510d744
	public Void EventOnStartBattleClicked() { }
	// RVA: 0x2af5bd4 VA: 0x759510dbd4
	public Void EventOnClearBtnClick() { }
	// RVA: 0x2af5de4 VA: 0x759510dde4
	public Void EventOnMultiFormatClick() { }
	// RVA: 0x2af2cb0 VA: 0x759510acb0
	private Void _InitIfNot() { }
	// RVA: 0x2af4d74 VA: 0x759510cd74
	private Void _StartBattle() { }
	// RVA: 0x2af6084 VA: 0x759510e084
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2af61fc VA: 0x759510e1fc
	private Boolean _EnsureSpChar(RoguelikeCharCardViewModel insertChar, List`1 squadList) { }
	// RVA: 0x2af6374 VA: 0x759510e374
	public Void DealWithFromStateBean(IStateBean stateBean) { }
	// RVA: 0x2af6d88 VA: 0x759510ed88
	public override Boolean UseEarlyFromDataListener(Type fromState) { }
	// RVA: 0x2af6e00 VA: 0x759510ee00
	public override Dictionary`2 RegisterFromDataListener() { }
	// RVA: 0x2af6abc VA: 0x759510eabc
	private static Void _PlaySquadVoice(List`1 prevSquad, List`1 newSquad) { }
	// RVA: 0x2af284c VA: 0x759510a84c
	public Void .ctor() { }
	// RVA: 0x2af7160 VA: 0x759510f160
	private Void <_EventOnStartBattle>b__26_0() { }
	// RVA: 0x2af7164 VA: 0x759510f164
	private Void <_InitIfNot>b__31_0() { }
	// RVA: 0x2af7174 VA: 0x759510f174
	private Void <_InitIfNot>b__31_1() { }
	// RVA: 0x2af71f8 VA: 0x759510f1f8
	private Void <RegisterToDataListener>b__33_0(IStateBean stateBean) { }
	// RVA: 0x2af7288 VA: 0x759510f288
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2af7290 VA: 0x759510f290
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x2af7298 VA: 0x759510f298
	private Boolean <>xLuaBaseProxy_UseEarlyFromDataListener(Type P0) { }
	// RVA: 0x2af72a0 VA: 0x759510f2a0
	private Dictionary`2 <>xLuaBaseProxy_RegisterFromDataListener() { }
}
```