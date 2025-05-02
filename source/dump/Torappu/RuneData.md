# RuneData

**Namespace:** `Torappu`


## Fields

- `String key`

- `Selector selector`

- `Blackboard blackboard`

- `Boolean m_inited`


## Methods

- `Void InitIfNot()`

- `RuneData Duplicate()`

- `Void _PopulateAdditionalMasksFromBlackboard()`

- `Void _PopulateAdditionalFiltersFromBlackboard()`

- `Void _PopulateAdditionalFiltersFromBlackboard(String, ref)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class RuneData
{
	public String key; // 0x10
	public Selector selector; // 0x18
	public Blackboard blackboard; // 0x20
	private Boolean m_inited; // 0x28


	// RVA: 0x34b1170 VA: 0x7595ac9170
	public Void InitIfNot() { }
	// RVA: 0x34b1680 VA: 0x7595ac9680
	public RuneData Duplicate() { }
	// RVA: 0x34b1ba8 VA: 0x7595ac9ba8
	public static RuneData CreateFromLegacy(LegacyInLevelRuneData legacyData) { }
	// RVA: 0x34b11a0 VA: 0x7595ac91a0
	private Void _PopulateAdditionalMasksFromBlackboard() { }
	// RVA: 0x34b1444 VA: 0x7595ac9444
	private Void _PopulateAdditionalFiltersFromBlackboard() { }
	// RVA: 0x34b1c44 VA: 0x7595ac9c44
	private Void _PopulateAdditionalFiltersFromBlackboard(String key, ref List`1 filter) { }
	// RVA: 0x34b1754 VA: 0x7595ac9754
	public Void .ctor() { }
}
```