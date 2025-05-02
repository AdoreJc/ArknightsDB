# SerializableKV

**Namespace:** ` `


## Fields

- `TKey key`

- `TValue value`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SerializableKV
{
	public TKey key; // 0x0
	public TValue value; // 0x0


	// RVA: 0x VA: 0x0
	public Void .ctor() { }
	// RVA: 0x VA: 0x0
	public Void .ctor(TKey key, TValue value) { }
	// RVA: 0x VA: 0x0
	public override String ToString() { }
	// RVA: 0x VA: 0x0
	public static KeyValuePair`2 op_Implicit(SerializableKV kv) { }
	// RVA: 0x VA: 0x0
	public static SerializableKV op_Implicit(KeyValuePair`2 kv) { }
}
```