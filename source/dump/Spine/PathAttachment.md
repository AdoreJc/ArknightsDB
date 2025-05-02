# PathAttachment

**Namespace:** `Spine`


## Properties

- `Boolean Closed`

- `Boolean ConstantSpeed`


## Methods

- `Void set_Lengths(Single[])`

- `Boolean get_Closed()`

- `Void set_Closed(Boolean)`

- `Boolean get_ConstantSpeed()`

- `Void set_ConstantSpeed(Boolean)`


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : Spine
public class PathAttachment : VertexAttachment
{
	internal Single[] lengths; // 0x40
	internal Boolean closed; // 0x48
	internal Boolean constantSpeed; // 0x49

	public Single[] Lengths { get; set; }
	public Boolean Closed { get; set; }
	public Boolean ConstantSpeed { get; set; }

	// RVA: 0x61d1f58 VA: 0x75987e9f58
	public Single[] get_Lengths() { }
	// RVA: 0x61d1f60 VA: 0x75987e9f60
	public Void set_Lengths(Single[] value) { }
	// RVA: 0x61d1f68 VA: 0x75987e9f68
	public Boolean get_Closed() { }
	// RVA: 0x61d1f70 VA: 0x75987e9f70
	public Void set_Closed(Boolean value) { }
	// RVA: 0x61d1f7c VA: 0x75987e9f7c
	public Boolean get_ConstantSpeed() { }
	// RVA: 0x61d1f84 VA: 0x75987e9f84
	public Void set_ConstantSpeed(Boolean value) { }
	// RVA: 0x61d1f90 VA: 0x75987e9f90
	public Void .ctor(String name) { }
	// RVA: 0x61d213c VA: 0x75987ea13c
	public override Attachment Copy() { }
}
```