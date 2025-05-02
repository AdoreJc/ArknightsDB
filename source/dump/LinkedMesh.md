# LinkedMesh

**Namespace:** ` `


## Dump
```C#
// Dll : spine-unity.dll
// Namespace : 
internal class LinkedMesh
{
	internal String parent; // 0x10
	internal String skin; // 0x18
	internal Int32 slotIndex; // 0x20
	internal MeshAttachment mesh; // 0x28
	internal Boolean inheritDeform; // 0x30


	// RVA: 0x61f1cd4 VA: 0x7598809cd4
	public Void .ctor(MeshAttachment mesh, String skin, Int32 slotIndex, String parent, Boolean inheritDeform) { }
}
```