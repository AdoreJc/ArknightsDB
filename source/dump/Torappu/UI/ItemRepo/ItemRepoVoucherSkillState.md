# ItemRepoVoucherSkillState

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `ItemRepoVoucherSkillView _view`

- `ItemRepoVoucherSkillStateBean _stateBean`

- `RectTransform _btnExit`


## Methods

- `Void _OnChooseSkill(Int32)`

- `Void _OnBackOrCancel()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoVoucherSkillState : PopupFloatState
{
	private ItemRepoVoucherSkillView _view; // 0x70
	private ItemRepoVoucherSkillStateBean _stateBean; // 0x78
	private RectTransform _btnExit; // 0x80
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnResume; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0__OnChooseSkill; // 0x18
	private static DelegateBridge __Hotfix0__OnBackOrCancel; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2d27f24 VA: 0x759533ff24
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2d27f8c VA: 0x759533ff8c
	protected override Void OnResume() { }
	// RVA: 0x2d28008 VA: 0x7595340008
	protected override Void OnEnter() { }
	// RVA: 0x2d28330 VA: 0x7595340330
	private Void _OnChooseSkill(Int32 selectedIdx) { }
	// RVA: 0x2d284e0 VA: 0x75953404e0
	private Void _OnBackOrCancel() { }
	// RVA: 0x2d285f4 VA: 0x75953405f4
	public Void .ctor() { }
	// RVA: 0x2d28664 VA: 0x7595340664
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2d2866c VA: 0x759534066c
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```