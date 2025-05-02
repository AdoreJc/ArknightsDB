# GPUBuffer

**Namespace:** ` `


## Fields

- `IntPtr buffer`

- `Int32 elemCount`

- `Int32 elemStride`


## Properties

- `Int32 ElementStride`


## Methods

- `Void Dispose()`

- `Void UpdateRanges(NativeSlice`1, Int32, Int32)`

- `Int32 get_ElementStride()`


## Dump
```C#
// Dll : UnityEngine.UIElementsNativeModule.dll
// Namespace : 
public class GPUBuffer`1 : IDisposable
{
	private IntPtr buffer; // 0x0
	private Int32 elemCount; // 0x0
	private Int32 elemStride; // 0x0

	public Int32 ElementStride { get; }
	internal IntPtr BufferPointer { get; }

	// RVA: 0x VA: 0x0
	public Void .ctor(Int32 elementCount, GPUBufferType type) { }
	// RVA: 0x VA: 0x0
	public Void Dispose() { }
	// RVA: 0x VA: 0x0
	public Void UpdateRanges(NativeSlice`1 ranges, Int32 rangesMin, Int32 rangesMax) { }
	// RVA: 0x VA: 0x0
	public Int32 get_ElementStride() { }
	// RVA: 0x VA: 0x0
	internal IntPtr get_BufferPointer() { }
}
```