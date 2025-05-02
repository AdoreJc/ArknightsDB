# TorappuMemoryPool

**Namespace:** `Torappu`


## Methods

- `Void DeleteGroup(String)`

- `Void MarkGlobalFlag(Int32)`

- `Boolean ConsumeGlobalFlag(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class TorappuMemoryPool : Singleton`1
{
	private const Int32 DEFAULT_CAPACITY; // 0x0
	private ListSet`1 m_globalFlags; // 0x10
	private ListDict`2 m_cacheGroup; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_RequestGroup; // 0x8
	private static DelegateBridge __Hotfix0_DeleteGroup; // 0x10
	private static DelegateBridge __Hotfix0_MarkGlobalFlag; // 0x18
	private static DelegateBridge __Hotfix0_ConsumeGlobalFlag; // 0x20


	// RVA: 0x310a99c VA: 0x759572299c
	private Void .ctor() { }
	// RVA: 0x310aad0 VA: 0x7595722ad0
	public LRUCache`2 RequestGroup(String group, Int32 capacity) { }
	// RVA: 0x310ac2c VA: 0x7595722c2c
	public Void DeleteGroup(String group) { }
	// RVA: 0x310accc VA: 0x7595722ccc
	public Void MarkGlobalFlag(Int32 flag) { }
	// RVA: 0x310ad6c VA: 0x7595722d6c
	public Boolean ConsumeGlobalFlag(Int32 flag) { }
}
```