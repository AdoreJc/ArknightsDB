# ActMultiV3SquadHomeState

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `ActMultiV3SquadHomeView _view`

- `ActMultiV3CharSelectCharItemView _charSelectItemView`

- `UICommonTrackPoint _trackPoint`

- `RectTransform _topMenuContainer`

- `Boolean m_hasInited`

- `CommonTopMenu m_topMenu`

- `ActMultiV3SquadHomeStateBean m_stateBean`

- `InputParam m_cacheCharSelectInput`

- `String m_cacheActId`

- `ActMultiV3MapModeType m_cacheModeType`


## Methods

- `Void _RegisterFromCharSelectState(IStateBean)`

- `Void _TryPlayCharVoice(TemplateCharSelectMainViewModel)`

- `Void _RegisterFromEffectSelectState(IStateBean)`

- `Void _RegisterToEffectSelectState(IStateBean)`

- `Void _RegisterToCharSelectState(IStateBean)`

- `CommonCharSelectCustomization _GenCharSelectCustom()`

- `TemplateCharSelectCardViewModel _CreateCharSelectCard(Int32, TemplateCharSelectCharInputData, PlayerCharacter)`

- `Void _UpdateSquadEffectTrackPoint()`

- `Void _InitIfNot()`

- `Void _OnRoutedToOtherPage(UIRouteTarget, Object, Action`2)`

- `Void _EventOnBtnBack()`

- `Void _SaveCurrSquadIdToLocalCache()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _EventOnCharItemClick(Object)`

- `Void _NavToCharSelectState(ActMultiV3IdentityType, Boolean, Boolean, String)`

- `InputParam _ParseCharSelectInput(ActMultiV3IdentityType, Boolean, Boolean, String)`

- `Void _NavToEffectSelectState()`

- `Void _EventOnTeamFull(InputParam)`

- `Void _EventOnSquadSelect(String)`

- `Void _SelectSquadTab(String)`

- `Void _SaveSquadIfNeed(Action)`

- `Void EventOnBtnHighPriEditClick()`

- `Void EventOnBtnLowPriEditClick()`

- `Void EventOnBtnEffectEditClick()`

- `Void <_EventOnBtnBack>b__29_0()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3SquadHomeState : State, IValueMsgReceiver
{
	public const Int32 MSG_SQUAD_SELECT; // 0x0
	public const Int32 MSG_CHAR_ITEM_CLICK; // 0x0
	private ActMultiV3SquadHomeView _view; // 0x50
	private ActMultiV3CharSelectCharItemView _charSelectItemView; // 0x58
	private UICommonTrackPoint _trackPoint; // 0x60
	private RectTransform _topMenuContainer; // 0x68
	private Boolean m_hasInited; // 0x70
	private CommonTopMenu m_topMenu; // 0x78
	private ActMultiV3SquadHomeStateBean m_stateBean; // 0x80
	private InputParam m_cacheCharSelectInput; // 0x88
	private List`1 m_cachePreferSlotList; // 0x90
	private List`1 m_cacheBackupSlotList; // 0x98
	private String m_cacheActId; // 0xa0
	private ActMultiV3MapModeType m_cacheModeType; // 0xa8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x8
	private static DelegateBridge __Hotfix0_RegisterFromDataListener; // 0x10
	private static DelegateBridge __Hotfix0__RegisterFromCharSelectState; // 0x18
	private static DelegateBridge __Hotfix0__TryPlayCharVoice; // 0x20
	private static DelegateBridge __Hotfix0__RegisterFromEffectSelectState; // 0x28
	private static DelegateBridge __Hotfix0__RegisterToEffectSelectState; // 0x30
	private static DelegateBridge __Hotfix0__RegisterToCharSelectState; // 0x38
	private static DelegateBridge __Hotfix0__GenCharSelectCustom; // 0x40
	private static DelegateBridge __Hotfix0__CreateCharSelectCard; // 0x48
	private static DelegateBridge __Hotfix0_OnEnter; // 0x50
	private static DelegateBridge __Hotfix0_OnResume; // 0x58
	private static DelegateBridge __Hotfix0__UpdateSquadEffectTrackPoint; // 0x60
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x68
	private static DelegateBridge __Hotfix0__OnRoutedToOtherPage; // 0x70
	private static DelegateBridge __Hotfix0__EventOnBtnBack; // 0x78
	private static DelegateBridge __Hotfix0__SaveCurrSquadIdToLocalCache; // 0x80
	private static DelegateBridge __Hotfix0_OnMessage; // 0x88
	private static DelegateBridge __Hotfix0__EventOnCharItemClick; // 0x90
	private static DelegateBridge __Hotfix0__NavToCharSelectState; // 0x98
	private static DelegateBridge __Hotfix0__ParseCharSelectInput; // 0xa0
	private static DelegateBridge __Hotfix0__NavToEffectSelectState; // 0xa8
	private static DelegateBridge __Hotfix0__EventOnTeamFull; // 0xb0
	private static DelegateBridge __Hotfix0__EventOnSquadSelect; // 0xb8
	private static DelegateBridge __Hotfix0__SelectSquadTab; // 0xc0
	private static DelegateBridge __Hotfix0__SaveSquadIfNeed; // 0xc8
	private static DelegateBridge __Hotfix0_EventOnBtnHighPriEditClick; // 0xd0
	private static DelegateBridge __Hotfix0_EventOnBtnLowPriEditClick; // 0xd8
	private static DelegateBridge __Hotfix0_EventOnBtnEffectEditClick; // 0xe0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xe8


	// RVA: 0x313bdf8 VA: 0x7595753df8
	public override IStateBean GetCacheBean() { }
	// RVA: 0x313be60 VA: 0x7595753e60
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x313c054 VA: 0x7595754054
	public override Dictionary`2 RegisterFromDataListener() { }
	// RVA: 0x313c248 VA: 0x7595754248
	private Void _RegisterFromCharSelectState(IStateBean stateBean) { }
	// RVA: 0x313c960 VA: 0x7595754960
	private Void _TryPlayCharVoice(TemplateCharSelectMainViewModel charSelectModel) { }
	// RVA: 0x313cd10 VA: 0x7595754d10
	private Void _RegisterFromEffectSelectState(IStateBean stateBean) { }
	// RVA: 0x313cfe8 VA: 0x7595754fe8
	private Void _RegisterToEffectSelectState(IStateBean stateBean) { }
	// RVA: 0x313d0c8 VA: 0x75957550c8
	private Void _RegisterToCharSelectState(IStateBean stateBean) { }
	// RVA: 0x313d1c8 VA: 0x75957551c8
	private CommonCharSelectCustomization _GenCharSelectCustom() { }
	// RVA: 0x313d31c VA: 0x759575531c
	private TemplateCharSelectCardViewModel _CreateCharSelectCard(Int32 instId, TemplateCharSelectCharInputData inputNullable, PlayerCharacter playerData) { }
	// RVA: 0x313d6dc VA: 0x75957556dc
	protected override Void OnEnter() { }
	// RVA: 0x313de48 VA: 0x7595755e48
	protected override Void OnResume() { }
	// RVA: 0x313dd3c VA: 0x7595755d3c
	private Void _UpdateSquadEffectTrackPoint() { }
	// RVA: 0x313d874 VA: 0x7595755874
	private Void _InitIfNot() { }
	// RVA: 0x313dfac VA: 0x7595755fac
	private Void _OnRoutedToOtherPage(UIRouteTarget target, Object param, Action`2 baseHandler) { }
	// RVA: 0x313e4cc VA: 0x75957564cc
	private Void _EventOnBtnBack() { }
	// RVA: 0x313e584 VA: 0x7595756584
	private Void _SaveCurrSquadIdToLocalCache() { }
	// RVA: 0x313e6cc VA: 0x75957566cc
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x313e934 VA: 0x7595756934
	private Void _EventOnCharItemClick(Object objVal) { }
	// RVA: 0x313ea38 VA: 0x7595756a38
	private Void _NavToCharSelectState(ActMultiV3IdentityType idType, Boolean isSingle, Boolean needScroll, String charId) { }
	// RVA: 0x313ec14 VA: 0x7595756c14
	private InputParam _ParseCharSelectInput(ActMultiV3IdentityType idType, Boolean isSingle, Boolean needScroll, String targetCharId) { }
	// RVA: 0x313f50c VA: 0x759575750c
	private Void _NavToEffectSelectState() { }
	// RVA: 0x313f6d8 VA: 0x75957576d8
	private Void _EventOnTeamFull(InputParam input) { }
	// RVA: 0x313e798 VA: 0x7595756798
	private Void _EventOnSquadSelect(String squadId) { }
	// RVA: 0x313f8dc VA: 0x75957578dc
	private Void _SelectSquadTab(String squadId) { }
	// RVA: 0x313e0fc VA: 0x75957560fc
	private Void _SaveSquadIfNeed(Action nextStep) { }
	// RVA: 0x313fd0c VA: 0x7595757d0c
	public Void EventOnBtnHighPriEditClick() { }
	// RVA: 0x313fd84 VA: 0x7595757d84
	public Void EventOnBtnLowPriEditClick() { }
	// RVA: 0x313fdfc VA: 0x7595757dfc
	public Void EventOnBtnEffectEditClick() { }
	// RVA: 0x313feb4 VA: 0x7595757eb4
	public Void .ctor() { }
	// RVA: 0x31400d0 VA: 0x75957580d0
	private Void <_EventOnBtnBack>b__29_0() { }
	// RVA: 0x314016c VA: 0x759575816c
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x3140174 VA: 0x7595758174
	private Dictionary`2 <>xLuaBaseProxy_RegisterFromDataListener() { }
	// RVA: 0x314017c VA: 0x759575817c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x3140184 VA: 0x7595758184
	private Void <>xLuaBaseProxy_OnResume() { }
}
```