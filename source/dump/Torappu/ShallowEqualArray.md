# ShallowEqualArray

**Namespace:** `Torappu`


## Properties

- `Int32 length`

- `T Item`


## Methods

- `Int32 get_length()`

- `T get_Item(Int32)`

- `Void set_Item(Int32, T)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class ShallowEqualArray`1
{
	private T[] m_content; // 0x0

	public Int32 length { get; }
	public T Item { get; set; }

	// RVA: 0x VA: 0x0
	public Void .ctor(T[] array) { }
	// RVA: 0x VA: 0x0
	public Int32 get_length() { }
	// RVA: 0x VA: 0x0
	public T get_Item(Int32 index) { }
	// RVA: 0x VA: 0x0
	public Void set_Item(Int32 index, T value) { }
	// RVA: 0x VA: 0x0
	public static T[] op_Implicit(ShallowEqualArray`1 ary) { }
	// RVA: 0x VA: 0x0
	public static ShallowEqualArray`1 op_Implicit(T[] content) { }
	// RVA: 0x VA: 0x0
	public ShallowEqualArray`1 Clone() { }
	// RVA: 0x VA: 0x0
	public override Int32 GetHashCode() { }
	// RVA: 0x VA: 0x0
	public override Boolean Equals(Object obj) { }
}
```