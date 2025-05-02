# CharacterLvlupHomeState

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `TopMenuDynamicPrefabInstHolder _topMenuHolder`

- `CharacterLvlupHomeView _lvlupView`

- `CharacterInfoLevelUpNotifyView _levelUpNotify`

- `CharacterInfoTalentUnlockNotifyView _talentUnlockNotify`

- `CharacterInfoSkillUnlockNotifyView _skillUnlockNotify`

- `CharacterInfoBuildingBuffUnlockNotifyView _buildingBuffUnlockNotify`

- `CharacterInfoBuildingBuffUpgradeNotifyView _buildingBuffUpgradeNotify`

- `CharacterLvlupHomeStateBean _stateBean`

- `AnimationWrapper _animationWrapper`

- `Boolean m_isInited`


## Methods

- `Void EventOnClearBtnClick()`

- `Void EventOnUpgradeBtnClick()`

- `Void EventOnScrollResetBtnClick()`

- `Void EventOnScrollCancelBtnClick()`

- `Void EventOnScrollConfirmBtnClick()`

- `Void _InitIfNot()`

- `Void _OnInitTopMenu(GameObject)`

- `Void _OnModifyingExpCardNum(Int32, Int32)`

- `Void _OnWheelBeginDrag()`

- `Void _OnWheelScrollEnd(Int32)`

- `Void _OnWheelClicked(Int32)`

- `Void _OnMoveToMaxValidLevel()`

- `Void _OnJumpToMaxState(IStateBean)`

- `Boolean _CheckIfExpAndGoldEnough()`

- `Void <_OnInitTopMenu>b__22_0()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterLvlupHomeState : State
{
	private const Single TOAST_DELTA; // 0x0
	private const String ANIM_ENTER; // 0x0
	private TopMenuDynamicPrefabInstHolder _topMenuHolder; // 0x50
	private CharacterLvlupHomeView _lvlupView; // 0x58
	private CharacterInfoLevelUpNotifyView _levelUpNotify; // 0x60
	private CharacterInfoTalentUnlockNotifyView _talentUnlockNotify; // 0x68
	private CharacterInfoSkillUnlockNotifyView _skillUnlockNotify; // 0x70
	private CharacterInfoBuildingBuffUnlockNotifyView _buildingBuffUnlockNotify; // 0x78
	private CharacterInfoBuildingBuffUpgradeNotifyView _buildingBuffUpgradeNotify; // 0x80
	private CharacterLvlupHomeStateBean _stateBean; // 0x88
	private AnimationWrapper _animationWrapper; // 0x90
	private Boolean m_isInited; // 0x98
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x18
	private static DelegateBridge __Hotfix0_EventOnClearBtnClick; // 0x20
	private static DelegateBridge __Hotfix0_EventOnUpgradeBtnClick; // 0x28
	private static DelegateBridge __Hotfix0_EventOnScrollResetBtnClick; // 0x30
	private static DelegateBridge __Hotfix0_EventOnScrollCancelBtnClick; // 0x38
	private static DelegateBridge __Hotfix0_EventOnScrollConfirmBtnClick; // 0x40
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x48
	private static DelegateBridge __Hotfix0__OnInitTopMenu; // 0x50
	private static DelegateBridge __Hotfix0__OnModifyingExpCardNum; // 0x58
	private static DelegateBridge __Hotfix0__OnWheelBeginDrag; // 0x60
	private static DelegateBridge __Hotfix0__OnWheelScrollEnd; // 0x68
	private static DelegateBridge __Hotfix0__OnWheelClicked; // 0x70
	private static DelegateBridge __Hotfix0__OnMoveToMaxValidLevel; // 0x78
	private static DelegateBridge __Hotfix0__OnJumpToMaxState; // 0x80
	private static DelegateBridge __Hotfix0__CheckIfExpAndGoldEnough; // 0x88
	private static DelegateBridge __Hotfix0__ParseUpgradeCharRequest; // 0x90
	private static DelegateBridge __Hotfix0_ShowLevelUpToasts; // 0x98
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa0


	// RVA: 0x2d4c5d8 VA: 0x75953645d8
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2d4c640 VA: 0x7595364640
	protected override Void OnEnter() { }
	// RVA: 0x2d4ca50 VA: 0x7595364a50
	protected override Void OnResume() { }
	// RVA: 0x2d4cb30 VA: 0x7595364b30
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2d4cca8 VA: 0x7595364ca8
	public Void EventOnClearBtnClick() { }
	// RVA: 0x2d4cd1c VA: 0x7595364d1c
	public Void EventOnUpgradeBtnClick() { }
	// RVA: 0x2d4d2d4 VA: 0x75953652d4
	public Void EventOnScrollResetBtnClick() { }
	// RVA: 0x2d4d348 VA: 0x7595365348
	public Void EventOnScrollCancelBtnClick() { }
	// RVA: 0x2d4d3c0 VA: 0x75953653c0
	public Void EventOnScrollConfirmBtnClick() { }
	// RVA: 0x2d4c778 VA: 0x7595364778
	private Void _InitIfNot() { }
	// RVA: 0x2d4d450 VA: 0x7595365450
	private Void _OnInitTopMenu(GameObject inst) { }
	// RVA: 0x2d4d598 VA: 0x7595365598
	private Void _OnModifyingExpCardNum(Int32 index, Int32 deltaNum) { }
	// RVA: 0x2d4d630 VA: 0x7595365630
	private Void _OnWheelBeginDrag() { }
	// RVA: 0x2d4d6a8 VA: 0x75953656a8
	private Void _OnWheelScrollEnd(Int32 index) { }
	// RVA: 0x2d4d734 VA: 0x7595365734
	private Void _OnWheelClicked(Int32 index) { }
	// RVA: 0x2d4d7c0 VA: 0x75953657c0
	private Void _OnMoveToMaxValidLevel() { }
	// RVA: 0x2d4d834 VA: 0x7595365834
	private Void _OnJumpToMaxState(IStateBean stateBean) { }
	// RVA: 0x2d4d000 VA: 0x7595365000
	private Boolean _CheckIfExpAndGoldEnough() { }
	// RVA: 0x2d4d120 VA: 0x7595365120
	private static UpgradeCharRequest _ParseUpgradeCharRequest(Int32 charInstId, List`1 selectedItems) { }
	// RVA: 0x2d4d96c VA: 0x759536596c
	public static Void ShowLevelUpToasts(CharQuery charQuery, List`1 equipQueries, EvolvePhase evolve, Int32 potentialRank, Int32 mainSkillLvl, Int32 fromLevel, Int32 toLevel, LevelUpToastPrefabConfig prefabConfig) { }
	// RVA: 0x2d4e2b4 VA: 0x75953662b4
	public Void .ctor() { }
	// RVA: 0x2d4e324 VA: 0x7595366324
	private Void <_OnInitTopMenu>b__22_0() { }
	// RVA: 0x2d4e344 VA: 0x7595366344
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2d4e34c VA: 0x759536634c
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2d4e354 VA: 0x7595366354
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```