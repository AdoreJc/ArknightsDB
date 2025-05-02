# LocationTotemMapSelectResult

**Namespace:** `Torappu.UI.Roguelike.RL03`


## Fields

- `TotemMapNodeSelectType selectType`


## Properties

- `Boolean haveSelectableNode`


## Methods

- `Boolean get_haveSelectableNode()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL03
public class LocationTotemMapSelectResult : IHotfixable
{
	public HashSet`1 selectableNodeSet; // 0x10
	public TotemMapNodeSelectType selectType; // 0x18
	private static DelegateBridge __Hotfix0_get_haveSelectableNode; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8

	public Boolean haveSelectableNode { get; }

	// RVA: 0x2baa928 VA: 0x75951c2928
	public Boolean get_haveSelectableNode() { }
	// RVA: 0x2baa9b4 VA: 0x75951c29b4
	public Void .ctor() { }
}
```