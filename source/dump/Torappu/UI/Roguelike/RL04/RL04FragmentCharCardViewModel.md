# RL04FragmentCharCardViewModel

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `String charId`

- `String avatarId`

- `EvolvePhase evolvePhase`

- `Int32 weight`

- `Int32 instId`


## Properties

- `Boolean isEmpty`


## Methods

- `Boolean get_isEmpty()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04FragmentCharCardViewModel : IHotfixable
{
	public String charId; // 0x10
	public String avatarId; // 0x18
	public EvolvePhase evolvePhase; // 0x20
	public Int32 weight; // 0x24
	public Int32 instId; // 0x28
	private static DelegateBridge __Hotfix0_get_isEmpty; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8

	public Boolean isEmpty { get; }

	// RVA: 0x2b26c84 VA: 0x759513ec84
	public Boolean get_isEmpty() { }
	// RVA: 0x2b26cf0 VA: 0x759513ecf0
	public Void .ctor() { }
}
```