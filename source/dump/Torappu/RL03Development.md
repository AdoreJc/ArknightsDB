# RL03Development

**Namespace:** `Torappu`


## Fields

- `String buffId`

- `RL03DevelopmentNodeType nodeType`

- `Int32 positionRow`

- `Int32 positionOrder`

- `Int32 tokenCost`

- `String buffName`

- `String buffIconId`

- `RL03DevelopmentEffectType effectType`

- `String groupId`

- `String enrollId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class RL03Development
{
	public String buffId; // 0x10
	public RL03DevelopmentNodeType nodeType; // 0x18
	public List`1 frontNodeId; // 0x20
	public List`1 nextNodeId; // 0x28
	public Int32 positionRow; // 0x30
	public Int32 positionOrder; // 0x34
	public Int32 tokenCost; // 0x38
	public String buffName; // 0x40
	public String buffIconId; // 0x48
	public RL03DevelopmentEffectType effectType; // 0x50
	public List`1 rawDesc; // 0x58
	public List`1 buffDisplayInfo; // 0x60
	public String groupId; // 0x68
	public String enrollId; // 0x70


	// RVA: 0x34b0cd0 VA: 0x7595ac8cd0
	public Void .ctor() { }
}
```