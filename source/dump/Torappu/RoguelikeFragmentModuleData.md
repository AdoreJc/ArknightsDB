# RoguelikeFragmentModuleData

**Namespace:** `Torappu`


## Fields

- `RoguelikeFragmentModuleConsts moduleConsts`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class RoguelikeFragmentModuleData : RoguelikeModuleBaseData
{
	public Dictionary`2 fragmentData; // 0x10
	public Dictionary`2 fragmentTypeData; // 0x18
	public RoguelikeFragmentModuleConsts moduleConsts; // 0x20
	public Dictionary`2 fragmentBuffData; // 0x28
	public ListDict`2 alchemyData; // 0x30
	public Dictionary`2 alchemyFormulaData; // 0x38
	public Dictionary`2 fragmentLevelData; // 0x40

	public override RoguelikeModuleType moduleType { get; }

	// RVA: 0x34a92d4 VA: 0x7595ac12d4
	public override RoguelikeModuleType get_moduleType() { }
	// RVA: 0x34a92dc VA: 0x7595ac12dc
	public Void .ctor() { }
}
```