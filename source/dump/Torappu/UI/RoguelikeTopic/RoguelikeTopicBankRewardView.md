# RoguelikeTopicBankRewardView

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `Text _textHighest`

- `Text _textHighestShadow`

- `SimpleLayoutContent _rewardList`

- `String m_topicId`

- `RoguelikeTopicDetail m_topicData`

- `Bank m_outerBankData`

- `Adapter m_adapter`


## Methods

- `Void Render(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicBankRewardView : MonoBehaviour, IHotfixable
{
	private Text _textHighest; // 0x18
	private Text _textHighestShadow; // 0x20
	private SimpleLayoutContent _rewardList; // 0x28
	private String m_topicId; // 0x30
	private RoguelikeTopicDetail m_topicData; // 0x38
	private Bank m_outerBankData; // 0x40
	private Adapter m_adapter; // 0x48
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2634920 VA: 0x7594c4c920
	public Void Render(String topicId) { }
	// RVA: 0x2634bf4 VA: 0x7594c4cbf4
	public Void .ctor() { }
}
```