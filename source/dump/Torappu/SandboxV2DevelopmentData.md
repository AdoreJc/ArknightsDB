# SandboxV2DevelopmentData

**Namespace:** `Torappu`


## Fields

- `String techId`

- `SandboxV2DevelopmentType techType`

- `Int32 positionX`

- `Int32 positionY`

- `String frontNodeId`

- `Int32 limitBaseLevel`

- `Int32 tokenCost`

- `String techName`

- `String techIconId`

- `String nodeTitle`

- `String rawDesc`

- `Boolean canBuffReserch`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class SandboxV2DevelopmentData
{
	public String techId; // 0x10
	public SandboxV2DevelopmentType techType; // 0x18
	public Int32 positionX; // 0x1c
	public Int32 positionY; // 0x20
	public String frontNodeId; // 0x28
	public List`1 nextNodeIds; // 0x30
	public Int32 limitBaseLevel; // 0x38
	public Int32 tokenCost; // 0x3c
	public String techName; // 0x40
	public String techIconId; // 0x48
	public String nodeTitle; // 0x50
	public String rawDesc; // 0x58
	public Boolean canBuffReserch; // 0x60


	// RVA: 0x34f20d4 VA: 0x7595b0a0d4
	public Void .ctor() { }
}
```