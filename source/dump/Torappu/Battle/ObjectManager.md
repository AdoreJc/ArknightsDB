# ObjectManager

**Namespace:** `Torappu.Battle`


## Methods

- `Void set_projectiles(UnorderedArray`1)`

- `Void Register(BObject)`

- `Void Unregister(BObject)`

- `Void Clear()`

- `Void OnFixedUpdate(FP)`

- `Void OnLateFixedUpdate(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class ObjectManager
{
	private PriorityQueue`1 m_objects; // 0x10
	private List`1 m_cachedList; // 0x18
	private UnorderedArray`1 <projectiles>k__BackingField; // 0x20

	public UnorderedArray`1 projectiles { get; set; }

	// RVA: 0x40a2478 VA: 0x75966ba478
	public UnorderedArray`1 get_projectiles() { }
	// RVA: 0x40a2480 VA: 0x75966ba480
	private Void set_projectiles(UnorderedArray`1 value) { }
	// RVA: 0x40a2488 VA: 0x75966ba488
	public Void .ctor(Int32 capacity) { }
	// RVA: 0x40a25c8 VA: 0x75966ba5c8
	public Void Register(BObject obj) { }
	// RVA: 0x40a26d8 VA: 0x75966ba6d8
	public Void Unregister(BObject obj) { }
	// RVA: 0x40a27dc VA: 0x75966ba7dc
	public Void Clear() { }
	// RVA: 0x40a28d8 VA: 0x75966ba8d8
	public Void OnFixedUpdate(FP deltaTime) { }
	// RVA: 0x40a2ac8 VA: 0x75966baac8
	public Void OnLateFixedUpdate(FP deltaTime) { }
}
```