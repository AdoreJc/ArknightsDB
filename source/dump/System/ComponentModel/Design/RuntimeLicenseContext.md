# RuntimeLicenseContext

**Namespace:** `System.ComponentModel.Design`


## Methods

- `String GetLocalPath(String)`

- `Stream CaseInsensitiveManifestResourceStreamLookup(Assembly, String)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.ComponentModel.Design
internal class RuntimeLicenseContext : LicenseContext
{
	private static TraceSwitch s_runtimeLicenseContextSwitch; // 0x0
	internal Hashtable savedLicenseKeys; // 0x10


	// RVA: 0x64092c8 VA: 0x7598a212c8
	private String GetLocalPath(String fileName) { }
	// RVA: 0x6409350 VA: 0x7598a21350
	public override String GetSavedLicenseKey(Type type, Assembly resourceAssembly) { }
	// RVA: 0x6409898 VA: 0x7598a21898
	private Stream CaseInsensitiveManifestResourceStreamLookup(Assembly satellite, String name) { }
	// RVA: 0x6409c78 VA: 0x7598a21c78
	public Void .ctor() { }
	// RVA: 0x6409c80 VA: 0x7598a21c80
	private static Void .cctor() { }
}
```