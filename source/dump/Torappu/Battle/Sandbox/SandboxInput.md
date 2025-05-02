# SandboxInput

**Namespace:** `Torappu.Battle.Sandbox`


## Fields

- `String exploredMap`

- `String topicId`

- `Int32 currentAp`

- `Int32 baseLv`

- `String monthlyRushId`

- `RiftData riftData`

- `Boolean escapeTrap`

- `SandboxV2NodeRelatedData nodeRelatedData`

- `Int32 remainingRacerItemSpace`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Sandbox
public class SandboxInput : IHotfixable
{
	public String exploredMap; // 0x10
	public String topicId; // 0x18
	public Int32 currentAp; // 0x20
	public Int32 baseLv; // 0x24
	public String monthlyRushId; // 0x28
	public List`1 bossKill; // 0x30
	public List`1 entityStatus; // 0x38
	public List`1 placedItems; // 0x40
	public Dictionary`2 constructItems; // 0x48
	public List`1 rushEnemies; // 0x50
	public Dictionary`2 bossStatus; // 0x58
	public Dictionary`2 resCollected; // 0x60
	public List`1 luredRacers; // 0x68
	public Dictionary`2 catchedAnimals; // 0x70
	public ListDict`2 rareAnimals; // 0x78
	public List`1 action; // 0x80
	public List`1 actionKill; // 0x88
	public RiftData riftData; // 0x90
	public Boolean escapeTrap; // 0x98
	public List`1 npcDatas; // 0xa0
	public Dictionary`2 conditionProgress; // 0xa8
	public Dictionary`2 npcFavor; // 0xb0
	public Dictionary`2 globalBuilding; // 0xb8
	public Dictionary`2 buildingLimit; // 0xc0
	public SandboxV2NodeRelatedData nodeRelatedData; // 0xc8
	public List`1 storyIds; // 0xd0
	public Dictionary`2 shinyAnimals; // 0xd8
	public List`1 shinyUniEnemy; // 0xe0
	public Int32 remainingRacerItemSpace; // 0xe8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0


	// RVA: 0x1dfa13c VA: 0x759441213c
	public Void .ctor() { }
}
```