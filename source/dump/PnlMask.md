# PnlMask

**Namespace:** ` `


## Fields

- `GameObject _mask`

- `Boolean m_showForbiddenMask`

- `Boolean m_showUnavailableMask`


## Methods

- `Void SetMaskShowStatus(ShowType, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class PnlMask : IHotfixable
{
	private GameObject _mask; // 0x10
	private Boolean m_showForbiddenMask; // 0x18
	private Boolean m_showUnavailableMask; // 0x19
	private static DelegateBridge __Hotfix0_SetMaskShowStatus; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x30ef024 VA: 0x7595707024
	public Void SetMaskShowStatus(ShowType showType, Boolean status) { }
	// RVA: 0x30f0ae8 VA: 0x7595708ae8
	public Void .ctor() { }
}
```