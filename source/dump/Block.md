# Block

**Namespace:** ` `


## Fields

- `UInt32 start`

- `UInt32 end`

- `Block prev`

- `Block next`

- `Block prevAvailable`

- `Block nextAvailable`

- `Boolean allocated`


## Properties

- `UInt32 size`


## Methods

- `UInt32 get_size()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : 
private class Block : LinkedPoolItem`1
{
	public UInt32 start; // 0x18
	public UInt32 end; // 0x1c
	public Block prev; // 0x20
	public Block next; // 0x28
	public Block prevAvailable; // 0x30
	public Block nextAvailable; // 0x38
	public Boolean allocated; // 0x40

	public UInt32 size { get; }

	// RVA: 0x6964c90 VA: 0x7598f7cc90
	public UInt32 get_size() { }
	// RVA: 0x6965218 VA: 0x7598f7d218
	public Void .ctor() { }
}
```