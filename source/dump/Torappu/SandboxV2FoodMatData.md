# SandboxV2FoodMatData

**Namespace:** `Torappu`


## Fields

- `String id`

- `SandboxV2FoodMatType type`

- `SandboxV2FoodAttribute attribute`

- `SandboxV2FoodVariantType variantType`

- `Int32 bonusDuration`

- `String buffDesc`

- `Int32 sortId`


## Methods

- `Boolean ShouldSerializeattribute()`

- `Boolean ShouldSerializevariantType()`

- `Boolean ShouldSerializebonusDuration()`

- `Boolean ShouldSerializebuffDesc()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class SandboxV2FoodMatData
{
	public String id; // 0x10
	public SandboxV2FoodMatType type; // 0x18
	public SandboxV2FoodAttribute attribute; // 0x1c
	public SandboxV2FoodVariantType variantType; // 0x20
	public Int32 bonusDuration; // 0x24
	public String buffDesc; // 0x28
	public Int32 sortId; // 0x30


	// RVA: 0x34b2698 VA: 0x7595aca698
	public Boolean ShouldSerializeattribute() { }
	// RVA: 0x34b26a8 VA: 0x7595aca6a8
	public Boolean ShouldSerializevariantType() { }
	// RVA: 0x34b26b8 VA: 0x7595aca6b8
	public Boolean ShouldSerializebonusDuration() { }
	// RVA: 0x34b26c8 VA: 0x7595aca6c8
	public Boolean ShouldSerializebuffDesc() { }
	// RVA: 0x34b26e8 VA: 0x7595aca6e8
	public Void .ctor() { }
}
```