# AdvancedSelectorWithBuffStackcount

**Namespace:** `Torappu.Battle`


## Fields

- `String _buffKey`

- `UInt32 _buffStackcount`

- `CompareType _compareType`


## Methods

- `Void _CheckBuff(List`1)`

- `Void <>xLuaBaseProxy_OnPostFilter(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class AdvancedSelectorWithBuffStackcount : AdvancedSelector
{
	private String _buffKey; // 0xe8
	private UInt32 _buffStackcount; // 0xf0
	private CompareType _compareType; // 0xf4
	private static DelegateBridge __Hotfix0_OnPostFilter; // 0x0
	private static DelegateBridge __Hotfix0__CheckBuff; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x1b9a684 VA: 0x75941b2684
	protected override Void OnPostFilter(List`1 candidates) { }
	// RVA: 0x1b9a710 VA: 0x75941b2710
	private Void _CheckBuff(List`1 candidates) { }
	// RVA: 0x1b9a908 VA: 0x75941b2908
	public Void .ctor() { }
	// RVA: 0x1b9a97c VA: 0x75941b297c
	private Void <>xLuaBaseProxy_OnPostFilter(List`1 P0) { }
}
```