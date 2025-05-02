# RoguelikeTopicEndingMonthTaskViewModel

**Namespace:** `Torappu.UI.RoguelikeTopic.Ending`


## Fields

- `Int32 m_index`

- `Boolean m_isValid`

- `String m_topicId`

- `GameSettleOuterInfo m_settleData`

- `Int32 <currBpPoint>k__BackingField`

- `Int32 <preBpPoint>k__BackingField`

- `RoguelikeTopicMonthTaskListModel <monthTaskModel>k__BackingField`

- `RoguelikeTopicMonthTaskListModel <preMonthTaskModel>k__BackingField`


## Properties

- `Int32 currBpPoint`

- `Int32 preBpPoint`

- `RoguelikeTopicMonthTaskListModel monthTaskModel`

- `RoguelikeTopicMonthTaskListModel preMonthTaskModel`


## Methods

- `Int32 get_currBpPoint()`

- `Void set_currBpPoint(Int32)`

- `Int32 get_preBpPoint()`

- `Void set_preBpPoint(Int32)`

- `RoguelikeTopicMonthTaskListModel get_monthTaskModel()`

- `Void set_monthTaskModel(RoguelikeTopicMonthTaskListModel)`

- `RoguelikeTopicMonthTaskListModel get_preMonthTaskModel()`

- `Void set_preMonthTaskModel(RoguelikeTopicMonthTaskListModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.Ending
public class RoguelikeTopicEndingMonthTaskViewModel : RoguelikeTopicEndingPageViewModelBase, IHotfixable
{
	private Int32 m_index; // 0x10
	private Boolean m_isValid; // 0x14
	private String m_topicId; // 0x18
	private GameSettleOuterInfo m_settleData; // 0x20
	private Int32 <currBpPoint>k__BackingField; // 0x28
	private Int32 <preBpPoint>k__BackingField; // 0x2c
	private RoguelikeTopicMonthTaskListModel <monthTaskModel>k__BackingField; // 0x30
	private RoguelikeTopicMonthTaskListModel <preMonthTaskModel>k__BackingField; // 0x38
	private static DelegateBridge __Hotfix0_get_index; // 0x0
	private static DelegateBridge __Hotfix0_get_isValid; // 0x8
	private static DelegateBridge __Hotfix0_get_topicId; // 0x10
	private static DelegateBridge __Hotfix0_get_settleData; // 0x18
	private static DelegateBridge __Hotfix0_get_currBpPoint; // 0x20
	private static DelegateBridge __Hotfix0_set_currBpPoint; // 0x28
	private static DelegateBridge __Hotfix0_get_preBpPoint; // 0x30
	private static DelegateBridge __Hotfix0_set_preBpPoint; // 0x38
	private static DelegateBridge __Hotfix0_get_monthTaskModel; // 0x40
	private static DelegateBridge __Hotfix0_set_monthTaskModel; // 0x48
	private static DelegateBridge __Hotfix0_get_preMonthTaskModel; // 0x50
	private static DelegateBridge __Hotfix0_set_preMonthTaskModel; // 0x58
	private static DelegateBridge __Hotfix0_LoadData; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public override Int32 index { get; }
	public override Boolean isValid { get; }
	public override String topicId { get; }
	public override GameSettleOuterInfo settleData { get; }
	public Int32 currBpPoint { get; set; }
	public Int32 preBpPoint { get; set; }
	public RoguelikeTopicMonthTaskListModel monthTaskModel { get; set; }
	public RoguelikeTopicMonthTaskListModel preMonthTaskModel { get; set; }

	// RVA: 0x26d810c VA: 0x7594cf010c
	public override Int32 get_index() { }
	// RVA: 0x26d8174 VA: 0x7594cf0174
	public override Boolean get_isValid() { }
	// RVA: 0x26d81dc VA: 0x7594cf01dc
	public override String get_topicId() { }
	// RVA: 0x26d8244 VA: 0x7594cf0244
	public override GameSettleOuterInfo get_settleData() { }
	// RVA: 0x26d82ac VA: 0x7594cf02ac
	public Int32 get_currBpPoint() { }
	// RVA: 0x26d8314 VA: 0x7594cf0314
	private Void set_currBpPoint(Int32 value) { }
	// RVA: 0x26d8390 VA: 0x7594cf0390
	public Int32 get_preBpPoint() { }
	// RVA: 0x26d83f8 VA: 0x7594cf03f8
	private Void set_preBpPoint(Int32 value) { }
	// RVA: 0x26d8474 VA: 0x7594cf0474
	public RoguelikeTopicMonthTaskListModel get_monthTaskModel() { }
	// RVA: 0x26d84dc VA: 0x7594cf04dc
	private Void set_monthTaskModel(RoguelikeTopicMonthTaskListModel value) { }
	// RVA: 0x26d8560 VA: 0x7594cf0560
	public RoguelikeTopicMonthTaskListModel get_preMonthTaskModel() { }
	// RVA: 0x26d85c8 VA: 0x7594cf05c8
	private Void set_preMonthTaskModel(RoguelikeTopicMonthTaskListModel value) { }
	// RVA: 0x26d864c VA: 0x7594cf064c
	public override Void LoadData(Int32 index, String topicId, SettleInfo settleInfo) { }
	// RVA: 0x26d89d0 VA: 0x7594cf09d0
	public Void .ctor() { }
}
```