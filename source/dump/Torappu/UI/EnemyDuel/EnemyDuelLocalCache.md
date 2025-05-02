# EnemyDuelLocalCache

**Namespace:** `Torappu.UI.EnemyDuel`


## Methods

- `ActData _EnsureMemCacheData()`

- `ActData _EnsureActCacheData(String)`

- `DataInAct _GetDataInAct(String)`

- `Void _SaveData(ActData)`

- `String GetLastUseEmoticonId(String)`

- `Void SaveLastUseEmoticonThemeId(String, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelLocalCache : Singleton`1
{
	private Data`1 m_memData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0__EnsureMemCacheData; // 0x8
	private static DelegateBridge __Hotfix0__EnsureActCacheData; // 0x10
	private static DelegateBridge __Hotfix0__GetDataInAct; // 0x18
	private static DelegateBridge __Hotfix0__SaveData; // 0x20
	private static DelegateBridge __Hotfix0_GetLastUseEmoticonId; // 0x28
	private static DelegateBridge __Hotfix0_SaveLastUseEmoticonThemeId; // 0x30


	// RVA: 0x2942fdc VA: 0x7594f5afdc
	private Void .ctor() { }
	// RVA: 0x294306c VA: 0x7594f5b06c
	private ActData _EnsureMemCacheData() { }
	// RVA: 0x29431d0 VA: 0x7594f5b1d0
	private ActData _EnsureActCacheData(String actId) { }
	// RVA: 0x29433b0 VA: 0x7594f5b3b0
	private DataInAct _GetDataInAct(String actId) { }
	// RVA: 0x29434f4 VA: 0x7594f5b4f4
	private Void _SaveData(ActData data) { }
	// RVA: 0x29435a0 VA: 0x7594f5b5a0
	public String GetLastUseEmoticonId(String actId) { }
	// RVA: 0x294362c VA: 0x7594f5b62c
	public Void SaveLastUseEmoticonThemeId(String actId, String emoticonThemeId) { }
}
```