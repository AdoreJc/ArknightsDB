# SiracusaCharTaskRingModel

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `TaskRingData m_taskRingData`

- `TaskRing m_playerRing`

- `Boolean m_isUnlock`

- `String m_unlockHint`

- `Int32 m_selectIndex`


## Properties

- `SiracusaCharTaskModel selectTaskModel`

- `Boolean isUnlock`

- `String unlockHint`

- `Int32 sortId`

- `ItemBundle rewardItem`

- `String ringId`

- `TaskRingStatus ringStatus`

- `String taskRingDesc`

- `TaskRingLogicType ringType`

- `Boolean isDoing`


## Methods

- `SiracusaCharTaskModel get_selectTaskModel()`

- `Boolean get_isUnlock()`

- `String get_unlockHint()`

- `Int32 get_sortId()`

- `ItemBundle get_rewardItem()`

- `String get_ringId()`

- `TaskRingStatus get_ringStatus()`

- `String get_taskRingDesc()`

- `TaskRingLogicType get_ringType()`

- `Boolean get_isDoing()`

- `Void LoadData(SiracusaData, TaskRingData, TaskRing, Dictionary`2)`

- `String _GetUnlockHint(SiracusaData, String)`

- `SiracusaCharTaskModel FindTaskAndSelect(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaCharTaskRingModel : IHotfixable
{
	private TaskRingData m_taskRingData; // 0x10
	private TaskRing m_playerRing; // 0x18
	private List`1 m_taskList; // 0x20
	private HashSet`1 m_relatedAreaSet; // 0x28
	private Boolean m_isUnlock; // 0x30
	private String m_unlockHint; // 0x38
	private Int32 m_selectIndex; // 0x40
	private static DelegateBridge __Hotfix0_get_selectTaskModel; // 0x0
	private static DelegateBridge __Hotfix0_get_isUnlock; // 0x8
	private static DelegateBridge __Hotfix0_get_unlockHint; // 0x10
	private static DelegateBridge __Hotfix0_get_sortId; // 0x18
	private static DelegateBridge __Hotfix0_get_rewardItem; // 0x20
	private static DelegateBridge __Hotfix0_get_ringId; // 0x28
	private static DelegateBridge __Hotfix0_get_ringStatus; // 0x30
	private static DelegateBridge __Hotfix0_get_taskRingDesc; // 0x38
	private static DelegateBridge __Hotfix0_get_ringType; // 0x40
	private static DelegateBridge __Hotfix0_get_taskList; // 0x48
	private static DelegateBridge __Hotfix0_get_isDoing; // 0x50
	private static DelegateBridge __Hotfix0_LoadData; // 0x58
	private static DelegateBridge __Hotfix0__GetUnlockHint; // 0x60
	private static DelegateBridge __Hotfix0_FindTaskAndSelect; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public SiracusaCharTaskModel selectTaskModel { get; }
	public Boolean isUnlock { get; }
	public String unlockHint { get; }
	public Int32 sortId { get; }
	public ItemBundle rewardItem { get; }
	public String ringId { get; }
	public TaskRingStatus ringStatus { get; }
	public String taskRingDesc { get; }
	public TaskRingLogicType ringType { get; }
	public List`1 taskList { get; }
	public Boolean isDoing { get; }

	// RVA: 0x23e559c VA: 0x75949fd59c
	public SiracusaCharTaskModel get_selectTaskModel() { }
	// RVA: 0x23e5624 VA: 0x75949fd624
	public Boolean get_isUnlock() { }
	// RVA: 0x23e568c VA: 0x75949fd68c
	public String get_unlockHint() { }
	// RVA: 0x23e56f4 VA: 0x75949fd6f4
	public Int32 get_sortId() { }
	// RVA: 0x23e576c VA: 0x75949fd76c
	public ItemBundle get_rewardItem() { }
	// RVA: 0x23e57e4 VA: 0x75949fd7e4
	public String get_ringId() { }
	// RVA: 0x23e585c VA: 0x75949fd85c
	public TaskRingStatus get_ringStatus() { }
	// RVA: 0x23e58d4 VA: 0x75949fd8d4
	public String get_taskRingDesc() { }
	// RVA: 0x23e5968 VA: 0x75949fd968
	public TaskRingLogicType get_ringType() { }
	// RVA: 0x23e59e0 VA: 0x75949fd9e0
	public List`1 get_taskList() { }
	// RVA: 0x23e5a48 VA: 0x75949fda48
	public Boolean get_isDoing() { }
	// RVA: 0x23e5acc VA: 0x75949fdacc
	public Void LoadData(SiracusaData siracusaData, TaskRingData ringData, TaskRing playerRing, Dictionary`2 area) { }
	// RVA: 0x23e60b8 VA: 0x75949fe0b8
	private String _GetUnlockHint(SiracusaData siracusaData, String areaId) { }
	// RVA: 0x23e6204 VA: 0x75949fe204
	public SiracusaCharTaskModel FindTaskAndSelect(String taskId) { }
	// RVA: 0x23e632c VA: 0x75949fe32c
	public Void .ctor() { }
}
```