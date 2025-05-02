# RoguelikeCharCommonCharView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Image _charHeadIcon2`

- `Image _professionIcon`

- `Image _evolveImg`

- `Image _potentialImg`

- `Text _levelTxt`

- `Text _charName`

- `UIAtlasImage _charNameDeco`

- `SimpleLayoutContent _content`

- `GameObject _selectOutLine`

- `Text _selectIndex`

- `GameObject _upgradeFlag`

- `GameObject _charPart`

- `GameObject _buyPart`

- `GameObject _isFree`

- `GameObject _isNPC`

- `GameObject _isFriendAssist`

- `GameObject _isMonthlyTeam`

- `UIAtlasImage _monthlyImg`

- `Text _monthlyCharCardTagName`

- `GameObject _isUpgradeFlag`

- `RectTransform _conflictPanelHolder`

- `Text _popText`

- `Image _rarityImg`

- `Text _upType`

- `Image _branchIcon`

- `UIColorGraphic _colorGraphic`

- `CanvasGroup _canvasGroup`

- `Single _fadeInDur`

- `UIIntEvent charClick`

- `UIIntStringEvent charSkillClick`

- `Int32 m_cacheInstId`

- `RoguelikeSelectCharConflictPanel m_conflictPanel`

- `SkillAdapter m_adapter`


## Methods

- `Void _InitIfNot()`

- `Void OnClick()`

- `Void OnClickSkill(String)`

- `Void AsyncSetData(AsyncParam)`

- `Void AsyncShow()`

- `Void Render(RoguelikeCharCardViewModel, ShowConfig, Boolean, Int32)`

- `Boolean _OverrideRaritySprite(RoguelikeCharCardViewModel, ShowConfig, Boolean, Int32, out)`

- `Boolean _OverrideCharNameColor(RoguelikeCharCardViewModel, ShowConfig, Boolean, Int32, out)`

- `Boolean _OverrideConflictPanel(RoguelikeCharCardViewModel, ShowConfig, Boolean, Int32, out, out)`

- `Boolean _OverrideValid(RoguelikeCharCardViewModel, ShowConfig, Boolean, Int32, out)`

- `Void _DealWithNPC(RoguelikeCharCardViewModel, ShowConfig)`

- `Void _DealWithFriend(RoguelikeCharCardViewModel, ShowConfig)`

- `Void _DealWithUpgradeFlag(RoguelikeCharCardViewModel, ShowConfig)`

- `Void _DealWithMonthlyTeamFlag(RoguelikeCharCardViewModel, ShowConfig)`

- `Void _DealWithIsFreeFlag(RoguelikeCharCardViewModel, ShowConfig)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeCharCommonCharView : MonoBehaviour, IHotfixable, IAsyncShowEffect, IAsyncDataView`1
{
	private Image _charHeadIcon2; // 0x18
	private Image _professionIcon; // 0x20
	private Image _evolveImg; // 0x28
	private Image _potentialImg; // 0x30
	private Text _levelTxt; // 0x38
	private Text _charName; // 0x40
	private UIAtlasImage _charNameDeco; // 0x48
	private SimpleLayoutContent _content; // 0x50
	private GameObject _selectOutLine; // 0x58
	private Text _selectIndex; // 0x60
	private GameObject _upgradeFlag; // 0x68
	private GameObject _charPart; // 0x70
	private GameObject _buyPart; // 0x78
	private GameObject _isFree; // 0x80
	private GameObject _isNPC; // 0x88
	private GameObject _isFriendAssist; // 0x90
	private GameObject _isMonthlyTeam; // 0x98
	private UIAtlasImage _monthlyImg; // 0xa0
	private Text _monthlyCharCardTagName; // 0xa8
	private GameObject _isUpgradeFlag; // 0xb0
	private RectTransform _conflictPanelHolder; // 0xb8
	private Text _popText; // 0xc0
	private Image _rarityImg; // 0xc8
	private Text _upType; // 0xd0
	private Image _branchIcon; // 0xd8
	private UIColorGraphic _colorGraphic; // 0xe0
	private CanvasGroup _canvasGroup; // 0xe8
	private Single _fadeInDur; // 0xf0
	public UIIntEvent charClick; // 0xf8
	public UIIntStringEvent charSkillClick; // 0x100
	public List`1 plugins; // 0x108
	private Int32 m_cacheInstId; // 0x110
	private RoguelikeSelectCharConflictPanel m_conflictPanel; // 0x118
	private SkillAdapter m_adapter; // 0x120
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnClick; // 0x8
	private static DelegateBridge __Hotfix0_OnClickSkill; // 0x10
	private static DelegateBridge __Hotfix0_AsyncSetData; // 0x18
	private static DelegateBridge __Hotfix0_AsyncShow; // 0x20
	private static DelegateBridge __Hotfix0_Render; // 0x28
	private static DelegateBridge __Hotfix0__OverrideRaritySprite; // 0x30
	private static DelegateBridge __Hotfix0__OverrideCharNameColor; // 0x38
	private static DelegateBridge __Hotfix0__OverrideConflictPanel; // 0x40
	private static DelegateBridge __Hotfix0__OverrideValid; // 0x48
	private static DelegateBridge __Hotfix0__DealWithNPC; // 0x50
	private static DelegateBridge __Hotfix0__DealWithFriend; // 0x58
	private static DelegateBridge __Hotfix0__DealWithUpgradeFlag; // 0x60
	private static DelegateBridge __Hotfix0__DealWithMonthlyTeamFlag; // 0x68
	private static DelegateBridge __Hotfix0__DealWithIsFreeFlag; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78


	// RVA: 0x2ac90dc VA: 0x75950e10dc
	private Void _InitIfNot() { }
	// RVA: 0x2ac9268 VA: 0x75950e1268
	public Void OnClick() { }
	// RVA: 0x2ac92fc VA: 0x75950e12fc
	public Void OnClickSkill(String skillId) { }
	// RVA: 0x2ac93b8 VA: 0x75950e13b8
	public Void AsyncSetData(AsyncParam param) { }
	// RVA: 0x2ac9f38 VA: 0x75950e1f38
	public Void AsyncShow() { }
	// RVA: 0x2ac9498 VA: 0x75950e1498
	public Void Render(RoguelikeCharCardViewModel viewModel, ShowConfig showConfig, Boolean isSelect, Int32 selectIndex) { }
	// RVA: 0x2aca1b8 VA: 0x75950e21b8
	private Boolean _OverrideRaritySprite(RoguelikeCharCardViewModel viewModel, ShowConfig showConfig, Boolean isSelect, Int32 selectIndex, out Sprite overrideSprite) { }
	// RVA: 0x2aca394 VA: 0x75950e2394
	private Boolean _OverrideCharNameColor(RoguelikeCharCardViewModel viewModel, ShowConfig showConfig, Boolean isSelect, Int32 selectIndex, out Color overrideColor) { }
	// RVA: 0x2aca568 VA: 0x75950e2568
	private Boolean _OverrideConflictPanel(RoguelikeCharCardViewModel viewModel, ShowConfig showConfig, Boolean isSelect, Int32 selectIndex, out RoguelikeSelectCharConflictPanel overridePrefab, out IRoguelikeCharCardPlugin plugin) { }
	// RVA: 0x2ac9fe4 VA: 0x75950e1fe4
	private Boolean _OverrideValid(RoguelikeCharCardViewModel viewModel, ShowConfig showConfig, Boolean isSelect, Int32 selectIndex, out Boolean overrideValid) { }
	// RVA: 0x2aca880 VA: 0x75950e2880
	private Void _DealWithNPC(RoguelikeCharCardViewModel viewModel, ShowConfig showConfig) { }
	// RVA: 0x2aca7e4 VA: 0x75950e27e4
	private Void _DealWithFriend(RoguelikeCharCardViewModel viewModel, ShowConfig showConfig) { }
	// RVA: 0x2acaa58 VA: 0x75950e2a58
	private Void _DealWithUpgradeFlag(RoguelikeCharCardViewModel viewModel, ShowConfig showConfig) { }
	// RVA: 0x2aca91c VA: 0x75950e291c
	private Void _DealWithMonthlyTeamFlag(RoguelikeCharCardViewModel viewModel, ShowConfig showConfig) { }
	// RVA: 0x2acab00 VA: 0x75950e2b00
	private Void _DealWithIsFreeFlag(RoguelikeCharCardViewModel viewModel, ShowConfig showConfig) { }
	// RVA: 0x2acab9c VA: 0x75950e2b9c
	public Void .ctor() { }
}
```