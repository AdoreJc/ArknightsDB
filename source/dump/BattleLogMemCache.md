# BattleLogMemCache

**Namespace:** ` `


## Fields

- `UInt32 m_loginHash`


## Methods

- `Void Save(String, BattleLog)`

- `Boolean TryGet(String, out)`

- `Void _UpdateLoginInfoAndAutoClear()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class BattleLogMemCache : IHotfixable
{
	private LRUCache`2 m_cache; // 0x10
	private UInt32 m_loginHash; // 0x18
	private static DelegateBridge __Hotfix0_Save; // 0x0
	private static DelegateBridge __Hotfix0_TryGet; // 0x8
	private static DelegateBridge __Hotfix0__UpdateLoginInfoAndAutoClear; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x216fb38 VA: 0x7594787b38
	public Void Save(String key, BattleLog value) { }
	// RVA: 0x216f8dc VA: 0x75947878dc
	public Boolean TryGet(String key, out BattleLog ret) { }
	// RVA: 0x2171a18 VA: 0x7594789a18
	private Void _UpdateLoginInfoAndAutoClear() { }
	// RVA: 0x21716c0 VA: 0x75947896c0
	public Void .ctor() { }
}
```