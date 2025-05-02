# EnvoyInfo

**Namespace:** `System.Runtime.Remoting`


## Fields

- `IMessageSink envoySinks`


## Properties

- `IMessageSink EnvoySinks`


## Methods

- `IMessageSink get_EnvoySinks()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting
internal class EnvoyInfo : IEnvoyInfo
{
	private IMessageSink envoySinks; // 0x10

	public IMessageSink EnvoySinks { get; }

	// RVA: 0x5f7cc04 VA: 0x7598594c04
	public Void .ctor(IMessageSink sinks) { }
	// RVA: 0x5f7cc34 VA: 0x7598594c34
	public IMessageSink get_EnvoySinks() { }
}
```