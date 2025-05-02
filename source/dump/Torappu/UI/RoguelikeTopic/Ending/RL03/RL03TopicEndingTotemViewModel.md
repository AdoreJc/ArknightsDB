# RL03TopicEndingTotemViewModel

**Namespace:** `Torappu.UI.RoguelikeTopic.Ending.RL03`


## Fields

- `Int32 m_index`

- `Boolean m_isValid`

- `String m_topicId`

- `GameSettleOuterInfo m_settleData`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.Ending.RL03
public class RL03TopicEndingTotemViewModel : RoguelikeTopicEndingPageViewModelBase, IHotfixable
{
	private Int32 m_index; // 0x10
	private Boolean m_isValid; // 0x14
	private String m_topicId; // 0x18
	private GameSettleOuterInfo m_settleData; // 0x20
	private static DelegateBridge __Hotfix0_get_index; // 0x0
	private static DelegateBridge __Hotfix0_get_isValid; // 0x8
	private static DelegateBridge __Hotfix0_get_topicId; // 0x10
	private static DelegateBridge __Hotfix0_get_settleData; // 0x18
	private static DelegateBridge __Hotfix0_LoadData; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override Int32 index { get; }
	public override Boolean isValid { get; }
	public override String topicId { get; }
	public override GameSettleOuterInfo settleData { get; }

	// RVA: 0x26dcd88 VA: 0x7594cf4d88
	public override Int32 get_index() { }
	// RVA: 0x26dcdf0 VA: 0x7594cf4df0
	public override Boolean get_isValid() { }
	// RVA: 0x26dce58 VA: 0x7594cf4e58
	public override String get_topicId() { }
	// RVA: 0x26dcec0 VA: 0x7594cf4ec0
	public override GameSettleOuterInfo get_settleData() { }
	// RVA: 0x26dcf28 VA: 0x7594cf4f28
	public override Void LoadData(Int32 index, String topicId, SettleInfo settleInfo) { }
	// RVA: 0x26dd030 VA: 0x7594cf5030
	public Void .ctor() { }
}
```