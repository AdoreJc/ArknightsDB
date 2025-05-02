# SecurityException

**Namespace:** `System.Security`


## Fields

- `String permissionState`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Security
public class SecurityException : SystemException
{
	private String permissionState; // 0x90


	// RVA: 0x5f43780 VA: 0x759855b780
	public Void .ctor() { }
	// RVA: 0x5f437e8 VA: 0x759855b7e8
	public Void .ctor(String message) { }
	// RVA: 0x5f4380c VA: 0x759855b80c
	protected Void .ctor(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x5f43938 VA: 0x759855b938
	public Void .ctor(String message, Exception inner) { }
	// RVA: 0x5f4395c VA: 0x759855b95c
	public override Void GetObjectData(SerializationInfo info, StreamingContext context) { }
	// RVA: 0x5f43a5c VA: 0x759855ba5c
	public override String ToString() { }
}
```