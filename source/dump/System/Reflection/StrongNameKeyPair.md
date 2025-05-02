# StrongNameKeyPair

**Namespace:** `System.Reflection`


## Fields

- `String _keyPairContainer`

- `Boolean _keyPairExported`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Reflection
public class StrongNameKeyPair : ISerializable, IDeserializationCallback
{
	private Byte[] _publicKey; // 0x10
	private String _keyPairContainer; // 0x18
	private Boolean _keyPairExported; // 0x20
	private Byte[] _keyPairArray; // 0x28


	// RVA: 0x5ff8edc VA: 0x7598610edc
	protected Void .ctor(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x5ff910c VA: 0x759861110c
	private Void System.Runtime.Serialization.ISerializable.GetObjectData(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x5ff9254 VA: 0x7598611254
	private Void System.Runtime.Serialization.IDeserializationCallback.OnDeserialization(Object sender) { }
}
```