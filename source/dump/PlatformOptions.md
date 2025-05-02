# PlatformOptions

**Namespace:** ` `


## Fields

- `Boolean overridePath`

- `FileLocation pathLocation`

- `String path`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : 
public class PlatformOptions
{
	public Boolean overridePath; // 0x10
	public FileLocation pathLocation; // 0x14
	public String path; // 0x18


	// RVA: 0x66846b0 VA: 0x7598c9c6b0
	public virtual Boolean IsModified() { }
	// RVA: 0x66846b8 VA: 0x7598c9c6b8
	public virtual String GetKeyServerURL() { }
	// RVA: 0x66846c0 VA: 0x7598c9c6c0
	public virtual String GetKeyServerAuthToken() { }
	// RVA: 0x66846c8 VA: 0x7598c9c6c8
	public virtual String GetDecryptionKey() { }
	// RVA: 0x66846d0 VA: 0x7598c9c6d0
	protected static String StringAsJsonString(String str) { }
	// RVA: 0x6684ad4 VA: 0x7598c9cad4
	protected static List`1 ParseJsonHTTPHeadersIntoHTTPHeaderList(String httpHeaderJson) { }
	// RVA: 0x6684edc VA: 0x7598c9cedc
	public Void .ctor() { }
}
```