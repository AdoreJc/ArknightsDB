# ObjectHolderListEnumerator

**Namespace:** `System.Runtime.Serialization`


## Fields

- `Boolean m_isFixupEnumerator`

- `ObjectHolderList m_list`

- `Int32 m_startingVersion`

- `Int32 m_currPos`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Serialization
internal class ObjectHolderListEnumerator
{
	private Boolean m_isFixupEnumerator; // 0x10
	private ObjectHolderList m_list; // 0x18
	private Int32 m_startingVersion; // 0x20
	private Int32 m_currPos; // 0x24

	internal ObjectHolder Current { get; }

	// RVA: 0x5fb6cc4 VA: 0x75985cecc4
	internal Void .ctor(ObjectHolderList list, Boolean isFixupEnumerator) { }
	// RVA: 0x5fb5acc VA: 0x75985cdacc
	internal Boolean MoveNext() { }
	// RVA: 0x5fb5a74 VA: 0x75985cda74
	internal ObjectHolder get_Current() { }
}
```