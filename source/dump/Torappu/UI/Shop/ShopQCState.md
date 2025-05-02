# ShopQCState

**Namespace:** `Torappu.UI.Shop`


## Fields

- `QCShopDetailShopEnum currentState`

- `QCShopController _controller`


## Methods

- `Void ApplyDetailState(QCShopDetailShopEnum)`

- `Void OpenConverter()`

- `Void OpenClassicConverter()`

- `Void OnQCInfoClick()`

- `Void _ApplyDetailState(QCShopDetailShopEnum)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopQCState : ShopCommonState
{
	public const QCShopDetailShopEnum DEFAULT_STATE; // 0x0
	public QCShopDetailShopEnum currentState; // 0x68
	private QCShopController _controller; // 0x70
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_OnResume; // 0x8
	private static DelegateBridge __Hotfix0_ApplyDetailState; // 0x10
	private static DelegateBridge __Hotfix0_OpenConverter; // 0x18
	private static DelegateBridge __Hotfix0_OpenClassicConverter; // 0x20
	private static DelegateBridge __Hotfix0_OnQCInfoClick; // 0x28
	private static DelegateBridge __Hotfix0__ApplyDetailState; // 0x30
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x2473fd8 VA: 0x7594a8bfd8
	protected override Void OnEnter() { }
	// RVA: 0x2474198 VA: 0x7594a8c198
	protected override Void OnResume() { }
	// RVA: 0x2474280 VA: 0x7594a8c280
	public Void ApplyDetailState(QCShopDetailShopEnum type) { }
	// RVA: 0x247439c VA: 0x7594a8c39c
	public Void OpenConverter() { }
	// RVA: 0x2474530 VA: 0x7594a8c530
	public Void OpenClassicConverter() { }
	// RVA: 0x24746c4 VA: 0x7594a8c6c4
	public Void OnQCInfoClick() { }
	// RVA: 0x2474054 VA: 0x7594a8c054
	private Void _ApplyDetailState(QCShopDetailShopEnum type) { }
	// RVA: 0x24749a8 VA: 0x7594a8c9a8
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2474a0c VA: 0x7594a8ca0c
	public Void .ctor() { }
	// RVA: 0x2474a7c VA: 0x7594a8ca7c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2474a84 VA: 0x7594a8ca84
	private Void <>xLuaBaseProxy_OnResume() { }
}
```