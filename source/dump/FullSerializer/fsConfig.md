# fsConfig

**Namespace:** `FullSerializer`


## Fields

- `fsMemberSerialization DefaultMemberSerialization`

- `Boolean SerializeNonAutoProperties`

- `Boolean SerializeNonPublicSetProperties`

- `String CustomDateTimeFormatString`

- `Boolean Serialize64BitIntegerAsString`

- `Boolean SerializeEnumsAsInteger`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : FullSerializer
public class fsConfig
{
	public Type[] SerializeAttributes; // 0x10
	public Type[] IgnoreSerializeAttributes; // 0x18
	public fsMemberSerialization DefaultMemberSerialization; // 0x20
	public Func`3 GetJsonNameFromMemberName; // 0x28
	public Boolean SerializeNonAutoProperties; // 0x30
	public Boolean SerializeNonPublicSetProperties; // 0x31
	public String CustomDateTimeFormatString; // 0x38
	public Boolean Serialize64BitIntegerAsString; // 0x40
	public Boolean SerializeEnumsAsInteger; // 0x41


	// RVA: 0x3496884 VA: 0x7595aae884
	public Void .ctor() { }
}
```