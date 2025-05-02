# BankTrieMap

**Namespace:** `Torappu.Audio.Middleware.Data`


## Fields

- `TrieNode m_root`


## Methods

- `Void Add(String, Bank)`

- `Boolean TryGet(String, out)`

- `Boolean TryGet(String, String, out)`

- `Void Clear()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Audio.Middleware.Data
public class BankTrieMap
{
	private const Int32 SEPARATOR_CHAR; // 0x0
	private const Int32 ALPHABET_SIZE; // 0x0
	private TrieNode m_root; // 0x10


	// RVA: 0x3ee019c VA: 0x75964f819c
	public Void Add(String key, Bank bank) { }
	// RVA: 0x3ee03d0 VA: 0x75964f83d0
	public Boolean TryGet(String key, out Bank bank) { }
	// RVA: 0x3ee0488 VA: 0x75964f8488
	public Boolean TryGet(String key1, String key2, out Bank bank) { }
	// RVA: 0x3ee05d4 VA: 0x75964f85d4
	public Void Clear() { }
	// RVA: 0x3ee063c VA: 0x75964f863c
	public Void .ctor() { }
}
```