# RL03TotemBuffMapNodeViewModel

**Namespace:** `Torappu.UI.Roguelike.RL03`


## Fields

- `String topicId`

- `RoguelikeDungeonNode node`

- `TotemMapNodeSelectType selectType`

- `Boolean isManualSelected`


## Properties

- `Boolean isSelectable`


## Methods

- `Boolean get_isSelectable()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL03
public class RL03TotemBuffMapNodeViewModel : IHotfixable
{
	public String topicId; // 0x10
	public RoguelikeDungeonNode node; // 0x18
	public TotemMapNodeSelectType selectType; // 0x20
	public Boolean isManualSelected; // 0x24
	private static DelegateBridge __Hotfix0_get_isSelectable; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8

	public Boolean isSelectable { get; }

	// RVA: 0x2ba994c VA: 0x75951c194c
	public Boolean get_isSelectable() { }
	// RVA: 0x2baad6c VA: 0x75951c2d6c
	public Void .ctor() { }
}
```