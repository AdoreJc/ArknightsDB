# RangeData

**Namespace:** `Torappu`


## Fields

- `String id`

- `Direction direction`


## Methods

- `Void OnInit()`

- `Void _ConstructBoundingBoxes()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class RangeData
{
	public const Direction RANGE_STANDARD_DIRECTION; // 0x0
	private static List`1 s_sharedList; // 0x0
	private static HashSet`1 s_sharedRemainingSet; // 0x8
	private static HashSet`1 s_sharedAllSet; // 0x10
	public String id; // 0x10
	public Direction direction; // 0x18
	public List`1 grids; // 0x20
	public List`1 boundingBoxes; // 0x28


	// RVA: 0x34a61ac VA: 0x7595abe1ac
	public Void OnInit() { }
	// RVA: 0x34a61b0 VA: 0x7595abe1b0
	private Void _ConstructBoundingBoxes() { }
	// RVA: 0x34a6734 VA: 0x7595abe734
	private static Boolean _TryFindBoundingBox(GridPosition min, HashSet`1 remainingSet, HashSet`1 allSet, out ObscuredRect rect) { }
	// RVA: 0x34a6b34 VA: 0x7595abeb34
	public Void .ctor() { }
	// RVA: 0x34a6bc4 VA: 0x7595abebc4
	private static Void .cctor() { }
}
```