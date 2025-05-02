# AttributeMetaAttribute

**Namespace:** `Torappu`


## Fields

- `AttributeType Attribute`

- `Boolean KeepLowerValue`

- `Single m_min`

- `Single m_max`

- `Boolean m_hasMin`

- `Boolean m_hasMax`


## Methods

- `Single GetMinAsFloat()`

- `Single GetMaxAsFloat()`

- `TSVector2 GetRangeAsTVector2()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class AttributeMetaAttribute : Attribute
{
	public AttributeType Attribute; // 0x10
	public Boolean KeepLowerValue; // 0x14
	private Single m_min; // 0x18
	private Single m_max; // 0x1c
	private Boolean m_hasMin; // 0x20
	private Boolean m_hasMax; // 0x21


	// RVA: 0x33bf56c VA: 0x75959d756c
	public Void .ctor() { }
	// RVA: 0x33bf580 VA: 0x75959d7580
	public Void .ctor(AttributeType attribute) { }
	// RVA: 0x33bf5b4 VA: 0x75959d75b4
	public Void .ctor(AttributeType attribute, Single min) { }
	// RVA: 0x33bf600 VA: 0x75959d7600
	public Void .ctor(AttributeType attribute, Single min, Single max) { }
	// RVA: 0x33bf650 VA: 0x75959d7650
	public Single GetMinAsFloat() { }
	// RVA: 0x33bf658 VA: 0x75959d7658
	public Single GetMaxAsFloat() { }
	// RVA: 0x33bf660 VA: 0x75959d7660
	public TSVector2 GetRangeAsTVector2() { }
}
```