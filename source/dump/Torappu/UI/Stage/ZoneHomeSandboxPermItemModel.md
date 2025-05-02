# ZoneHomeSandboxPermItemModel

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
public class ZoneHomeSandboxPermItemModel : ZoneHomeEntryItemModel, IHotfixable
{
	private ZoneHomeEntryLockInfo m_lockInfo; // 0x40
	private String <topicId>k__BackingField; // 0x58
	private static DelegateBridge __Hotfix0_get_topicId; // 0x0
	private static DelegateBridge __Hotfix0_set_topicId; // 0x8
	private static DelegateBridge __Hotfix0_CreateEntryModel; // 0x10
	private static DelegateBridge __Hotfix0_GetLockInfo; // 0x18
	private static DelegateBridge __Hotfix0__CheckIfIsTopic; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public String topicId { get; set; }

	// RVA: 0x2f02684 VA: 0x759551a684
	public String get_topicId() { }
	// RVA: 0x2f026ec VA: 0x759551a6ec
	private Void set_topicId(String value) { }
	// RVA: 0x2f02770 VA: 0x759551a770
	public static ZoneHomeSandboxPermItemModel CreateEntryModel(ActivityThemeData sandboxTheme, Int64 currTs) { }
	// RVA: 0x2f02c88 VA: 0x759551ac88
	public override ZoneHomeEntryLockInfo GetLockInfo() { }
	// RVA: 0x2f02acc VA: 0x759551aacc
	private static Boolean _CheckIfIsTopic(SandboxPermBasicData basicData, String displayId, Int64 currTs) { }
	// RVA: 0x2f02c18 VA: 0x759551ac18
	public Void .ctor() { }
	// RVA: 0x2f02d18 VA: 0x759551ad18
	private ZoneHomeEntryLockInfo <>xLuaBaseProxy_GetLockInfo() { }
}
```