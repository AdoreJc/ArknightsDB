# CharacterInfoPotentialState

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `CharacterInfoPotentialView _view`

- `CharacterInfoPotentialNotifyView _potentialNotifyPrefab`

- `TopMenuDynamicPrefabInstHolder _topMenuHolder`

- `AnimationWrapper _animationWrapper`

- `CharacterInfoPotentialStateBean m_stateBean`

- `Boolean m_hasInited`


## Methods

- `Void _OnJumpToPotentialFullState(IStateBean)`

- `Void OnCancelClick()`

- `Void OnItemClick(String)`

- `Void OnVoucherClick(String)`

- `Void _RefreshDataAfterLvlUp()`

- `Void _ShowPotentialNotify(Boolean)`

- `Void _InitIfNot()`

- `Void _OnInitTopMenu(GameObject)`

- `Void _ItemRequest(String)`

- `Void <OnVoucherClick>b__14_0(UseFullPotentialItemResponse)`

- `Void <_OnInitTopMenu>b__18_0()`

- `Void <_ItemRequest>b__19_0(BoostPotentialResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoPotentialState : State
{
	private const String ANIM_ENTER; // 0x0
	private CharacterInfoPotentialView _view; // 0x50
	private CharacterInfoPotentialNotifyView _potentialNotifyPrefab; // 0x58
	private TopMenuDynamicPrefabInstHolder _topMenuHolder; // 0x60
	private AnimationWrapper _animationWrapper; // 0x68
	private CharacterInfoPotentialStateBean m_stateBean; // 0x70
	private Boolean m_hasInited; // 0x78
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_OnResume; // 0x18
	private static DelegateBridge __Hotfix0__OnJumpToPotentialFullState; // 0x20
	private static DelegateBridge __Hotfix0_OnCancelClick; // 0x28
	private static DelegateBridge __Hotfix0_OnItemClick; // 0x30
	private static DelegateBridge __Hotfix0_OnVoucherClick; // 0x38
	private static DelegateBridge __Hotfix0__RefreshDataAfterLvlUp; // 0x40
	private static DelegateBridge __Hotfix0__ShowPotentialNotify; // 0x48
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x50
	private static DelegateBridge __Hotfix0__OnInitTopMenu; // 0x58
	private static DelegateBridge __Hotfix0__ItemRequest; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68


	// RVA: 0x2d462d4 VA: 0x759535e2d4
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2d4633c VA: 0x759535e33c
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2d464b4 VA: 0x759535e4b4
	protected override Void OnEnter() { }
	// RVA: 0x2d469b4 VA: 0x759535e9b4
	protected override Void OnResume() { }
	// RVA: 0x2d46acc VA: 0x759535eacc
	private Void _OnJumpToPotentialFullState(IStateBean stateBean) { }
	// RVA: 0x2d46bd8 VA: 0x759535ebd8
	public Void OnCancelClick() { }
	// RVA: 0x2d46c54 VA: 0x759535ec54
	public Void OnItemClick(String itemId) { }
	// RVA: 0x2d47294 VA: 0x759535f294
	public Void OnVoucherClick(String itemId) { }
	// RVA: 0x2d474e4 VA: 0x759535f4e4
	private Void _RefreshDataAfterLvlUp() { }
	// RVA: 0x2d477c0 VA: 0x759535f7c0
	private Void _ShowPotentialNotify(Boolean isSuc) { }
	// RVA: 0x2d46620 VA: 0x759535e620
	private Void _InitIfNot() { }
	// RVA: 0x2d47898 VA: 0x759535f898
	private Void _OnInitTopMenu(GameObject inst) { }
	// RVA: 0x2d4707c VA: 0x759535f07c
	private Void _ItemRequest(String itemId) { }
	// RVA: 0x2d479e0 VA: 0x759535f9e0
	public Void .ctor() { }
	// RVA: 0x2d47b38 VA: 0x759535fb38
	private Void <OnVoucherClick>b__14_0(UseFullPotentialItemResponse response) { }
	// RVA: 0x2d47bc8 VA: 0x759535fbc8
	private Void <_OnInitTopMenu>b__18_0() { }
	// RVA: 0x2d47be8 VA: 0x759535fbe8
	private Void <_ItemRequest>b__19_0(BoostPotentialResponse response) { }
	// RVA: 0x2d47c90 VA: 0x759535fc90
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x2d47c98 VA: 0x759535fc98
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2d47ca0 VA: 0x759535fca0
	private Void <>xLuaBaseProxy_OnResume() { }
}
```