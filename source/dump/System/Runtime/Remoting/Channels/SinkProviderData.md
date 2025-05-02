# SinkProviderData

**Namespace:** `System.Runtime.Remoting.Channels`


## Fields

- `String sinkName`

- `ArrayList children`

- `Hashtable properties`


## Properties

- `IList Children`

- `IDictionary Properties`


## Methods

- `IList get_Children()`

- `IDictionary get_Properties()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting.Channels
public class SinkProviderData
{
	private String sinkName; // 0x10
	private ArrayList children; // 0x18
	private Hashtable properties; // 0x20

	public IList Children { get; }
	public IDictionary Properties { get; }

	// RVA: 0x5f9cdf4 VA: 0x75985b4df4
	public Void .ctor(String name) { }
	// RVA: 0x5f9cec0 VA: 0x75985b4ec0
	public IList get_Children() { }
	// RVA: 0x5f9cec8 VA: 0x75985b4ec8
	public IDictionary get_Properties() { }
}
```