# TypeLoadException

**Namespace:** `System`


## Fields

- `String ClassName`

- `String AssemblyName`

- `String MessageArg`


## Methods

- `Void SetMessageField()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System
public class TypeLoadException : SystemException, ISerializable
{
	private String ClassName; // 0x90
	private String AssemblyName; // 0x98
	private String MessageArg; // 0xa0
	internal Int32 ResourceId; // 0xa8

	public override String Message { get; }

	// RVA: 0x60f7efc VA: 0x759870fefc
	public Void .ctor() { }
	// RVA: 0x60f7f5c VA: 0x759870ff5c
	public Void .ctor(String message) { }
	// RVA: 0x60f7f84 VA: 0x759870ff84
	public override String get_Message() { }
	// RVA: 0x60f7f9c VA: 0x759870ff9c
	private Void SetMessageField() { }
	// RVA: 0x60f80d0 VA: 0x75987100d0
	private Void .ctor(String className, String assemblyName) { }
	// RVA: 0x60f80dc VA: 0x75987100dc
	private Void .ctor(String className, String assemblyName, String messageArg, Int32 resourceId) { }
	// RVA: 0x60f8164 VA: 0x7598710164
	protected Void .ctor(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x60f82d0 VA: 0x75987102d0
	public override Void GetObjectData(SerializationInfo info, StreamingContext context) { }
}
```