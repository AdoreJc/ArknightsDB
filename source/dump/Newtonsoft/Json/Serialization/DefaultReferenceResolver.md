# DefaultReferenceResolver

**Namespace:** `Newtonsoft.Json.Serialization`


## Fields

- `Int32 _referenceCount`


## Methods

- `Object ResolveReference(Object, String)`

- `String GetReference(Object, Object)`

- `Void AddReference(Object, String, Object)`

- `Boolean IsReferenced(Object, Object)`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Serialization
internal class DefaultReferenceResolver : IReferenceResolver
{
	private Int32 _referenceCount; // 0x10


	// RVA: 0x6166c80 VA: 0x759877ec80
	private BidirectionalDictionary`2 GetMappings(Object context) { }
	// RVA: 0x6166d94 VA: 0x759877ed94
	public Object ResolveReference(Object context, String reference) { }
	// RVA: 0x6166e08 VA: 0x759877ee08
	public String GetReference(Object context, Object value) { }
	// RVA: 0x6166efc VA: 0x759877eefc
	public Void AddReference(Object context, String reference, Object value) { }
	// RVA: 0x6166f68 VA: 0x759877ef68
	public Boolean IsReferenced(Object context, Object value) { }
	// RVA: 0x6166fdc VA: 0x759877efdc
	public Void .ctor() { }
}
```