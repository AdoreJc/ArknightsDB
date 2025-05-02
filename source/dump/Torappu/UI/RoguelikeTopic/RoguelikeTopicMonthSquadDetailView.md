# RoguelikeTopicMonthSquadDetailView

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `Text _monthSquadTitle`

- `Text _monthSquadDesc`

- `Text _monthSquadSubDesc`

- `Text _textTarget`

- `UIAtlasImage _iconTeam`

- `RectTransform _rewardViewHolder`

- `RoguelikeTopicMonthSquadRewardView _rewardViewPrefab`

- `RoguelikeTopicMonthSquadDetailState <bindState>k__BackingField`

- `RoguelikeTopicMonthSquadStyle m_style`

- `RoguelikeTopicMonthSquadRewardView m_rewardView`

- `String m_cachedSquadId`

- `Boolean m_hasInited`


## Properties

- `RoguelikeTopicMonthSquadDetailState bindState`


## Methods

- `RoguelikeTopicMonthSquadDetailState get_bindState()`

- `Void set_bindState(RoguelikeTopicMonthSquadDetailState)`

- `Void _InitIfNot()`

- `Void Init(RoguelikeTopicMonthSquadDetailState, RoguelikeTopicMonthSquadStyle)`

- `Void _Render(RoguelikeTopicModeViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicMonthSquadDetailView : DataBinder`1
{
	private Text _monthSquadTitle; // 0x20
	private Text _monthSquadDesc; // 0x28
	private Text _monthSquadSubDesc; // 0x30
	private Text _textTarget; // 0x38
	private UIAtlasImage _iconTeam; // 0x40
	private RectTransform _rewardViewHolder; // 0x48
	private RoguelikeTopicMonthSquadRewardView _rewardViewPrefab; // 0x50
	private RoguelikeTopicMonthSquadDetailState <bindState>k__BackingField; // 0x58
	private RoguelikeTopicMonthSquadStyle m_style; // 0x60
	private RoguelikeTopicMonthSquadRewardView m_rewardView; // 0x68
	private String m_cachedSquadId; // 0x70
	private Boolean m_hasInited; // 0x78
	private static DelegateBridge __Hotfix0_get_bindState; // 0x0
	private static DelegateBridge __Hotfix0_set_bindState; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_Init; // 0x18
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x20
	private static DelegateBridge __Hotfix0__Render; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private RoguelikeTopicMonthSquadDetailState bindState { get; set; }

	// RVA: 0x2655d94 VA: 0x7594c6dd94
	private RoguelikeTopicMonthSquadDetailState get_bindState() { }
	// RVA: 0x2655dfc VA: 0x7594c6ddfc
	private Void set_bindState(RoguelikeTopicMonthSquadDetailState value) { }
	// RVA: 0x2655e80 VA: 0x7594c6de80
	private Void _InitIfNot() { }
	// RVA: 0x2655c10 VA: 0x7594c6dc10
	public Void Init(RoguelikeTopicMonthSquadDetailState state, RoguelikeTopicMonthSquadStyle style) { }
	// RVA: 0x26561a0 VA: 0x7594c6e1a0
	public override Void OnValueChanged(RoguelikeTopicModeViewProperty property) { }
	// RVA: 0x2656254 VA: 0x7594c6e254
	private Void _Render(RoguelikeTopicModeViewModel model) { }
	// RVA: 0x26569f8 VA: 0x7594c6e9f8
	public Void .ctor() { }
}
```