# ItemRepoRenameState

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `ItemRepoItemDetailStateBean _stateBean`

- `ItemRepoUseChangeNameCard _changeNameCard`


## Methods

- `Void DismissToHome()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoRenameState : PopupFloatState
{
	private ItemRepoItemDetailStateBean _stateBean; // 0x70
	private ItemRepoUseChangeNameCard _changeNameCard; // 0x78
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_DismissToHome; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2d23a8c VA: 0x759533ba8c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2d23af4 VA: 0x759533baf4
	protected override Void OnEnter() { }
	// RVA: 0x2d23c68 VA: 0x759533bc68
	public Void DismissToHome() { }
	// RVA: 0x2d23d74 VA: 0x759533bd74
	public Void .ctor() { }
	// RVA: 0x2d23de4 VA: 0x759533bde4
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```