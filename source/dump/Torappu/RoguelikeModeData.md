# RoguelikeModeData

**Namespace:** `Torappu`


## Fields

- `String id`

- `String name`

- `Int32 canUnlockItem`

- `Single scoreFactor`

- `String difficultyDesc`

- `String ruleDesc`

- `Int32 sortId`

- `String unlockMode`

- `String color`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class RoguelikeModeData
{
	public String id; // 0x10
	public String name; // 0x18
	public Int32 canUnlockItem; // 0x20
	public Single scoreFactor; // 0x24
	public List`1 itemPools; // 0x28
	public String difficultyDesc; // 0x30
	public String ruleDesc; // 0x38
	public Int32 sortId; // 0x40
	public String unlockMode; // 0x48
	public String color; // 0x50


	// RVA: 0x34a8d9c VA: 0x7595ac0d9c
	public Void .ctor() { }
}
```