# ObjectPool

**Namespace:** `XLua`


## Fields

- `Int32 freelist`

- `Int32 count`


## Properties

- `Object Item`


## Methods

- `Object get_Item(Int32)`

- `Void Clear()`

- `Void extend_capacity()`

- `Int32 Add(Object)`

- `Boolean TryGetValue(Int32, out)`

- `Object Get(Int32)`

- `Object Remove(Int32)`

- `Object Replace(Int32, Object)`

- `Int32 Check(Int32, Int32, Func`2, Dictionary`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : XLua
public class ObjectPool
{
	private const Int32 LIST_END; // 0x0
	private const Int32 ALLOCED; // 0x0
	private Slot[] list; // 0x10
	private Int32 freelist; // 0x18
	private Int32 count; // 0x1c

	public Object Item { get; }

	// RVA: 0x3ff109c VA: 0x759660909c
	public Object get_Item(Int32 i) { }
	// RVA: 0x3ff10e4 VA: 0x75966090e4
	public Void Clear() { }
	// RVA: 0x3ff1144 VA: 0x7596609144
	private Void extend_capacity() { }
	// RVA: 0x3ff1218 VA: 0x7596609218
	public Int32 Add(Object obj) { }
	// RVA: 0x3ff1334 VA: 0x7596609334
	public Boolean TryGetValue(Int32 index, out Object obj) { }
	// RVA: 0x3ff13b0 VA: 0x75966093b0
	public Object Get(Int32 index) { }
	// RVA: 0x3ff13f8 VA: 0x75966093f8
	public Object Remove(Int32 index) { }
	// RVA: 0x3ff149c VA: 0x759660949c
	public Object Replace(Int32 index, Object o) { }
	// RVA: 0x3ff14f4 VA: 0x75966094f4
	public Int32 Check(Int32 check_pos, Int32 max_check, Func`2 checker, Dictionary`2 reverse_map) { }
	// RVA: 0x3ff1688 VA: 0x7596609688
	public Void .ctor() { }
}
```