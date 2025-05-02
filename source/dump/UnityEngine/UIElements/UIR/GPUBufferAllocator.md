# GPUBufferAllocator

**Namespace:** `UnityEngine.UIElements.UIR`


## Fields

- `BestFitAllocator m_Low`

- `BestFitAllocator m_High`


## Properties

- `Boolean isEmpty`


## Methods

- `Alloc Allocate(UInt32, Boolean)`

- `Void Free(Alloc)`

- `Boolean get_isEmpty()`

- `Boolean HighLowCollide()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements.UIR
internal class GPUBufferAllocator
{
	private BestFitAllocator m_Low; // 0x10
	private BestFitAllocator m_High; // 0x18

	public Boolean isEmpty { get; }

	// RVA: 0x6965264 VA: 0x7598f7d264
	public Void .ctor(UInt32 maxSize) { }
	// RVA: 0x69601b8 VA: 0x7598f781b8
	public Alloc Allocate(UInt32 size, Boolean shortLived) { }
	// RVA: 0x69602f4 VA: 0x7598f782f4
	public Void Free(Alloc alloc) { }
	// RVA: 0x6965344 VA: 0x7598f7d344
	public Boolean get_isEmpty() { }
	// RVA: 0x696530c VA: 0x7598f7d30c
	private Boolean HighLowCollide() { }
}
```