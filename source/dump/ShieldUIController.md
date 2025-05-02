# ShieldUIController

**Namespace:** ` `


## Fields

- `Entity m_owner`

- `FP m_shieldToShow`


## Properties

- `FP shieldToShow`


## Methods

- `FP get_shieldToShow()`

- `Void Reset(Entity)`

- `Void CalculateShieldData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ShieldUIController : IHotfixable
{
	private Entity m_owner; // 0x10
	private FP m_shieldToShow; // 0x18
	private static DelegateBridge __Hotfix0_get_shieldToShow; // 0x0
	private static DelegateBridge __Hotfix0_Reset; // 0x8
	private static DelegateBridge __Hotfix0_CalculateShieldData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public FP shieldToShow { get; }

	// RVA: 0x3fd39ec VA: 0x75965eb9ec
	public FP get_shieldToShow() { }
	// RVA: 0x3fd3a54 VA: 0x75965eba54
	public Void Reset(Entity owner) { }
	// RVA: 0x3fd3b10 VA: 0x75965ebb10
	public Void CalculateShieldData() { }
	// RVA: 0x3fd3c28 VA: 0x75965ebc28
	public Void .ctor() { }
}
```