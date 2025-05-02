# Skin

**Namespace:** `Spine`


## Properties

- `String Name`


## Methods

- `String get_Name()`

- `Void SetAttachment(Int32, String, Attachment)`

- `Void AddSkin(Skin)`

- `Void CopySkin(Skin)`

- `Attachment GetAttachment(Int32, String)`

- `Void RemoveAttachment(Int32, String)`

- `Void GetAttachments(Int32, List`1)`

- `Void Clear()`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine
public class Skin
{
	internal String name; // 0x10
	private OrderedDictionary`2 attachments; // 0x18
	internal readonly ExposedList`1 bones; // 0x20
	internal readonly ExposedList`1 constraints; // 0x28

	public String Name { get; }
	public OrderedDictionary`2 Attachments { get; }
	public ExposedList`1 Bones { get; }
	public ExposedList`1 Constraints { get; }

	// RVA: 0x61f2310 VA: 0x759880a310
	public String get_Name() { }
	// RVA: 0x61f2318 VA: 0x759880a318
	public OrderedDictionary`2 get_Attachments() { }
	// RVA: 0x61f2320 VA: 0x759880a320
	public ExposedList`1 get_Bones() { }
	// RVA: 0x61f2328 VA: 0x759880a328
	public ExposedList`1 get_Constraints() { }
	// RVA: 0x61ebbb4 VA: 0x7598803bb4
	public Void .ctor(String name) { }
	// RVA: 0x61eca10 VA: 0x7598804a10
	public Void SetAttachment(Int32 slotIndex, String name, Attachment attachment) { }
	// RVA: 0x61f239c VA: 0x759880a39c
	public Void AddSkin(Skin skin) { }
	// RVA: 0x61f2940 VA: 0x759880a940
	public Void CopySkin(Skin skin) { }
	// RVA: 0x61ecb4c VA: 0x7598804b4c
	public Attachment GetAttachment(Int32 slotIndex, String name) { }
	// RVA: 0x61f2f90 VA: 0x759880af90
	public Void RemoveAttachment(Int32 slotIndex, String name) { }
	// RVA: 0x61f3090 VA: 0x759880b090
	public ICollection`1 GetAttachments() { }
	// RVA: 0x61f30e0 VA: 0x759880b0e0
	public Void GetAttachments(Int32 slotIndex, List`1 attachments) { }
	// RVA: 0x61f34c0 VA: 0x759880b4c0
	public Void Clear() { }
	// RVA: 0x61f3560 VA: 0x759880b560
	public override String ToString() { }
	// RVA: 0x61f3568 VA: 0x759880b568
	internal Void AttachAll(Skeleton skeleton, Skin oldSkin) { }
}
```