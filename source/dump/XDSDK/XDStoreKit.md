# XDStoreKit

**Namespace:** `XDSDK`


## Fields

- `Boolean m_isInited`

- `XDStoreKitHandler m_handler`

- `XDStorePayRequest m_payRequest`

- `Boolean m_isErrorHalted`

- `Boolean m_isFetchingProducts`


## Methods

- `Void InitIfNot(XDStoreKitHandler)`

- `Void _ErrorAndHalt(String)`

- `Boolean _CheckIfComponentValid()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : XDSDK
public class XDStoreKit : Singleton`1, IHotfixable
{
	private const Int32 DEFAULT_PRODUCT_QUALITY; // 0x0
	private Boolean m_isInited; // 0x10
	private XDStoreKitHandler m_handler; // 0x18
	private XDStorePayRequest m_payRequest; // 0x20
	private List`1 m_refreshReceiptCallbacks; // 0x28
	private Boolean m_isErrorHalted; // 0x30
	private Boolean m_isFetchingProducts; // 0x31
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__ErrorAndHalt; // 0x10
	private static DelegateBridge __Hotfix0__CheckIfComponentValid; // 0x18


	// RVA: 0x2582970 VA: 0x7594b9a970
	private Void .ctor() { }
	// RVA: 0x2582a54 VA: 0x7594b9aa54
	public Void InitIfNot(XDStoreKitHandler handler) { }
	// RVA: 0x2582ad8 VA: 0x7594b9aad8
	private Void _ErrorAndHalt(String errorInfo) { }
	// RVA: 0x2582b88 VA: 0x7594b9ab88
	private Boolean _CheckIfComponentValid() { }
}
```