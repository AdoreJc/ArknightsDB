# RL02OuterBuffItemModel

**Namespace:** `Torappu.UI.RoguelikeTopic.RL02`


## Fields

- `String buffId`

- `RL02DevelopmentNodeType nodeType`

- `UnlockStatus status`

- `PolarPoint position`

- `RL02DevelopmentEffectType effectType`

- `String rawDesc`

- `String iconId`

- `Int32 tokenCost`

- `String name`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL02
public class RL02OuterBuffItemModel : IHotfixable
{
	public String buffId; // 0x10
	public RL02DevelopmentNodeType nodeType; // 0x18
	public List`1 frontNodeId; // 0x20
	public UnlockStatus status; // 0x28
	public PolarPoint position; // 0x2c
	public List`1 buffDisplayInfo; // 0x38
	public RL02DevelopmentEffectType effectType; // 0x40
	public String rawDesc; // 0x48
	public String iconId; // 0x50
	public Int32 tokenCost; // 0x58
	public String name; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0


	// RVA: 0x26c6278 VA: 0x7594cde278
	public Void .ctor() { }
}
```