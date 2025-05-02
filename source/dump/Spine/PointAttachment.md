# PointAttachment

**Namespace:** `Spine`


## Properties

- `Single X`

- `Single Y`

- `Single Rotation`


## Methods

- `Single get_X()`

- `Void set_X(Single)`

- `Single get_Y()`

- `Void set_Y(Single)`

- `Single get_Rotation()`

- `Void set_Rotation(Single)`

- `Void ComputeWorldPosition(Bone, out, out)`

- `Single ComputeWorldRotation(Bone)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine
public class PointAttachment : Attachment
{
	internal Single x; // 0x18
	internal Single y; // 0x1c
	internal Single rotation; // 0x20

	public Single X { get; set; }
	public Single Y { get; set; }
	public Single Rotation { get; set; }

	// RVA: 0x61d2344 VA: 0x75987ea344
	public Single get_X() { }
	// RVA: 0x61d234c VA: 0x75987ea34c
	public Void set_X(Single value) { }
	// RVA: 0x61d2354 VA: 0x75987ea354
	public Single get_Y() { }
	// RVA: 0x61d235c VA: 0x75987ea35c
	public Void set_Y(Single value) { }
	// RVA: 0x61d2364 VA: 0x75987ea364
	public Single get_Rotation() { }
	// RVA: 0x61d236c VA: 0x75987ea36c
	public Void set_Rotation(Single value) { }
	// RVA: 0x61d2374 VA: 0x75987ea374
	public Void .ctor(String name) { }
	// RVA: 0x61d237c VA: 0x75987ea37c
	public Void ComputeWorldPosition(Bone bone, out Single ox, out Single oy) { }
	// RVA: 0x61d2408 VA: 0x75987ea408
	public Single ComputeWorldRotation(Bone bone) { }
	// RVA: 0x61d260c VA: 0x75987ea60c
	public override Attachment Copy() { }
}
```