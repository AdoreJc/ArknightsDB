# SoapAttribute

**Namespace:** `System.Runtime.Remoting.Metadata`


## Fields

- `Boolean _useAttribute`

- `String ProtXmlNamespace`

- `Object ReflectInfo`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting.Metadata
public class SoapAttribute : Attribute
{
	private Boolean _useAttribute; // 0x10
	protected String ProtXmlNamespace; // 0x18
	protected Object ReflectInfo; // 0x20

	public virtual Boolean UseAttribute { get; }
	public virtual String XmlNamespace { get; }

	// RVA: 0x5f9e92c VA: 0x75985b692c
	public Void .ctor() { }
	// RVA: 0x5f9e934 VA: 0x75985b6934
	public virtual Boolean get_UseAttribute() { }
	// RVA: 0x5f9e93c VA: 0x75985b693c
	public virtual String get_XmlNamespace() { }
	// RVA: 0x5f9e944 VA: 0x75985b6944
	internal virtual Void SetReflectionObject(Object reflectionObject) { }
}
```