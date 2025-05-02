# RectOffset

**Namespace:** `UnityEngine`


## Properties

- `Int32 left`

- `Int32 right`

- `Int32 top`

- `Int32 bottom`

- `Int32 horizontal`

- `Int32 vertical`


## Methods

- `String ToString(String, IFormatProvider)`

- `Void Destroy()`

- `Int32 get_left()`

- `Void set_left(Int32)`

- `Int32 get_right()`

- `Void set_right(Int32)`

- `Int32 get_top()`

- `Void set_top(Int32)`

- `Int32 get_bottom()`

- `Void set_bottom(Int32)`

- `Int32 get_horizontal()`

- `Int32 get_vertical()`

- `Rect Remove(Rect)`

- `Void Remove_Injected(ref, out)`


## Dump
```C#
// Dll : UnityEngine.CoreModule.dll
// Namespace : UnityEngine
public class RectOffset : IFormattable
{
	internal IntPtr m_Ptr; // 0x10
	private readonly Object m_SourceStyle; // 0x18

	public Int32 left { get; set; }
	public Int32 right { get; set; }
	public Int32 top { get; set; }
	public Int32 bottom { get; set; }
	public Int32 horizontal { get; }
	public Int32 vertical { get; }

	// RVA: 0x685bc08 VA: 0x7598e73c08
	public Void .ctor() { }
	// RVA: 0x685bc78 VA: 0x7598e73c78
	internal Void .ctor(Object sourceStyle, IntPtr source) { }
	// RVA: 0x685bcb4 VA: 0x7598e73cb4
	protected override Void Finalize() { }
	// RVA: 0x685bdf4 VA: 0x7598e73df4
	public Void .ctor(Int32 left, Int32 right, Int32 top, Int32 bottom) { }
	// RVA: 0x685c018 VA: 0x7598e74018
	public override String ToString() { }
	// RVA: 0x685c024 VA: 0x7598e74024
	public String ToString(String format, IFormatProvider formatProvider) { }
	// RVA: 0x685bd54 VA: 0x7598e73d54
	private Void Destroy() { }
	// RVA: 0x685bc50 VA: 0x7598e73c50
	private static IntPtr InternalCreate() { }
	// RVA: 0x685c3e0 VA: 0x7598e743e0
	private static Void InternalDestroy(IntPtr ptr) { }
	// RVA: 0x685c2f0 VA: 0x7598e742f0
	public Int32 get_left() { }
	// RVA: 0x685bf08 VA: 0x7598e73f08
	public Void set_left(Int32 value) { }
	// RVA: 0x685c32c VA: 0x7598e7432c
	public Int32 get_right() { }
	// RVA: 0x685bf4c VA: 0x7598e73f4c
	public Void set_right(Int32 value) { }
	// RVA: 0x685c368 VA: 0x7598e74368
	public Int32 get_top() { }
	// RVA: 0x685bf90 VA: 0x7598e73f90
	public Void set_top(Int32 value) { }
	// RVA: 0x685c3a4 VA: 0x7598e743a4
	public Int32 get_bottom() { }
	// RVA: 0x685bfd4 VA: 0x7598e73fd4
	public Void set_bottom(Int32 value) { }
	// RVA: 0x685c41c VA: 0x7598e7441c
	public Int32 get_horizontal() { }
	// RVA: 0x685c458 VA: 0x7598e74458
	public Int32 get_vertical() { }
	// RVA: 0x685c494 VA: 0x7598e74494
	public Rect Remove(Rect rect) { }
	// RVA: 0x685c4f8 VA: 0x7598e744f8
	private Void Remove_Injected(ref Rect rect, out Rect ret) { }
}
```