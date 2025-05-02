# QCShopControllerObj

**Namespace:** `Torappu.UI.Shop`


## Fields

- `UIQCShopEvent clickEvent`

- `TwoStateToggle _clickChange`

- `QCShopDetailShopEnum _shopState`

- `GameObject _newFlag`


## Properties

- `QCShopDetailShopEnum shopState`


## Methods

- `QCShopDetailShopEnum get_shopState()`

- `Void OnClick()`

- `Void ApplyNewFlag(List`1)`

- `Void ApplyState(QCShopDetailShopEnum)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class QCShopControllerObj : MonoBehaviour, IHotfixable
{
	public UIQCShopEvent clickEvent; // 0x18
	private TwoStateToggle _clickChange; // 0x20
	private QCShopDetailShopEnum _shopState; // 0x28
	private GameObject _newFlag; // 0x30
	private static DelegateBridge __Hotfix0_get_shopState; // 0x0
	private static DelegateBridge __Hotfix0_OnClick; // 0x8
	private static DelegateBridge __Hotfix0_ApplyNewFlag; // 0x10
	private static DelegateBridge __Hotfix0_ApplyState; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public QCShopDetailShopEnum shopState { get; }

	// RVA: 0x2450ba0 VA: 0x7594a68ba0
	public QCShopDetailShopEnum get_shopState() { }
	// RVA: 0x24520d8 VA: 0x7594a6a0d8
	public Void OnClick() { }
	// RVA: 0x2450d64 VA: 0x7594a68d64
	public Void ApplyNewFlag(List`1 newFlagList) { }
	// RVA: 0x2451fd4 VA: 0x7594a69fd4
	public Void ApplyState(QCShopDetailShopEnum state) { }
	// RVA: 0x245216c VA: 0x7594a6a16c
	public Void .ctor() { }
}
```