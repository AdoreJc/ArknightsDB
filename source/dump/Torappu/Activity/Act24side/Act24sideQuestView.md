# Act24sideQuestView

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `SimpleLayoutContent _questGroupList`

- `SimpleLayoutContent _stageRankList`

- `SimpleLayoutContent _meldingRewardList`

- `Text _textPlanCount`

- `Text _textStageName`

- `Text _textDangerLv`

- `Text _textStageDesc`

- `Text _textApCost`

- `Text _textPracticeCost`

- `TwoStateToggle _btnStartDecoToggle`

- `UIAtlasImage _imgIcon`

- `UIAtlasObject _atlasQuest`

- `String _normalIconName`

- `String _hardIconName`

- `String _dragonIconName`

- `Act24sideQuestRewardItemPreview _rewardItemPreview`

- `QuestListAdapter m_questListAdapter`

- `StageRankListAdapter m_stageRankListAdapter`

- `MeldingListAdapter m_meldingListAdapter`

- `Boolean m_hasInited`

- `Act24sideQuestModel m_questModel`

- `Act24sideQuestStageItemModel m_selectQuestItemModel`


## Methods

- `Void _RenderStageInfo(Act24sideQuestStageItemModel)`

- `String _GetIconSpriteName(Act24sideQuestStageItemModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideQuestView : DataBinder`1
{
	private SimpleLayoutContent _questGroupList; // 0x20
	private SimpleLayoutContent _stageRankList; // 0x28
	private SimpleLayoutContent _meldingRewardList; // 0x30
	private Text _textPlanCount; // 0x38
	private Text _textStageName; // 0x40
	private Text _textDangerLv; // 0x48
	private Text _textStageDesc; // 0x50
	private Text _textApCost; // 0x58
	private Text _textPracticeCost; // 0x60
	private TwoStateToggle _btnStartDecoToggle; // 0x68
	private UIAtlasImage _imgIcon; // 0x70
	private UIAtlasObject _atlasQuest; // 0x78
	private String _normalIconName; // 0x80
	private String _hardIconName; // 0x88
	private String _dragonIconName; // 0x90
	private Act24sideQuestRewardItemPreview _rewardItemPreview; // 0x98
	private QuestListAdapter m_questListAdapter; // 0xa0
	private StageRankListAdapter m_stageRankListAdapter; // 0xa8
	private MeldingListAdapter m_meldingListAdapter; // 0xb0
	private Boolean m_hasInited; // 0xb8
	private Act24sideQuestModel m_questModel; // 0xc0
	private Act24sideQuestStageItemModel m_selectQuestItemModel; // 0xc8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__RenderStageInfo; // 0x8
	private static DelegateBridge __Hotfix0__GetIconSpriteName; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x32e06a8 VA: 0x75958f86a8
	public override Void OnValueChanged(Act24sideQuestProp property) { }
	// RVA: 0x32e0988 VA: 0x75958f8988
	private Void _RenderStageInfo(Act24sideQuestStageItemModel selectQuestItemModel) { }
	// RVA: 0x32e0c9c VA: 0x75958f8c9c
	private String _GetIconSpriteName(Act24sideQuestStageItemModel selectQuestItemModel) { }
	// RVA: 0x32e0810 VA: 0x75958f8810
	private Void _InitIfNot() { }
	// RVA: 0x32e0f08 VA: 0x75958f8f08
	public Void .ctor() { }
}
```