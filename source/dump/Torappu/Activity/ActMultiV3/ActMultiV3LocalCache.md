# ActMultiV3LocalCache

**Namespace:** `Torappu.Activity.ActMultiV3`


## Methods

- `ActData _EnsureMemCacheData()`

- `ActData _EnsureActCacheData(String)`

- `DataInAct _GetDataInAct(String)`

- `Void _SaveData(ActData)`

- `String LoadSelectSquadId(String)`

- `Void SaveSelectSquadId(String, String)`

- `String GetLastUseEmoticonId(String, EmojiSceneType)`

- `Void SaveLastUseEmoticonThemeId(String, String, EmojiSceneType)`

- `Boolean _TryGetLastUseEmoticonThemeGroup(List`1, EmojiSceneType, out)`

- `ManualTabType GetLastSelectedManualTab(String)`

- `Void SaveLastSelectedManualTab(String, ManualTabType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3LocalCache : Singleton`1
{
	private Data`1 m_memData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0__EnsureMemCacheData; // 0x8
	private static DelegateBridge __Hotfix0__EnsureActCacheData; // 0x10
	private static DelegateBridge __Hotfix0__GetDataInAct; // 0x18
	private static DelegateBridge __Hotfix0__SaveData; // 0x20
	private static DelegateBridge __Hotfix0_LoadSelectSquadId; // 0x28
	private static DelegateBridge __Hotfix0_SaveSelectSquadId; // 0x30
	private static DelegateBridge __Hotfix0_GetLastUseEmoticonId; // 0x38
	private static DelegateBridge __Hotfix0_SaveLastUseEmoticonThemeId; // 0x40
	private static DelegateBridge __Hotfix0__TryGetLastUseEmoticonThemeGroup; // 0x48
	private static DelegateBridge __Hotfix0_GetLastSelectedManualTab; // 0x50
	private static DelegateBridge __Hotfix0_SaveLastSelectedManualTab; // 0x58


	// RVA: 0x30da804 VA: 0x75956f2804
	private Void .ctor() { }
	// RVA: 0x30da894 VA: 0x75956f2894
	private ActData _EnsureMemCacheData() { }
	// RVA: 0x30da9f8 VA: 0x75956f29f8
	private ActData _EnsureActCacheData(String actId) { }
	// RVA: 0x30dabd8 VA: 0x75956f2bd8
	private DataInAct _GetDataInAct(String actId) { }
	// RVA: 0x30dad1c VA: 0x75956f2d1c
	private Void _SaveData(ActData data) { }
	// RVA: 0x30dadc8 VA: 0x75956f2dc8
	public String LoadSelectSquadId(String actId) { }
	// RVA: 0x30dae54 VA: 0x75956f2e54
	public Void SaveSelectSquadId(String actId, String squadId) { }
	// RVA: 0x30daf28 VA: 0x75956f2f28
	public String GetLastUseEmoticonId(String actId, EmojiSceneType sceneType) { }
	// RVA: 0x30db2f0 VA: 0x75956f32f0
	public Void SaveLastUseEmoticonThemeId(String actId, String emoticonThemeId, EmojiSceneType sceneType) { }
	// RVA: 0x30db018 VA: 0x75956f3018
	private Boolean _TryGetLastUseEmoticonThemeGroup(List`1 themeIdGroups, EmojiSceneType sceneType, out EmoticonLastUseThemeIdGroup themeGroup) { }
	// RVA: 0x30db510 VA: 0x75956f3510
	public ManualTabType GetLastSelectedManualTab(String actId) { }
	// RVA: 0x30db59c VA: 0x75956f359c
	public Void SaveLastSelectedManualTab(String actId, ManualTabType selectedManualTabType) { }
}
```