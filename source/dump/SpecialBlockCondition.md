# SpecialBlockCondition

**Namespace:** ` `


## Fields

- `Type _type`


## Properties

- `Boolean filterBuffKeyPairs`

- `Boolean filterTags`


## Methods

- `Void SetCondition(Type, BuffKeyPair[], String[])`

- `Boolean get_filterBuffKeyPairs()`

- `Boolean get_filterTags()`

- `Boolean CheckBlockable(Character, Entity)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SpecialBlockCondition
{
	private Type _type; // 0x10
	private BuffKeyPair[] _buffKeyPairs; // 0x18
	private String[] _filterTags; // 0x20

	private Boolean filterBuffKeyPairs { get; }
	private Boolean filterTags { get; }

	// RVA: 0x1c1850c VA: 0x759423050c
	public Void SetCondition(Type type, BuffKeyPair[] buffKeyPairs, String[] filterTags) { }
	// RVA: 0x1c18544 VA: 0x7594230544
	private Boolean get_filterBuffKeyPairs() { }
	// RVA: 0x1c18558 VA: 0x7594230558
	private Boolean get_filterTags() { }
	// RVA: 0x1c18568 VA: 0x7594230568
	public Boolean CheckBlockable(Character blocker, Entity blockee) { }
	// RVA: 0x1c188d0 VA: 0x75942308d0
	public Void .ctor() { }
}
```