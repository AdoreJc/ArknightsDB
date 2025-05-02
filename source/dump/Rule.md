# Rule

**Namespace:** ` `


## Fields

- `String regex`

- `String pattern`

- `Regex m_regex`


## Methods

- `Boolean IsEmpty()`

- `String ExtractTag(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class Rule
{
	public String regex; // 0x10
	public String pattern; // 0x18
	private Regex m_regex; // 0x20


	// RVA: 0x21c0984 VA: 0x75947d8984
	public Boolean IsEmpty() { }
	// RVA: 0x21c0ab0 VA: 0x75947d8ab0
	public String ExtractTag(String assetPath) { }
	// RVA: 0x21c0d8c VA: 0x75947d8d8c
	public Void .ctor() { }
}
```