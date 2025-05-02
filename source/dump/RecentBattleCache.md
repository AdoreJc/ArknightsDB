# RecentBattleCache

**Namespace:** ` `


## Methods

- `Void RecordLastBattle(RecentBattleRecord)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class RecentBattleCache : IHotfixable
{
	private const Int32 MAX_RECORDS_EACH_TYPE; // 0x0
	private Dictionary`2 m_typeCountMap; // 0x10
	public List`1 records; // 0x18
	private static DelegateBridge __Hotfix0_RecordLastBattle; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2271624 VA: 0x7594889624
	public Void RecordLastBattle(RecentBattleRecord newRecord) { }
	// RVA: 0x227193c VA: 0x759488993c
	public Void .ctor() { }
}
```