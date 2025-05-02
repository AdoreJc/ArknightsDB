# MemCache

**Namespace:** ` `


## Fields

- `String uid`

- `String sessionId`

- `RecentBattleCache recentBattleCache`


## Methods

- `Boolean IsValid(String, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class MemCache : IHotfixable
{
	public String uid; // 0x10
	public String sessionId; // 0x18
	public Dictionary`2 stageCache; // 0x20
	public Dictionary`2 zoneCache; // 0x28
	public RecentBattleCache recentBattleCache; // 0x30
	private static DelegateBridge __Hotfix0_IsValid; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2270d60 VA: 0x7594888d60
	public Boolean IsValid(String uid, String sessionId) { }
	// RVA: 0x2270e14 VA: 0x7594888e14
	public Void .ctor() { }
}
```