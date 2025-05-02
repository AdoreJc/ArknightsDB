# ActCommonReplicateState

**Namespace:** `Torappu.Activity`


## Fields

- `ActCommonReplicateView _view`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void ToShopPage()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity
public class ActCommonReplicateState : PopupFloatState
{
	private ActCommonReplicateView _view; // 0x70
	private Boolean m_isInited; // 0x78
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x10
	private static DelegateBridge __Hotfix0_ToShopPage; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x30c82a8 VA: 0x75956e02a8
	private Void _InitIfNot() { }
	// RVA: 0x30c83a8 VA: 0x75956e03a8
	protected override Void OnEnter() { }
	// RVA: 0x30c8594 VA: 0x75956e0594
	public override IStateBean GetCacheBean() { }
	// RVA: 0x30c85f8 VA: 0x75956e05f8
	public Void ToShopPage() { }
	// RVA: 0x30c86d8 VA: 0x75956e06d8
	public Void .ctor() { }
	// RVA: 0x30c8748 VA: 0x75956e0748
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```