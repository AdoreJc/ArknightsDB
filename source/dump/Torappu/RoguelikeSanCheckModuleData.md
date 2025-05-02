# RoguelikeSanCheckModuleData

**Namespace:** `Torappu`


## Fields

- `RoguelikeSanCheckConsts moduleConsts`


## Methods

- `RoguelikeSanRangeData GetSanRangeBySanValue(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class RoguelikeSanCheckModuleData : RoguelikeModuleBaseData
{
	public List`1 sanRanges; // 0x10
	public RoguelikeSanCheckConsts moduleConsts; // 0x18

	public override RoguelikeModuleType moduleType { get; }

	// RVA: 0x34a8e4c VA: 0x7595ac0e4c
	public override RoguelikeModuleType get_moduleType() { }
	// RVA: 0x34a8e54 VA: 0x7595ac0e54
	public RoguelikeSanRangeData GetSanRangeBySanValue(Int32 sanValue) { }
	// RVA: 0x34a8fe8 VA: 0x7595ac0fe8
	public Void .ctor() { }
}
```