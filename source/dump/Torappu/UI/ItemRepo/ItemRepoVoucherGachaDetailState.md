# ItemRepoVoucherGachaDetailState

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `ItemRepoItemDetailStateBean _stateBean`

- `Transform _container`

- `RecruitGachaPoolDetailHolder m_holder`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoVoucherGachaDetailState : PopupFloatState
{
	private ItemRepoItemDetailStateBean _stateBean; // 0x70
	private Transform _container; // 0x78
	private RecruitGachaPoolDetailHolder m_holder; // 0x80
	private Boolean m_isInited; // 0x88
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2d24ce8 VA: 0x759533cce8
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2d24d50 VA: 0x759533cd50
	private Void _InitIfNot() { }
	// RVA: 0x2d24f34 VA: 0x759533cf34
	protected override Void OnEnter() { }
	// RVA: 0x2d24fe0 VA: 0x759533cfe0
	public Void .ctor() { }
	// RVA: 0x2d25050 VA: 0x759533d050
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```