# RL04TopicEndingFragmentViewModel

**Namespace:** `Torappu.UI.RoguelikeTopic.RL04`


## Fields

- `Int32 m_index`

- `Boolean m_isValid`

- `String m_topicId`

- `GameSettleOuterInfo m_settleData`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL04
public class RL04TopicEndingFragmentViewModel : RoguelikeTopicEndingPageViewModelBase, IHotfixable
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

	// RVA: 0x26f20e4 VA: 0x7594d0a0e4
	public override Int32 get_index() { }
	// RVA: 0x26f214c VA: 0x7594d0a14c
	public override Boolean get_isValid() { }
	// RVA: 0x26f21b4 VA: 0x7594d0a1b4
	public override String get_topicId() { }
	// RVA: 0x26f221c VA: 0x7594d0a21c
	public override GameSettleOuterInfo get_settleData() { }
	// RVA: 0x26f2284 VA: 0x7594d0a284
	public override Void LoadData(Int32 index, String topicId, SettleInfo settleInfo) { }
	// RVA: 0x26f238c VA: 0x7594d0a38c
	public Void .ctor() { }
}
```