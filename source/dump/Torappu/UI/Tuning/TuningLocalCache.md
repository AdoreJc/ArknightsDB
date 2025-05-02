# TuningLocalCache

**Namespace:** `Torappu.UI.Tuning`


## Methods

- `ActData _EnsureMemCacheData()`

- `ActData _EnsureActCacheData(String)`

- `DataInAct _GetDataInAct(String)`

- `Void _SaveData(ActData)`

- `Boolean CheckTuningInvestUnhandledIndex(String, String, String)`

- `Int32 GetTuningInvestUnhandledIndex(String, String, String)`

- `Void SetTuningInvestUnhandledIndex(String, String, String, Int32)`

- `Void ConsumeTuningInvestUnhandledIndex(String, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningLocalCache : Singleton`1
{
	private Data`1 m_memData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0__EnsureMemCacheData; // 0x8
	private static DelegateBridge __Hotfix0__EnsureActCacheData; // 0x10
	private static DelegateBridge __Hotfix0__GetDataInAct; // 0x18
	private static DelegateBridge __Hotfix0__SaveData; // 0x20
	private static DelegateBridge __Hotfix0_CheckTuningInvestUnhandledIndex; // 0x28
	private static DelegateBridge __Hotfix0_GetTuningInvestUnhandledIndex; // 0x30
	private static DelegateBridge __Hotfix0_SetTuningInvestUnhandledIndex; // 0x38
	private static DelegateBridge __Hotfix0_ConsumeTuningInvestUnhandledIndex; // 0x40


	// RVA: 0x232b570 VA: 0x7594943570
	private Void .ctor() { }
	// RVA: 0x232b600 VA: 0x7594943600
	private ActData _EnsureMemCacheData() { }
	// RVA: 0x232b764 VA: 0x7594943764
	private ActData _EnsureActCacheData(String actId) { }
	// RVA: 0x232b944 VA: 0x7594943944
	private DataInAct _GetDataInAct(String actId) { }
	// RVA: 0x232ba88 VA: 0x7594943a88
	private Void _SaveData(ActData data) { }
	// RVA: 0x232bb34 VA: 0x7594943b34
	public Boolean CheckTuningInvestUnhandledIndex(String actId, String groupId, String investId) { }
	// RVA: 0x232bc60 VA: 0x7594943c60
	public Int32 GetTuningInvestUnhandledIndex(String actId, String groupId, String investId) { }
	// RVA: 0x232bd98 VA: 0x7594943d98
	public Void SetTuningInvestUnhandledIndex(String actId, String groupId, String investId, Int32 index) { }
	// RVA: 0x232bf7c VA: 0x7594943f7c
	public Void ConsumeTuningInvestUnhandledIndex(String actId, String groupId) { }
}
```