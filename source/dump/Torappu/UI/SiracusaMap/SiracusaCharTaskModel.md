# SiracusaCharTaskModel

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `TaskBasicInfoData m_basicInfoData`

- `TaskInfo m_playerTask`

- `PointData m_pointData`


## Properties

- `Int32 sortId`

- `String placeId`

- `String npcId`

- `String placeName`

- `StateEnum taskStatus`

- `BattleProgress battleProgress`

- `TaskType taskType`

- `String taskId`


## Methods

- `Int32 get_sortId()`

- `String get_placeId()`

- `String get_npcId()`

- `String get_placeName()`

- `StateEnum get_taskStatus()`

- `BattleProgress get_battleProgress()`

- `TaskType get_taskType()`

- `String get_taskId()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaCharTaskModel : IHotfixable
{
	private TaskBasicInfoData m_basicInfoData; // 0x10
	private TaskInfo m_playerTask; // 0x18
	private PointData m_pointData; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_sortId; // 0x8
	private static DelegateBridge __Hotfix0_get_placeId; // 0x10
	private static DelegateBridge __Hotfix0_get_npcId; // 0x18
	private static DelegateBridge __Hotfix0_get_placeName; // 0x20
	private static DelegateBridge __Hotfix0_get_taskStatus; // 0x28
	private static DelegateBridge __Hotfix0_get_battleProgress; // 0x30
	private static DelegateBridge __Hotfix0_get_taskType; // 0x38
	private static DelegateBridge __Hotfix0_get_taskId; // 0x40
	private static DelegateBridge __Hotfix0_LoadData; // 0x48
	private static DelegateBridge __Hotfix0_Create; // 0x50

	public Int32 sortId { get; }
	public String placeId { get; }
	public String npcId { get; }
	public String placeName { get; }
	public StateEnum taskStatus { get; }
	public BattleProgress battleProgress { get; }
	public TaskType taskType { get; }
	public String taskId { get; }

	// RVA: 0x23e4ad4 VA: 0x75949fcad4
	protected Void .ctor() { }
	// RVA: 0x23e4b44 VA: 0x75949fcb44
	public Int32 get_sortId() { }
	// RVA: 0x23e4bbc VA: 0x75949fcbbc
	public String get_placeId() { }
	// RVA: 0x23e4c50 VA: 0x75949fcc50
	public String get_npcId() { }
	// RVA: 0x23e4ce4 VA: 0x75949fcce4
	public String get_placeName() { }
	// RVA: 0x23e4d78 VA: 0x75949fcd78
	public StateEnum get_taskStatus() { }
	// RVA: 0x23e4df0 VA: 0x75949fcdf0
	public BattleProgress get_battleProgress() { }
	// RVA: 0x23e4e68 VA: 0x75949fce68
	public TaskType get_taskType() { }
	// RVA: 0x23e4ee0 VA: 0x75949fcee0
	public String get_taskId() { }
	// RVA: 0x23e4f58 VA: 0x75949fcf58
	public virtual Void LoadData(SiracusaData siracusaData, TaskBasicInfoData taskInfoData, TaskInfo playerTask) { }
	// RVA: 0x23e506c VA: 0x75949fd06c
	public static SiracusaCharTaskModel Create(SiracusaData siracusaData, TaskBasicInfoData taskInfoData, TaskInfo playerTask) { }
}
```