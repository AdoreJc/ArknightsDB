# PersistentResInfo

**Namespace:** `Torappu.Resource`


## Fields

- `String manifestName`

- `String manifestVersion`


## Methods

- `PersistentResInfo ShallowCopy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Resource
public class PersistentResInfo
{
	public String manifestName; // 0x10
	public String manifestVersion; // 0x18
	public List`1 abInfos; // 0x20
	public List`1 delete; // 0x28


	// RVA: 0x373f304 VA: 0x7595d57304
	public PersistentResInfo ShallowCopy() { }
	// RVA: 0x373f454 VA: 0x7595d57454
	public Void .ctor() { }
}
```