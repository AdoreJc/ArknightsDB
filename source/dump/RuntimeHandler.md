# RuntimeHandler

**Namespace:** ` `


## Fields

- `InternalId m_id`

- `MonoBehaviour m_fakeHost`


## Properties

- `InternalId id`

- `MonoBehaviour fakeHost`


## Methods

- `InternalId get_id()`

- `MonoBehaviour get_fakeHost()`

- `Void Stop()`

- `Boolean IsFinished()`

- `Boolean MoveNext()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class RuntimeHandler
{
	private InternalId m_id; // 0x10
	private MonoBehaviour m_fakeHost; // 0x18
	private Stack`1 m_routines; // 0x20

	public InternalId id { get; }
	public MonoBehaviour fakeHost { get; }

	// RVA: 0x3f66d10 VA: 0x759657ed10
	public InternalId get_id() { }
	// RVA: 0x3f66d18 VA: 0x759657ed18
	public MonoBehaviour get_fakeHost() { }
	// RVA: 0x3f66868 VA: 0x759657e868
	public Void .ctor(InternalId id, MonoBehaviour fakeHost, IEnumerator routine) { }
	// RVA: 0x3f665dc VA: 0x759657e5dc
	public Void Stop() { }
	// RVA: 0x3f66d30 VA: 0x759657ed30
	public Boolean IsFinished() { }
	// RVA: 0x3f66318 VA: 0x759657e318
	public Boolean MoveNext() { }
}
```