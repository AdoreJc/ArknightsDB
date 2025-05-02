# NameValueSectionHandler

**Namespace:** `System.Configuration`


## Methods

- `Object Create(Object, Object, XmlNode)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Configuration
public class NameValueSectionHandler : IConfigurationSectionHandler
{

	protected virtual String KeyAttributeName { get; }
	protected virtual String ValueAttributeName { get; }

	// RVA: 0x636aac0 VA: 0x7598982ac0
	public Void .ctor() { }
	// RVA: 0x636aaf8 VA: 0x7598982af8
	protected virtual String get_KeyAttributeName() { }
	// RVA: 0x636ab30 VA: 0x7598982b30
	protected virtual String get_ValueAttributeName() { }
	// RVA: 0x636ab68 VA: 0x7598982b68
	public Object Create(Object parent, Object context, XmlNode section) { }
}
```