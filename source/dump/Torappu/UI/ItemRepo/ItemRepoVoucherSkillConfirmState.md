# ItemRepoVoucherSkillConfirmState

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `ItemRepoVoucherSkillConfirmView _view`

- `ItemRepoVoucherSkillStateBean _stateBean`

- `RectTransform _btnExit`


## Methods

- `Void _OnBackOrCancel()`

- `Void _OnConfirmUpgrade()`

- `Void <_OnConfirmUpgrade>b__7_0(UpgradeSpecializedSkillUseItemResponse)`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoVoucherSkillConfirmState : PopupFloatState
{
	private ItemRepoVoucherSkillConfirmView _view; // 0x70
	private ItemRepoVoucherSkillStateBean _stateBean; // 0x78
	private RectTransform _btnExit; // 0x80
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnResume; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0__OnBackOrCancel; // 0x18
	private static DelegateBridge __Hotfix0__OnConfirmUpgrade; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2d270b4 VA: 0x759533f0b4
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2d2711c VA: 0x759533f11c
	protected override Void OnResume() { }
	// RVA: 0x2d274e0 VA: 0x759533f4e0
	protected override Void OnEnter() { }
	// RVA: 0x2d276d0 VA: 0x759533f6d0
	private Void _OnBackOrCancel() { }
	// RVA: 0x2d277e4 VA: 0x759533f7e4
	private Void _OnConfirmUpgrade() { }
	// RVA: 0x2d27a84 VA: 0x759533fa84
	public Void .ctor() { }
	// RVA: 0x2d27af4 VA: 0x759533faf4
	private Void <_OnConfirmUpgrade>b__7_0(UpgradeSpecializedSkillUseItemResponse response) { }
	// RVA: 0x2d27df4 VA: 0x759533fdf4
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2d27dfc VA: 0x759533fdfc
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```