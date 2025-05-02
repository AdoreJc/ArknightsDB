# PhaseData

**Namespace:** ` `


## Fields

- `Single preDelay`


## Methods

- `Int32 GetEnemiesCnt()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class PhaseData
{
	public Single preDelay; // 0x10
	public ActionData[] actions; // 0x18
	private readonly Dictionary`2 m_randomActionGroups; // 0x20
	private readonly List`1 m_actionWithRandomSpawn; // 0x28
	private readonly HashSet`1 m_validActionPackKeys; // 0x30

	private Dictionary`2 randomActionGroups { get; }

	// RVA: 0x34a4380 VA: 0x7595abc380
	private Dictionary`2 get_randomActionGroups() { }
	// RVA: 0x34a4610 VA: 0x7595abc610
	public List`1 FetchActionsWithRandomSpawn(Boolean refreshResult) { }
	// RVA: 0x34a4a18 VA: 0x7595abca18
	public Int32 GetEnemiesCnt() { }
	// RVA: 0x34a4a74 VA: 0x7595abca74
	public Void .ctor() { }
}
```