# RoguelikeTopicEndingOverViewModel

**Namespace:** `Torappu.UI.RoguelikeTopic.Ending`


## Fields

- `Int32 m_index`

- `Boolean m_isValid`

- `String m_topicId`

- `GameSettleOuterInfo m_settleData`

- `Int32 <currBpPoint>k__BackingField`

- `Int32 <preBpPoint>k__BackingField`


## Properties

- `Int32 currBpPoint`

- `Int32 preBpPoint`


## Methods

- `Int32 get_currBpPoint()`

- `Void set_currBpPoint(Int32)`

- `Int32 get_preBpPoint()`

- `Void set_preBpPoint(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.Ending
public class RoguelikeTopicEndingOverViewModel : RoguelikeTopicEndingPageViewModelBase, IHotfixable
{
	private Int32 m_index; // 0x10
	private Boolean m_isValid; // 0x14
	private String m_topicId; // 0x18
	private GameSettleOuterInfo m_settleData; // 0x20
	private Int32 <currBpPoint>k__BackingField; // 0x28
	private Int32 <preBpPoint>k__BackingField; // 0x2c
	private static DelegateBridge __Hotfix0_get_index; // 0x0
	private static DelegateBridge __Hotfix0_get_isValid; // 0x8
	private static DelegateBridge __Hotfix0_get_topicId; // 0x10
	private static DelegateBridge __Hotfix0_get_settleData; // 0x18
	private static DelegateBridge __Hotfix0_get_currBpPoint; // 0x20
	private static DelegateBridge __Hotfix0_set_currBpPoint; // 0x28
	private static DelegateBridge __Hotfix0_get_preBpPoint; // 0x30
	private static DelegateBridge __Hotfix0_set_preBpPoint; // 0x38
	private static DelegateBridge __Hotfix0_LoadData; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public override Int32 index { get; }
	public override Boolean isValid { get; }
	public override String topicId { get; }
	public override GameSettleOuterInfo settleData { get; }
	public Int32 currBpPoint { get; set; }
	public Int32 preBpPoint { get; set; }

	// RVA: 0x26d8a40 VA: 0x7594cf0a40
	public override Int32 get_index() { }
	// RVA: 0x26d8aa8 VA: 0x7594cf0aa8
	public override Boolean get_isValid() { }
	// RVA: 0x26d8b10 VA: 0x7594cf0b10
	public override String get_topicId() { }
	// RVA: 0x26d8b78 VA: 0x7594cf0b78
	public override GameSettleOuterInfo get_settleData() { }
	// RVA: 0x26d8be0 VA: 0x7594cf0be0
	public Int32 get_currBpPoint() { }
	// RVA: 0x26d8c48 VA: 0x7594cf0c48
	private Void set_currBpPoint(Int32 value) { }
	// RVA: 0x26d8cc4 VA: 0x7594cf0cc4
	public Int32 get_preBpPoint() { }
	// RVA: 0x26d8d2c VA: 0x7594cf0d2c
	private Void set_preBpPoint(Int32 value) { }
	// RVA: 0x26d8da8 VA: 0x7594cf0da8
	public override Void LoadData(Int32 index, String topicId, SettleInfo settleInfo) { }
	// RVA: 0x26d9030 VA: 0x7594cf1030
	public Void .ctor() { }
}
```