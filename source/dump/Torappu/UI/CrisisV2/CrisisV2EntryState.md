# CrisisV2EntryState

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `RectTransform _topMenuContainer`

- `CrisisV2EntryStateBean _stateBean`

- `CrisisV2EntryMainView _mainView`

- `AnimationWrapper _animationWrapper`

- `GameObject _panelShopBtn`

- `GameObject _panelAchieveBtn`

- `GameObject _panelDailyBtn`

- `GameObject _panelMainMapBtn`

- `CrisisV2EntryAVGAdapter _avgAdapter`

- `Boolean m_hasInited`

- `CommonTopMenu m_topMenu`

- `String m_cacheMapId`

- `Boolean m_requestingCrisisData`

- `CrisisV2DataFromServer m_crisisData`


## Methods

- `Void Update()`

- `Void _TriggerCrisisV2BGM()`

- `Void _RegisterToMapState(IStateBean)`

- `Void _OnCrisisDataFetched()`

- `Void _InitIfNot()`

- `Void _EventOnBack()`

- `Void _TriggerTutorialAVG()`

- `Void _TryConsumeGuidebook(Story)`

- `Void _RegisterTutorialGo()`

- `Void OpenShopPage()`

- `Void OpenArchievePage()`

- `Void EventOnMedalClicked()`

- `Void _RegisterToMedalState(IStateBean)`

- `Void OnOpenMapState(String)`

- `Void OnMessage(Int32, ValueBundle)`

- `Void OnDestroy()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2EntryState : State, IValueMsgReceiver
{
	private const String GUIDE_BOOK_SUB_SIGNAL; // 0x0
	public const String ENTRY_ENTER_ANIM; // 0x0
	private RectTransform _topMenuContainer; // 0x50
	private CrisisV2EntryStateBean _stateBean; // 0x58
	private CrisisV2EntryMainView _mainView; // 0x60
	private AnimationWrapper _animationWrapper; // 0x68
	private GameObject _panelShopBtn; // 0x70
	private GameObject _panelAchieveBtn; // 0x78
	private GameObject _panelDailyBtn; // 0x80
	private GameObject _panelMainMapBtn; // 0x88
	private CrisisV2EntryAVGAdapter _avgAdapter; // 0x90
	private Boolean m_hasInited; // 0x98
	private CommonTopMenu m_topMenu; // 0xa0
	private String m_cacheMapId; // 0xa8
	private Boolean m_requestingCrisisData; // 0xb0
	private CrisisV2DataFromServer m_crisisData; // 0xb8
	public const Int32 PERM_MAP_CLICK; // 0x0
	public const Int32 TEMP_MAP_CLICK; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_Update; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x18
	private static DelegateBridge __Hotfix0__TriggerCrisisV2BGM; // 0x20
	private static DelegateBridge __Hotfix0__RegisterToMapState; // 0x28
	private static DelegateBridge __Hotfix0__OnCrisisDataFetched; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x38
	private static DelegateBridge __Hotfix0__EventOnBack; // 0x40
	private static DelegateBridge __Hotfix0__TriggerTutorialAVG; // 0x48
	private static DelegateBridge __Hotfix0__TryConsumeGuidebook; // 0x50
	private static DelegateBridge __Hotfix0__RegisterTutorialGo; // 0x58
	private static DelegateBridge __Hotfix0_OpenShopPage; // 0x60
	private static DelegateBridge __Hotfix0_OpenArchievePage; // 0x68
	private static DelegateBridge __Hotfix0_EventOnMedalClicked; // 0x70
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x78
	private static DelegateBridge __Hotfix0__RegisterToMedalState; // 0x80
	private static DelegateBridge __Hotfix0_OnOpenMapState; // 0x88
	private static DelegateBridge __Hotfix0_OnMessage; // 0x90
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x98
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa0


	// RVA: 0x2bd95f4 VA: 0x75951f15f4
	protected override Void OnEnter() { }
	// RVA: 0x2bd9c48 VA: 0x75951f1c48
	private Void Update() { }
	// RVA: 0x2bd9cf4 VA: 0x75951f1cf4
	protected override Void OnResume() { }
	// RVA: 0x2bda05c VA: 0x75951f205c
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2bd9af4 VA: 0x75951f1af4
	private Void _TriggerCrisisV2BGM() { }
	// RVA: 0x2bda250 VA: 0x75951f2250
	private Void _RegisterToMapState(IStateBean targetBean) { }
	// RVA: 0x2bd99ec VA: 0x75951f19ec
	private Void _OnCrisisDataFetched() { }
	// RVA: 0x2bd96f4 VA: 0x75951f16f4
	private Void _InitIfNot() { }
	// RVA: 0x2bda3f0 VA: 0x75951f23f0
	private Void _EventOnBack() { }
	// RVA: 0x2bd98ec VA: 0x75951f18ec
	private Void _TriggerTutorialAVG() { }
	// RVA: 0x2bd9f80 VA: 0x75951f1f80
	private Void _TryConsumeGuidebook(Story story) { }
	// RVA: 0x2bd9e04 VA: 0x75951f1e04
	private Void _RegisterTutorialGo() { }
	// RVA: 0x2bda4bc VA: 0x75951f24bc
	public Void OpenShopPage() { }
	// RVA: 0x2bda580 VA: 0x75951f2580
	public Void OpenArchievePage() { }
	// RVA: 0x2bda644 VA: 0x75951f2644
	public Void EventOnMedalClicked() { }
	// RVA: 0x2bda7c0 VA: 0x75951f27c0
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2bda828 VA: 0x75951f2828
	private Void _RegisterToMedalState(IStateBean stateBean) { }
	// RVA: 0x2bda93c VA: 0x75951f293c
	public Void OnOpenMapState(String mapId) { }
	// RVA: 0x2bdaaa0 VA: 0x75951f2aa0
	public Void OnMessage(Int32 type, ValueBundle value) { }
	// RVA: 0x2bdab68 VA: 0x75951f2b68
	private Void OnDestroy() { }
	// RVA: 0x2bdac14 VA: 0x75951f2c14
	public Void .ctor() { }
	// RVA: 0x2bdacc4 VA: 0x75951f2cc4
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2bdaccc VA: 0x75951f2ccc
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2bdacd4 VA: 0x75951f2cd4
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```