# RoguelikeChaosModuleData

**Namespace:** `Torappu`


## Fields

- `RoguelikeChaosModuleConsts moduleConsts`


## Methods

- `RoguelikeChaosRangeData GetChaosRangeByValue(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class RoguelikeChaosModuleData : RoguelikeModuleBaseData
{
	public Dictionary`2 chaosDatas; // 0x10
	public List`1 chaosRanges; // 0x18
	public Dictionary`2 levelInfoDict; // 0x20
	public RoguelikeChaosModuleConsts moduleConsts; // 0x28

	public override RoguelikeModuleType moduleType { get; }

	// RVA: 0x34a9030 VA: 0x7595ac1030
	public override RoguelikeModuleType get_moduleType() { }
	// RVA: 0x34a9038 VA: 0x7595ac1038
	public RoguelikeChaosRangeData GetChaosRangeByValue(Int32 chaosValue) { }
	// RVA: 0x34a91cc VA: 0x7595ac11cc
	public Void .ctor() { }
}
```