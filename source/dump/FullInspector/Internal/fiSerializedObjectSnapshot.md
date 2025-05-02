# fiSerializedObjectSnapshot

**Namespace:** `FullInspector.Internal`


## Properties

- `Boolean IsEmpty`


## Methods

- `Void RestoreSnapshot(ISerializedObject)`

- `Boolean get_IsEmpty()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : FullInspector.Internal
public class fiSerializedObjectSnapshot
{
	private readonly List`1 _keys; // 0x10
	private readonly List`1 _values; // 0x18
	private readonly List`1 _objectReferences; // 0x20

	public Boolean IsEmpty { get; }

	// RVA: 0x34e3bb0 VA: 0x7595afbbb0
	public Void .ctor(ISerializedObject obj) { }
	// RVA: 0x34e3e14 VA: 0x7595afbe14
	public Void RestoreSnapshot(ISerializedObject target) { }
	// RVA: 0x34e4094 VA: 0x7595afc094
	public Boolean get_IsEmpty() { }
	// RVA: 0x34e40fc VA: 0x7595afc0fc
	public override Boolean Equals(Object obj) { }
	// RVA: 0x34e41e8 VA: 0x7595afc1e8
	public override Int32 GetHashCode() { }
	// RVA: 0x34e4270 VA: 0x7595afc270
	public static Boolean op_Equality(fiSerializedObjectSnapshot a, fiSerializedObjectSnapshot b) { }
	// RVA: 0x34e4278 VA: 0x7595afc278
	public static Boolean op_Inequality(fiSerializedObjectSnapshot a, fiSerializedObjectSnapshot b) { }
	// RVA: 0x VA: 0x0
	private static Boolean AreEqual(List`1 a, List`1 b) { }
}
```