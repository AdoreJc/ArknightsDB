# Act13sideDailyMissionPoolView

**Namespace:** `Torappu.Activity.Act13Side`


## Fields

- `Act13sideMissionPoolItemView _missionItemTemplate`

- `Text _textAgendaMax`

- `Text _textAgendaOwn`

- `Text _textMissionBoard`

- `Text _textSearchCount`

- `Button _btnSearch`

- `Color _hintColor`

- `Color _greyColor`

- `GameObject _emptyPartGo`

- `GameObject _normalPartGo`

- `Text _textPrincipalName`

- `Text _textPrincipalEnName`

- `Text _textOrgEnName`

- `Text _textMissionName`

- `Text _textMissionDesc`

- `Text _textPrestigeDesc`

- `Text _textAgendaNeed`

- `Text _textPrincipalDialog`

- `Image _imgOrgLogo`

- `GameObject _btnAccpetGo`

- `GameObject _btnReplaceGo`

- `GameObject _agendaLackHint`

- `SimpleLayoutContent _rewardList`

- `Single _itemCardScale`

- `UIAVGCharacter _uiAVGCharacter`

- `Single _layoutAnimDelay`

- `Single _layoutAnimDuration`

- `Single _layoutElementHeight`

- `Boolean m_hasInited`

- `String m_actId`

- `Act13sideDailyMissionPoolViewModel m_model`

- `Act13SideData m_actData`

- `RewardListAdapter m_rewardListAdapter`

- `String m_prevAvgCharId`


## Methods

- `Void _RenderNormalPart(Act13sideDailyMissionPoolViewModel)`

- `Int32 _CalcBoardAgendaVal()`

- `Int32 _GetMissionAgendaCount(String)`

- `Void _CleanView()`

- `Void ResetLayoutElement()`

- `Void Init(String, Action`1)`

- `Void _InitIfNot()`

- `Void PlayAcceptAnim(Int32, TweenCallback)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act13Side
public class Act13sideDailyMissionPoolView : DataBinder`1
{
	private LayoutElement[] _missionItemParentList; // 0x20
	private Act13sideMissionPoolItemView _missionItemTemplate; // 0x28
	private Text _textAgendaMax; // 0x30
	private Text _textAgendaOwn; // 0x38
	private Text _textMissionBoard; // 0x40
	private Text _textSearchCount; // 0x48
	private Button _btnSearch; // 0x50
	private Color _hintColor; // 0x58
	private Color _greyColor; // 0x68
	private TwoStateToggle[] _missionBoardItemList; // 0x78
	private GameObject _emptyPartGo; // 0x80
	private GameObject _normalPartGo; // 0x88
	private Text _textPrincipalName; // 0x90
	private Text _textPrincipalEnName; // 0x98
	private Text _textOrgEnName; // 0xa0
	private Text _textMissionName; // 0xa8
	private Text _textMissionDesc; // 0xb0
	private Text _textPrestigeDesc; // 0xb8
	private Text _textAgendaNeed; // 0xc0
	private Text _textPrincipalDialog; // 0xc8
	private Image _imgOrgLogo; // 0xd0
	private GameObject _btnAccpetGo; // 0xd8
	private GameObject _btnReplaceGo; // 0xe0
	private GameObject _agendaLackHint; // 0xe8
	private SimpleLayoutContent _rewardList; // 0xf0
	private Single _itemCardScale; // 0xf8
	private UIAVGCharacter _uiAVGCharacter; // 0x100
	private Single _layoutAnimDelay; // 0x108
	private Single _layoutAnimDuration; // 0x10c
	private Single _layoutElementHeight; // 0x110
	private Boolean m_hasInited; // 0x114
	private String m_actId; // 0x118
	private Act13sideDailyMissionPoolViewModel m_model; // 0x120
	private Act13SideData m_actData; // 0x128
	private Action`1 m_onPoolItemSelected; // 0x130
	private RewardListAdapter m_rewardListAdapter; // 0x138
	private String m_prevAvgCharId; // 0x140
	private List`1 m_missionItemList; // 0x148
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__RenderNormalPart; // 0x8
	private static DelegateBridge __Hotfix0__CalcBoardAgendaVal; // 0x10
	private static DelegateBridge __Hotfix0__GetMissionAgendaCount; // 0x18
	private static DelegateBridge __Hotfix0__CleanView; // 0x20
	private static DelegateBridge __Hotfix0_ResetLayoutElement; // 0x28
	private static DelegateBridge __Hotfix0_Init; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x38
	private static DelegateBridge __Hotfix0_PlayAcceptAnim; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x343c1fc VA: 0x7595a541fc
	public override Void OnValueChanged(Act13sideDailyMissionPoolProperty property) { }
	// RVA: 0x343d188 VA: 0x7595a55188
	private Void _RenderNormalPart(Act13sideDailyMissionPoolViewModel missionModel) { }
	// RVA: 0x343d66c VA: 0x7595a5566c
	private Int32 _CalcBoardAgendaVal() { }
	// RVA: 0x343d810 VA: 0x7595a55810
	private Int32 _GetMissionAgendaCount(String missionId) { }
	// RVA: 0x343caa0 VA: 0x7595a54aa0
	private Void _CleanView() { }
	// RVA: 0x343d930 VA: 0x7595a55930
	public Void ResetLayoutElement() { }
	// RVA: 0x343da78 VA: 0x7595a55a78
	public Void Init(String actId, Action`1 onMissonPoolItemSelected) { }
	// RVA: 0x343c7b8 VA: 0x7595a547b8
	private Void _InitIfNot() { }
	// RVA: 0x343dbc4 VA: 0x7595a55bc4
	public Void PlayAcceptAnim(Int32 selectedPoolIdx, TweenCallback onAnimComplete) { }
	// RVA: 0x343de5c VA: 0x7595a55e5c
	public Void .ctor() { }
}
```