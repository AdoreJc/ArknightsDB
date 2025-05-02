# Act42D0LocalCache

**Namespace:** `Torappu.Activity.Act42D0`


## Methods

- `ActData _EnsureMemCacheData()`

- `ActData _EnsureActCacheData(String)`

- `DataInAct _GetDataInAct(String)`

- `Void _SaveData(ActData)`

- `Boolean LoadEffectShow(String, String)`

- `Void SaveEffectSelectList(String, String, List`1)`

- `Void SaveEffectShow(String, String, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42D0LocalCache : Singleton`1
{
	private Data`1 m_memData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0__EnsureMemCacheData; // 0x8
	private static DelegateBridge __Hotfix0__EnsureActCacheData; // 0x10
	private static DelegateBridge __Hotfix0__GetDataInAct; // 0x18
	private static DelegateBridge __Hotfix0__SaveData; // 0x20
	private static DelegateBridge __Hotfix0_LoadEffectSelectList; // 0x28
	private static DelegateBridge __Hotfix0_LoadEffectShow; // 0x30
	private static DelegateBridge __Hotfix0_SaveEffectSelectList; // 0x38
	private static DelegateBridge __Hotfix0_SaveEffectShow; // 0x40


	// RVA: 0x31fead0 VA: 0x7595816ad0
	private Void .ctor() { }
	// RVA: 0x31feb60 VA: 0x7595816b60
	private ActData _EnsureMemCacheData() { }
	// RVA: 0x31fecc4 VA: 0x7595816cc4
	private ActData _EnsureActCacheData(String actId) { }
	// RVA: 0x31feea4 VA: 0x7595816ea4
	private DataInAct _GetDataInAct(String actId) { }
	// RVA: 0x31feffc VA: 0x7595816ffc
	private Void _SaveData(ActData data) { }
	// RVA: 0x31ff0a8 VA: 0x75958170a8
	public List`1 LoadEffectSelectList(String actId, String areaId) { }
	// RVA: 0x31ff194 VA: 0x7595817194
	public Boolean LoadEffectShow(String actId, String areaId) { }
	// RVA: 0x31ff284 VA: 0x7595817284
	public Void SaveEffectSelectList(String actId, String areaId, List`1 selectEffect) { }
	// RVA: 0x31ff3f8 VA: 0x75958173f8
	public Void SaveEffectShow(String actId, String areaId, Boolean isShow) { }
}
```