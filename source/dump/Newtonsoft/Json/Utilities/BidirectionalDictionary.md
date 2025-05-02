# BidirectionalDictionary

**Namespace:** `Newtonsoft.Json.Utilities`


## Methods

- `Void Set(TFirst, TSecond)`

- `Boolean TryGetByFirst(TFirst, out)`

- `Boolean TryGetBySecond(TSecond, out)`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Utilities
internal class BidirectionalDictionary`2
{
	private readonly IDictionary`2 _firstToSecond; // 0x0
	private readonly IDictionary`2 _secondToFirst; // 0x0
	private readonly String _duplicateFirstErrorMessage; // 0x0
	private readonly String _duplicateSecondErrorMessage; // 0x0


	// RVA: 0x VA: 0x0
	public Void .ctor() { }
	// RVA: 0x VA: 0x0
	public Void .ctor(IEqualityComparer`1 firstEqualityComparer, IEqualityComparer`1 secondEqualityComparer) { }
	// RVA: 0x VA: 0x0
	public Void .ctor(IEqualityComparer`1 firstEqualityComparer, IEqualityComparer`1 secondEqualityComparer, String duplicateFirstErrorMessage, String duplicateSecondErrorMessage) { }
	// RVA: 0x VA: 0x0
	public Void Set(TFirst first, TSecond second) { }
	// RVA: 0x VA: 0x0
	public Boolean TryGetByFirst(TFirst first, out TSecond second) { }
	// RVA: 0x VA: 0x0
	public Boolean TryGetBySecond(TSecond second, out TFirst first) { }
}
```