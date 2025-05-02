# Object

**Namespace:** `System`


## Methods

- `Type GetType()`

- `Object MemberwiseClone()`

- `Void FieldGetter(String, String, ref)`

- `Void FieldSetter(String, String, Object)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System
public class Object
{


	// RVA: 0x61054f8 VA: 0x759871d4f8
	public virtual Boolean Equals(Object obj) { }
	// RVA: 0x6105504 VA: 0x759871d504
	public static Boolean Equals(Object objA, Object objB) { }
	// RVA: 0x60f7530 VA: 0x759870f530
	public Void .ctor() { }
	// RVA: 0x6105530 VA: 0x759871d530
	protected virtual Void Finalize() { }
	// RVA: 0x6105534 VA: 0x759871d534
	public virtual Int32 GetHashCode() { }
	// RVA: 0x60f7d28 VA: 0x759870fd28
	public Type GetType() { }
	// RVA: 0x60ff924 VA: 0x7598717924
	protected Object MemberwiseClone() { }
	// RVA: 0x610553c VA: 0x759871d53c
	public virtual String ToString() { }
	// RVA: 0x610555c VA: 0x759871d55c
	public static Boolean ReferenceEquals(Object objA, Object objB) { }
	// RVA: 0x6105538 VA: 0x759871d538
	internal static Int32 InternalGetHashCode(Object o) { }
	// RVA: 0x6105568 VA: 0x759871d568
	private Void FieldGetter(String typeName, String fieldName, ref Object val) { }
	// RVA: 0x610556c VA: 0x759871d56c
	private Void FieldSetter(String typeName, String fieldName, Object val) { }
}
```