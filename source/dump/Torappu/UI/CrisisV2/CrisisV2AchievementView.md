# CrisisV2AchievementView

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `Text _textName`

- `Text _textCode`

- `Text _textRuneCount`

- `CrisisV2AchievementRuneAdapter _runeAdapter`

- `CrisisV2AchievementCommentAdapter _commentAdapter`

- `Text _textTotalScore`

- `Image _imgRankIcon`

- `UIAtlasImage _imgMapBkg`

- `UIAtlasImage _imgTitle`

- `RectTransform _medalGroupContainer`

- `RectTransform _avatarContainer`

- `Text _textPlayerNickName`

- `Single _avatarScale`

- `CrisisV2DiagramView _diagramPrefab`

- `RectTransform _diagramContainer`

- `GameObject _panelSnapshootEmpty`

- `GameObject _panelSnapshootNotEmpty`

- `UIStateFinder m_stateFinder`

- `UIMedalGroupView m_medalGroup`

- `Boolean m_hasInited`

- `PlayerAvatarView m_avatarView`

- `CrisisV2DiagramView m_diagramView`

- `UIPage <page>k__BackingField`


## Properties

- `UIPage page`


## Methods

- `UIPage get_page()`

- `Void set_page(UIPage)`

- `Void EventOnNextBtnClicked()`

- `Void EventOnPrevBtnClicked()`

- `Void EventOnMedalGroupClicked()`

- `Void EventOnHistoryClicked()`

- `Void _InitIfNot()`

- `Void _RenderInfo(CrisisV2AchievementSeasonViewModel, Boolean)`

- `Void _RenderDiagram(CrisisV2AchievementSeasonViewModel, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2AchievementView : DataBinder`1, IHotfixable
{
	private Text _textName; // 0x20
	private Text _textCode; // 0x28
	private GameObject[] _panelEmpty; // 0x30
	private GameObject[] _panelInfo; // 0x38
	private Text _textRuneCount; // 0x40
	private CrisisV2AchievementRuneAdapter _runeAdapter; // 0x48
	private CrisisV2AchievementCommentAdapter _commentAdapter; // 0x50
	private Text _textTotalScore; // 0x58
	private Image _imgRankIcon; // 0x60
	private UIAtlasImage _imgMapBkg; // 0x68
	private UIAtlasImage _imgTitle; // 0x70
	private RectTransform _medalGroupContainer; // 0x78
	private GameObject[] _panelSwitchBtn; // 0x80
	private RectTransform _avatarContainer; // 0x88
	private Text _textPlayerNickName; // 0x90
	private Single _avatarScale; // 0x98
	private CrisisV2DiagramView _diagramPrefab; // 0xa0
	private RectTransform _diagramContainer; // 0xa8
	private GameObject _panelSnapshootEmpty; // 0xb0
	private GameObject _panelSnapshootNotEmpty; // 0xb8
	private UIStateFinder m_stateFinder; // 0xc0
	private UIMedalGroupView m_medalGroup; // 0xd0
	private Boolean m_hasInited; // 0xd8
	private PlayerAvatarView m_avatarView; // 0xe0
	private CrisisV2DiagramView m_diagramView; // 0xe8
	private UIPage <page>k__BackingField; // 0xf0
	private static DelegateBridge __Hotfix0_get_page; // 0x0
	private static DelegateBridge __Hotfix0_set_page; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0_EventOnNextBtnClicked; // 0x18
	private static DelegateBridge __Hotfix0_EventOnPrevBtnClicked; // 0x20
	private static DelegateBridge __Hotfix0_EventOnMedalGroupClicked; // 0x28
	private static DelegateBridge __Hotfix0_EventOnHistoryClicked; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x38
	private static DelegateBridge __Hotfix0__RenderInfo; // 0x40
	private static DelegateBridge __Hotfix0__RenderDiagram; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	private UIPage page { get; set; }

	// RVA: 0x2bf9ac4 VA: 0x7595211ac4
	private UIPage get_page() { }
	// RVA: 0x2bf9b2c VA: 0x7595211b2c
	public Void set_page(UIPage value) { }
	// RVA: 0x2bf9bb0 VA: 0x7595211bb0
	public override Void OnValueChanged(CrisisV2AchievementProperty property) { }
	// RVA: 0x2bfa6bc VA: 0x75952126bc
	public Void EventOnNextBtnClicked() { }
	// RVA: 0x2bfa760 VA: 0x7595212760
	public Void EventOnPrevBtnClicked() { }
	// RVA: 0x2bfa804 VA: 0x7595212804
	public Void EventOnMedalGroupClicked() { }
	// RVA: 0x2bfa8a8 VA: 0x75952128a8
	public Void EventOnHistoryClicked() { }
	// RVA: 0x2bf9ce8 VA: 0x7595211ce8
	private Void _InitIfNot() { }
	// RVA: 0x2bf9f78 VA: 0x7595211f78
	private Void _RenderInfo(CrisisV2AchievementSeasonViewModel model, Boolean showSwitchBtn) { }
	// RVA: 0x2bfa54c VA: 0x759521254c
	private Void _RenderDiagram(CrisisV2AchievementSeasonViewModel model, Boolean isFastMode) { }
	// RVA: 0x2bfaab4 VA: 0x7595212ab4
	public Void .ctor() { }
}
```