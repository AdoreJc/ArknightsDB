# VDoor

**Namespace:** `Torappu.Building.Vault`


## Fields

- `LeftOrRight _defaultSide`

- `GameObject _outlineObj`

- `LeftOrRight <side>k__BackingField`


## Properties

- `LeftOrRight side`


## Methods

- `LeftOrRight get_side()`

- `Void set_side(LeftOrRight)`

- `Void Locate(Vector3, LeftOrRight)`

- `Void EnableOutline(Boolean)`

- `Void Awake()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.Vault
public class VDoor : MonoBehaviour
{
	private LeftOrRight _defaultSide; // 0x18
	private GameObject _outlineObj; // 0x20
	private LeftOrRight <side>k__BackingField; // 0x28

	public LeftOrRight side { get; set; }

	// RVA: 0x3d02700 VA: 0x759631a700
	public LeftOrRight get_side() { }
	// RVA: 0x3d02708 VA: 0x759631a708
	private Void set_side(LeftOrRight value) { }
	// RVA: 0x3d02710 VA: 0x759631a710
	public Void Locate(Vector3 worldPos, LeftOrRight side) { }
	// RVA: 0x3cfd82c VA: 0x759631582c
	public Void EnableOutline(Boolean value) { }
	// RVA: 0x3d02844 VA: 0x759631a844
	private Void Awake() { }
	// RVA: 0x3d028c4 VA: 0x759631a8c4
	public Void .ctor() { }
}
```