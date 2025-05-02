# LicenseContext

**Namespace:** `System.ComponentModel`


## Dump
```C#
// Dll : System.dll
// Namespace : System.ComponentModel
public class LicenseContext : IServiceProvider
{

	public virtual LicenseUsageMode UsageMode { get; }

	// RVA: 0x63c54b4 VA: 0x75989dd4b4
	public virtual LicenseUsageMode get_UsageMode() { }
	// RVA: 0x63c54bc VA: 0x75989dd4bc
	public virtual String GetSavedLicenseKey(Type type, Assembly resourceAssembly) { }
	// RVA: 0x63c54c4 VA: 0x75989dd4c4
	public virtual Object GetService(Type type) { }
	// RVA: 0x63c54cc VA: 0x75989dd4cc
	public virtual Void SetSavedLicenseKey(Type type, String key) { }
	// RVA: 0x63c54d0 VA: 0x75989dd4d0
	public Void .ctor() { }
}
```