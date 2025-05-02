# NPCData

**Namespace:** `Torappu`


## Fields

- `String npcId`

- `String name`

- `String appellation`

- `ProfessionCategory profession`

- `String cv`

- `String displayNumber`

- `String nationId`

- `String groupId`

- `String teamId`

- `IllustNPCResType resType`

- `Boolean npcShowAudioInfoFlag`


## Properties

- `String minPowerId`


## Methods

- `String get_minPowerId()`

- `String GetPowerIdByLevel(PowerLevel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class NPCData
{
	public String npcId; // 0x10
	public String name; // 0x18
	public String appellation; // 0x20
	public ProfessionCategory profession; // 0x28
	public List`1 illustList; // 0x30
	public List`1 designerList; // 0x38
	public String cv; // 0x40
	public String displayNumber; // 0x48
	public String nationId; // 0x50
	public String groupId; // 0x58
	public String teamId; // 0x60
	public IllustNPCResType resType; // 0x68
	public Boolean npcShowAudioInfoFlag; // 0x6c
	public Dictionary`2 unlockDict; // 0x70

	public String minPowerId { get; }

	// RVA: 0x34a5dd0 VA: 0x7595abddd0
	public String get_minPowerId() { }
	// RVA: 0x34a5e50 VA: 0x7595abde50
	public String GetPowerIdByLevel(PowerLevel level) { }
	// RVA: 0x34a5e88 VA: 0x7595abde88
	public Void .ctor() { }
}
```