# HGStoreKit

**Namespace:** `HGSDK`


## Fields

- `Boolean m_isInited`

- `HGStoreKitHandler m_handler`

- `HGStorePayRequest m_payRequest`

- `Boolean m_isErrorHalted`

- `Boolean m_isFetchingProducts`


## Methods

- `Void InitIfNot(HGStoreKitHandler)`

- `Void _ErrorAndHalt(String)`

- `Boolean _CheckIfComponentValid()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : HGSDK
public class HGStoreKit : Singleton`1, IHotfixable
{
	private const Int32 DEFAULT_PRODUCT_QUALITY; // 0x0
	private Boolean m_isInited; // 0x10
	private HGStoreKitHandler m_handler; // 0x18
	private HGStorePayRequest m_payRequest; // 0x20
	private List`1 m_refreshReceiptCallbacks; // 0x28
	private Boolean m_isErrorHalted; // 0x30
	private Boolean m_isFetchingProducts; // 0x31


	// RVA: 0x2f1bda0 VA: 0x7595533da0
	private Void .ctor() { }
	// RVA: 0x2f1be3c VA: 0x7595533e3c
	public Void InitIfNot(HGStoreKitHandler handler) { }
	// RVA: 0x2f1be44 VA: 0x7595533e44
	private Void _ErrorAndHalt(String errorInfo) { }
	// RVA: 0x2f1be70 VA: 0x7595533e70
	private Boolean _CheckIfComponentValid() { }
}
```