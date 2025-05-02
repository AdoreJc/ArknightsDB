# RoguelikeDiceModuleData

**Namespace:** `Torappu`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class RoguelikeDiceModuleData : RoguelikeModuleBaseData
{
	public Dictionary`2 dice; // 0x10
	public Dictionary`2 diceEvents; // 0x18
	public Dictionary`2 diceChoices; // 0x20
	public Dictionary`2 diceRuleGroups; // 0x28
	public List`1 dicePredefines; // 0x30

	public override RoguelikeModuleType moduleType { get; }

	// RVA: 0x34a9000 VA: 0x7595ac1000
	public override RoguelikeModuleType get_moduleType() { }
	// RVA: 0x34a9008 VA: 0x7595ac1008
	public Void .ctor() { }
}
```