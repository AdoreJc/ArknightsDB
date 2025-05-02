# FireworkPuzzleDetailStateBean

**Namespace:** `Torappu.UI.Firework.FireworkPuzzle`


## Fields

- `FireworkPuzzleDetailProp m_prop`

- `String <puzzleId>k__BackingField`


## Properties

- `String puzzleId`

- `FireworkPuzzleDetailProp prop`


## Methods

- `String get_puzzleId()`

- `Void set_puzzleId(String)`

- `FireworkPuzzleDetailProp get_prop()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Firework.FireworkPuzzle
public class FireworkPuzzleDetailStateBean : IStateBean, IHotfixable
{
	private FireworkPuzzleDetailProp m_prop; // 0x10
	private String <puzzleId>k__BackingField; // 0x18
	private static DelegateBridge __Hotfix0_get_puzzleId; // 0x0
	private static DelegateBridge __Hotfix0_set_puzzleId; // 0x8
	private static DelegateBridge __Hotfix0_get_prop; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public String puzzleId { get; set; }
	public FireworkPuzzleDetailProp prop { get; }

	// RVA: 0x28fa614 VA: 0x7594f12614
	public String get_puzzleId() { }
	// RVA: 0x28f7eac VA: 0x7594f0feac
	public Void set_puzzleId(String value) { }
	// RVA: 0x28fa67c VA: 0x7594f1267c
	public FireworkPuzzleDetailProp get_prop() { }
	// RVA: 0x28fa6e4 VA: 0x7594f126e4
	public Void .ctor() { }
}
```