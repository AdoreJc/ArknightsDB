# SecondaryFilterExAdvancedSelector

**Namespace:** `Torappu.Battle`


## Fields

- `SecondaryFilterExType _secondaryFilterEx`


## Methods

- `Void _CheckSecondFilter(List`1)`

- `Void <>xLuaBaseProxy_OnPostFilter(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class SecondaryFilterExAdvancedSelector : AdvancedSelector
{
	private SecondaryFilterExType _secondaryFilterEx; // 0xe8
	private static DelegateBridge __Hotfix0_OnPostFilter; // 0x0
	private static DelegateBridge __Hotfix0__CheckSecondFilter; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x1bba250 VA: 0x75941d2250
	protected override Void OnPostFilter(List`1 candidates) { }
	// RVA: 0x1bba500 VA: 0x75941d2500
	private Void _CheckSecondFilter(List`1 candidates) { }
	// RVA: 0x1bba5f0 VA: 0x75941d25f0
	public Void .ctor() { }
	// RVA: 0x1bba660 VA: 0x75941d2660
	private Void <>xLuaBaseProxy_OnPostFilter(List`1 P0) { }
}
```