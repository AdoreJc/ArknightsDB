# RefCountReference

**Namespace:** `Torappu`


## Fields

- `Int64 m_signature`

- `Int32 m_selfRefCount`


## Methods

- `Void Attach(IRefCountInstance)`

- `Void Detach(IRefCountInstance)`

- `Void Unreference(IRefCountInstance)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class RefCountReference
{
	private Int64 m_signature; // 0x10
	private Int32 m_selfRefCount; // 0x18


	// RVA: 0x310590c VA: 0x759571d90c
	public Void Attach(IRefCountInstance inst) { }
	// RVA: 0x3105a90 VA: 0x759571da90
	public Void Detach(IRefCountInstance inst) { }
	// RVA: 0x3105bbc VA: 0x759571dbbc
	public Void Unreference(IRefCountInstance inst) { }
	// RVA: 0x3105ce0 VA: 0x759571dce0
	public Void .ctor() { }
}
```