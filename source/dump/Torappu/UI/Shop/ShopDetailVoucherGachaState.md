# ShopDetailVoucherGachaState

**Namespace:** `Torappu.UI.Shop`


## Fields

- `ShopDetailVoucherGachaStateBean m_stateBean`

- `Transform _container`

- `Boolean m_isInited`

- `RecruitGachaPoolDetailHolder m_holder`


## Methods

- `Void _InitIfNot()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopDetailVoucherGachaState : PopupFloatState
{
	private ShopDetailVoucherGachaStateBean m_stateBean; // 0x70
	private Transform _container; // 0x78
	private Boolean m_isInited; // 0x80
	private RecruitGachaPoolDetailHolder m_holder; // 0x88
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x243ca58 VA: 0x7594a54a58
	public override IStateBean GetCacheBean() { }
	// RVA: 0x243cac0 VA: 0x7594a54ac0
	private Void _InitIfNot() { }
	// RVA: 0x243cbe0 VA: 0x7594a54be0
	protected override Void OnEnter() { }
	// RVA: 0x243cc98 VA: 0x7594a54c98
	public Void .ctor() { }
	// RVA: 0x243cd44 VA: 0x7594a54d44
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```