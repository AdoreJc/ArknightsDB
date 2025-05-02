# MobileTouchPickable

**Namespace:** `BitBenderGames`


## Fields

- `Transform pickableTransform`

- `Vector2 localSnapOffset`


## Properties

- `Transform PickableTransform`

- `Vector2 LocalSnapOffset`


## Methods

- `Transform get_PickableTransform()`

- `Void set_PickableTransform(Transform)`

- `Vector2 get_LocalSnapOffset()`

- `Void Awake()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : BitBenderGames
public class MobileTouchPickable : MonoBehaviour
{
	private static MobileTouchCamera mobileTouchCam; // 0x0
	private Transform pickableTransform; // 0x18
	private Vector2 localSnapOffset; // 0x20

	public Transform PickableTransform { get; set; }
	public Vector2 LocalSnapOffset { get; }

	// RVA: 0x2c2a864 VA: 0x7595242864
	public Transform get_PickableTransform() { }
	// RVA: 0x2c2a86c VA: 0x759524286c
	public Void set_PickableTransform(Transform value) { }
	// RVA: 0x2c2a874 VA: 0x7595242874
	public Vector2 get_LocalSnapOffset() { }
	// RVA: 0x2c2a87c VA: 0x759524287c
	public Void Awake() { }
	// RVA: 0x2c2ab98 VA: 0x7595242b98
	public Void .ctor() { }
}
```