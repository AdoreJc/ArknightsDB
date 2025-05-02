# ZoneHomeRoguelikeEntryItemModel

**Namespace:** `Torappu.UI.Stage`


## Fields

- `ZoneHomeEntryLockInfo m_lockInfo`

- `String <topicId>k__BackingField`


## Properties

- `String topicId`


## Methods

- `String get_topicId()`

- `Void set_topicId(String)`

- `ZoneHomeEntryLockInfo <>xLuaBaseProxy_GetLockInfo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class ZoneHomeRoguelikeEntryItemModel : ZoneHomeEntryItemModel
{
	private ZoneHomeEntryLockInfo m_lockInfo; // 0x40
	private String <topicId>k__BackingField; // 0x58
	private static DelegateBridge __Hotfix0_get_topicId; // 0x0
	private static DelegateBridge __Hotfix0_set_topicId; // 0x8
	private static DelegateBridge __Hotfix0_GetLockInfo; // 0x10
	private static DelegateBridge __Hotfix0__CheckIfIsTopic; // 0x18
	private static DelegateBridge __Hotfix0_CreateEntryModel; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public String topicId { get; set; }

	// RVA: 0x2f01f80 VA: 0x7595519f80
	public String get_topicId() { }
	// RVA: 0x2f01fe8 VA: 0x7595519fe8
	private Void set_topicId(String value) { }
	// RVA: 0x2f0206c VA: 0x759551a06c
	public override ZoneHomeEntryLockInfo GetLockInfo() { }
	// RVA: 0x2f020fc VA: 0x759551a0fc
	private static Boolean _CheckIfIsTopic(RoguelikeTopicBasicData topicBasicData, String displayId, Int64 curTs) { }
	// RVA: 0x2f02250 VA: 0x759551a250
	public static ZoneHomeRoguelikeEntryItemModel CreateEntryModel(StageStateBean stateBean, ActivityThemeData rogueTheme, Int64 curTs) { }
	// RVA: 0x2f025e0 VA: 0x759551a5e0
	public Void .ctor() { }
	// RVA: 0x2f02650 VA: 0x759551a650
	private ZoneHomeEntryLockInfo <>xLuaBaseProxy_GetLockInfo() { }
}
```