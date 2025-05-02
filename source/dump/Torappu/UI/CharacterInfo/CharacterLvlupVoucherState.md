# CharacterLvlupVoucherState

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `TopMenuDynamicPrefabInstHolder _topMenuHolder`

- `CharacterLvlupVoucherStateBean _stateBean`

- `CharacterLvlupVoucherView _voucherView`

- `CharacterInfoLevelUpNotifyView _levelUpNotify`

- `CharacterInfoTalentUnlockNotifyView _talentUnlockNotify`

- `CharacterInfoSkillUnlockNotifyView _skillUnlockNotify`

- `CharacterInfoBuildingBuffUnlockNotifyView _buildingBuffUnlockNotify`

- `CharacterInfoBuildingBuffUpgradeNotifyView _buildingBuffUpgradeNotify`

- `Boolean m_isInited`

- `Param m_param`


## Methods

- `Void _OnJumpToMaxState(IStateBean)`

- `Void _InitIfNot()`

- `Void _OnInitTopMenu(GameObject)`

- `IEnumerator _TryOpenLevelMaxState()`

- `Void OnCloseBtnClicked()`

- `Void OnConfirmBtnClicked()`

- `Void <_OnInitTopMenu>b__16_0()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterLvlupVoucherState : State
{
	private TopMenuDynamicPrefabInstHolder _topMenuHolder; // 0x50
	private CharacterLvlupVoucherStateBean _stateBean; // 0x58
	private CharacterLvlupVoucherView _voucherView; // 0x60
	private CharacterInfoLevelUpNotifyView _levelUpNotify; // 0x68
	private CharacterInfoTalentUnlockNotifyView _talentUnlockNotify; // 0x70
	private CharacterInfoSkillUnlockNotifyView _skillUnlockNotify; // 0x78
	private CharacterInfoBuildingBuffUnlockNotifyView _buildingBuffUnlockNotify; // 0x80
	private CharacterInfoBuildingBuffUpgradeNotifyView _buildingBuffUpgradeNotify; // 0x88
	private Boolean m_isInited; // 0x90
	private Param m_param; // 0x98
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x18
	private static DelegateBridge __Hotfix0__OnJumpToMaxState; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0__OnInitTopMenu; // 0x30
	private static DelegateBridge __Hotfix0__TryOpenLevelMaxState; // 0x38
	private static DelegateBridge __Hotfix0_OnCloseBtnClicked; // 0x40
	private static DelegateBridge __Hotfix0_OnConfirmBtnClicked; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x2d4f708 VA: 0x7595367708
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2d4f770 VA: 0x7595367770
	protected override Void OnEnter() { }
	// RVA: 0x2d4f960 VA: 0x7595367960
	protected override Void OnResume() { }
	// RVA: 0x2d4fa00 VA: 0x7595367a00
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2d4fb78 VA: 0x7595367b78
	private Void _OnJumpToMaxState(IStateBean stateBean) { }
	// RVA: 0x2d4f850 VA: 0x7595367850
	private Void _InitIfNot() { }
	// RVA: 0x2d4fcb0 VA: 0x7595367cb0
	private Void _OnInitTopMenu(GameObject inst) { }
	// RVA: 0x2d4fdf8 VA: 0x7595367df8
	private IEnumerator _TryOpenLevelMaxState() { }
	// RVA: 0x2d4fecc VA: 0x7595367ecc
	public Void OnCloseBtnClicked() { }
	// RVA: 0x2d4ffdc VA: 0x7595367fdc
	public Void OnConfirmBtnClicked() { }
	// RVA: 0x2d50384 VA: 0x7595368384
	public Void .ctor() { }
	// RVA: 0x2d503f4 VA: 0x75953683f4
	private Void <_OnInitTopMenu>b__16_0() { }
	// RVA: 0x2d50414 VA: 0x7595368414
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2d5041c VA: 0x759536841c
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2d50424 VA: 0x7595368424
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```