# RoguelikeTopicDB

**Namespace:** `Torappu`


## Methods

- `String GetItemIcon(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class RoguelikeTopicDB : ConstTable`2
{
	private Dictionary`2 m_itemId2ItemIcon; // 0x60
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_GetItemIcon; // 0x8
	private static DelegateBridge __Hotfix0_TryGetArchiveCompData; // 0x10
	private static DelegateBridge __Hotfix0_TryGetItem; // 0x18
	private static DelegateBridge __Hotfix0_TryGetTask; // 0x20
	private static DelegateBridge __Hotfix0_GetArchiveChatGroupOrDetail; // 0x28
	private static DelegateBridge __Hotfix0_GetPrevNearestMonthRefreshTimeData; // 0x30
	private static DelegateBridge __Hotfix0_GetOpenTimeByEnrollId; // 0x38
	private static DelegateBridge __Hotfix0_GetEndTimeByEnrollId; // 0x40
	private static DelegateBridge __Hotfix0_GetEnrollTypeByEnrollId; // 0x48
	private static DelegateBridge __Hotfix0_CheckIfInEnrollByType; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x31f4fa8 VA: 0x759580cfa8
	protected override Void OnInit() { }
	// RVA: 0x31f5408 VA: 0x759580d408
	public String GetItemIcon(String itemId) { }
	// RVA: 0x31f54d0 VA: 0x759580d4d0
	public static Boolean TryGetArchiveCompData(String topicId, out RoguelikeArchiveComponentData compData) { }
	// RVA: 0x31f55e8 VA: 0x759580d5e8
	public static Boolean TryGetItem(String topicId, String itemId, out RoguelikeTopicItemModel item) { }
	// RVA: 0x31f5ab8 VA: 0x759580dab8
	public static Boolean TryGetTask(String topicId, String taskId, out RoguelikeTaskData taskData) { }
	// RVA: 0x31f5be0 VA: 0x759580dbe0
	public static ActArchiveChatGroupData GetArchiveChatGroupOrDetail(String topicId, String teamId) { }
	// RVA: 0x31f5d20 VA: 0x759580dd20
	public static Int64 GetPrevNearestMonthRefreshTimeData(String topicId, Int64 timestamp) { }
	// RVA: 0x31f5ed0 VA: 0x759580ded0
	public static Int64 GetOpenTimeByEnrollId(String topicId, String enrollId) { }
	// RVA: 0x31f6020 VA: 0x759580e020
	public static Int64 GetEndTimeByEnrollId(String topicId, String enrollId) { }
	// RVA: 0x31f61c0 VA: 0x759580e1c0
	public static RoguelikeEnrollType GetEnrollTypeByEnrollId(String topicId, String enrollId) { }
	// RVA: 0x31f6300 VA: 0x759580e300
	public static Boolean CheckIfInEnrollByType(String topicId, RoguelikeEnrollType enrollType) { }
	// RVA: 0x31f64d0 VA: 0x759580e4d0
	public Void .ctor() { }
}
```