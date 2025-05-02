# RoguelikeTopicMonthTaskListModel

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `Int32 refreshCount`

- `String m_topicId`

- `String m_bpItemName`

- `Sprite m_bpItemSprite`

- `Int64 m_nextUpdateTime`

- `Boolean m_isFinalUpdate`

- `Boolean m_showRefreshCount`


## Properties

- `String topicId`

- `Boolean isFinalUpdate`

- `Boolean canRefresh`

- `Boolean showRefreshCount`

- `TimeSpan updateCountDown`

- `String bpItemName`

- `Sprite bpItemSprite`


## Methods

- `String get_topicId()`

- `Boolean get_isFinalUpdate()`

- `Boolean get_canRefresh()`

- `Boolean get_showRefreshCount()`

- `TimeSpan get_updateCountDown()`

- `String get_bpItemName()`

- `Sprite get_bpItemSprite()`

- `Void LoadData(String)`

- `Void LoadData(String, IList`1, Int32)`

- `Int64 _GetFullStoredTime(String)`

- `Void _UpdateTopicData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicMonthTaskListModel : IHotfixable
{
	public List`1 taskModelList; // 0x10
	public Int32 refreshCount; // 0x18
	private String m_topicId; // 0x20
	private String m_bpItemName; // 0x28
	private Sprite m_bpItemSprite; // 0x30
	private Int64 m_nextUpdateTime; // 0x38
	private Boolean m_isFinalUpdate; // 0x40
	private Boolean m_showRefreshCount; // 0x41
	private Dictionary`2 m_monthTaskDict; // 0x48
	private List`1 m_updateList; // 0x50
	private static DelegateBridge __Hotfix0_get_topicId; // 0x0
	private static DelegateBridge __Hotfix0_get_isFinalUpdate; // 0x8
	private static DelegateBridge __Hotfix0_get_canRefresh; // 0x10
	private static DelegateBridge __Hotfix0_get_showRefreshCount; // 0x18
	private static DelegateBridge __Hotfix0_get_updateCountDown; // 0x20
	private static DelegateBridge __Hotfix0_get_bpItemName; // 0x28
	private static DelegateBridge __Hotfix0_get_bpItemSprite; // 0x30
	private static DelegateBridge __Hotfix0_LoadData; // 0x38
	private static DelegateBridge __Hotfix1_LoadData; // 0x40
	private static DelegateBridge __Hotfix0__GetFullStoredTime; // 0x48
	private static DelegateBridge __Hotfix0__UpdateTopicData; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public String topicId { get; }
	public Boolean isFinalUpdate { get; }
	public Boolean canRefresh { get; }
	public Boolean showRefreshCount { get; }
	public TimeSpan updateCountDown { get; }
	public String bpItemName { get; }
	public Sprite bpItemSprite { get; }

	// RVA: 0x265a8b8 VA: 0x7594c728b8
	public String get_topicId() { }
	// RVA: 0x265a920 VA: 0x7594c72920
	public Boolean get_isFinalUpdate() { }
	// RVA: 0x265a988 VA: 0x7594c72988
	public Boolean get_canRefresh() { }
	// RVA: 0x265a9f8 VA: 0x7594c729f8
	public Boolean get_showRefreshCount() { }
	// RVA: 0x265aa60 VA: 0x7594c72a60
	public TimeSpan get_updateCountDown() { }
	// RVA: 0x265ab3c VA: 0x7594c72b3c
	public String get_bpItemName() { }
	// RVA: 0x265aba4 VA: 0x7594c72ba4
	public Sprite get_bpItemSprite() { }
	// RVA: 0x2659a64 VA: 0x7594c71a64
	public Void LoadData(String topicId) { }
	// RVA: 0x265b15c VA: 0x7594c7315c
	public Void LoadData(String topicId, IList`1 missions, Int32 currBp) { }
	// RVA: 0x265aebc VA: 0x7594c72ebc
	private Int64 _GetFullStoredTime(String topicId) { }
	// RVA: 0x265ac0c VA: 0x7594c72c0c
	private Void _UpdateTopicData() { }
	// RVA: 0x265b490 VA: 0x7594c73490
	public Void .ctor() { }
}
```