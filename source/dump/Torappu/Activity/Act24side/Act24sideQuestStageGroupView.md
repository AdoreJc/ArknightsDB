# Act24sideQuestStageGroupView

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `SimpleLayoutContent _questList`

- `SimpleLayoutContent _rankList`

- `TwoStateToggle _groupInfoToggle`

- `Boolean m_hasInited`

- `QuestListAdapter m_questListAdapter`

- `RankListAdapter m_rankListAdapter`

- `Act24sideQuestStageGroupModel m_groupModel`

- `String m_selectStageId`


## Methods

- `Void Render(Act24sideQuestStageGroupModel, String)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideQuestStageGroupView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _questList; // 0x18
	private SimpleLayoutContent _rankList; // 0x20
	private TwoStateToggle _groupInfoToggle; // 0x28
	private Boolean m_hasInited; // 0x30
	private QuestListAdapter m_questListAdapter; // 0x38
	private RankListAdapter m_rankListAdapter; // 0x40
	private Act24sideQuestStageGroupModel m_groupModel; // 0x48
	private String m_selectStageId; // 0x50
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x32c1de8 VA: 0x75958d9de8
	public Void Render(Act24sideQuestStageGroupModel groupModel, String selectStageId) { }
	// RVA: 0x32c1ee0 VA: 0x75958d9ee0
	private Void _InitIfNot() { }
	// RVA: 0x32c212c VA: 0x75958da12c
	public Void .ctor() { }
}
```