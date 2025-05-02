# IllogicalCallContext

**Namespace:** `System.Runtime.Remoting.Messaging`


## Fields

- `Hashtable m_Datastore`

- `Object m_HostContext`


## Properties

- `Hashtable Datastore`


## Methods

- `Hashtable get_Datastore()`

- `Void FreeNamedDataSlot(String)`

- `IllogicalCallContext CreateCopy()`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting.Messaging
internal class IllogicalCallContext
{
	private Hashtable m_Datastore; // 0x10
	private Object m_HostContext; // 0x18

	private Hashtable Datastore { get; }
	internal Object HostContext { get; set; }
	internal Boolean HasUserData { get; }

	// RVA: 0x5f9f0c8 VA: 0x75985b70c8
	private Hashtable get_Datastore() { }
	// RVA: 0x5f9f140 VA: 0x75985b7140
	internal Object get_HostContext() { }
	// RVA: 0x5f9f148 VA: 0x75985b7148
	internal Void set_HostContext(Object value) { }
	// RVA: 0x5f9f150 VA: 0x75985b7150
	internal Boolean get_HasUserData() { }
	// RVA: 0x5f9f004 VA: 0x75985b7004
	public Void FreeNamedDataSlot(String name) { }
	// RVA: 0x5f9f17c VA: 0x75985b717c
	public IllogicalCallContext CreateCopy() { }
	// RVA: 0x5f9f3d8 VA: 0x75985b73d8
	public Void .ctor() { }
}
```