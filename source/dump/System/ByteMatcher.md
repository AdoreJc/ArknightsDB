# ByteMatcher

**Namespace:** `System`


## Fields

- `Hashtable map`

- `Hashtable starts`


## Methods

- `Void AddMapping(TermInfoStrings, Byte[])`

- `Void Sort()`

- `Boolean StartsWith(Int32)`

- `TermInfoStrings Match(Char[], Int32, Int32, out)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System
internal class ByteMatcher
{
	private Hashtable map; // 0x10
	private Hashtable starts; // 0x18


	// RVA: 0x610b918 VA: 0x7598723918
	public Void AddMapping(TermInfoStrings key, Byte[] val) { }
	// RVA: 0x610ba38 VA: 0x7598723a38
	public Void Sort() { }
	// RVA: 0x61088b4 VA: 0x75987208b4
	public Boolean StartsWith(Int32 c) { }
	// RVA: 0x610893c VA: 0x759872093c
	public TermInfoStrings Match(Char[] buffer, Int32 offset, Int32 length, out Int32 used) { }
	// RVA: 0x610b83c VA: 0x759872383c
	public Void .ctor() { }
}
```