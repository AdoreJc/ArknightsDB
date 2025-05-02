# RL02Development

**Namespace:** `Torappu`


## Fields

- `String buffId`

- `RL02DevelopmentNodeType nodeType`

- `Int32 positionP`

- `Int32 positionR`

- `Int32 tokenCost`

- `String buffName`

- `String buffIconId`

- `RL02DevelopmentEffectType effectType`

- `String rawDesc`

- `String enrollId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class RL02Development
{
	public String buffId; // 0x10
	public RL02DevelopmentNodeType nodeType; // 0x18
	public List`1 frontNodeId; // 0x20
	public List`1 nextNodeId; // 0x28
	public Int32 positionP; // 0x30
	public Int32 positionR; // 0x34
	public Int32 tokenCost; // 0x38
	public String buffName; // 0x40
	public String buffIconId; // 0x48
	public RL02DevelopmentEffectType effectType; // 0x50
	public String rawDesc; // 0x58
	public List`1 buffDisplayInfo; // 0x60
	public String enrollId; // 0x68


	// RVA: 0x34ab3ec VA: 0x7595ac33ec
	public Void .ctor() { }
}
```