# MainMissionTask

**Namespace:** `Torappu.UI.Mission`


## Fields

- `Text _description`

- `Image _requirementBackground`

- `Text _requirementText`

- `Image _acceptButtonImage`

- `Image _acceptButtonGlowImage`

- `Text _acceptButtonText`

- `MainMissionProgressItem _progressItemTypeOneReward`

- `MainMissionProgressItem _progressItemTypeTwoReward`

- `MissionRewardPreviewItem _rewardItemOne`

- `MissionRewardPreviewItem _rewardItemTwo`

- `GameObject _objAcceptTips`

- `GameObject _finished`

- `GameObject _unfinished`

- `GameObject _hotSpot`

- `Image _backgroundDownDecImage`

- `Image _backgroundImage`

- `GameObject _backgroundGlow`

- `GameObject _twoBackPart`

- `GameObject _threeBackPart`

- `GameObject _foldHotspot`

- `GameObject _foldBtn`

- `GameObject _foldBack`

- `Button _spreadBtn`

- `MainMissionTaskStyleHub _styleHub`

- `MissionViewModel m_dataCache`

- `UIStringEvent m_onFoldAction`

- `UIStringEvent m_onSpreadAction`


## Properties

- `String taskID`


## Methods

- `String get_taskID()`

- `Void OnClick()`

- `Void OnFinish()`

- `Void _ApplyViewStyle(MainMissionTaskViewStyleConfig)`

- `Void InitData(MissionViewModel, Option)`

- `Void OnClickFold()`

- `Void OnClickSpread()`

- `Void _ApplyStyle(Boolean, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Mission
public class MainMissionTask : MonoBehaviour, IHotfixable
{
	private const Single NORMAL_HEIGHT; // 0x0
	private const Single TWO_HEIGHT; // 0x0
	private const Single THREE_HEIGHT; // 0x0
	private const Single IS_LAST; // 0x0
	private Text _description; // 0x18
	private Text[] _descriptions; // 0x20
	private Image _requirementBackground; // 0x28
	private Text _requirementText; // 0x30
	private Image _acceptButtonImage; // 0x38
	private Image _acceptButtonGlowImage; // 0x40
	private Text _acceptButtonText; // 0x48
	private MainMissionProgressItem _progressItemTypeOneReward; // 0x50
	private MainMissionProgressItem _progressItemTypeTwoReward; // 0x58
	private MissionRewardPreviewItem _rewardItemOne; // 0x60
	private MissionRewardPreviewItem _rewardItemTwo; // 0x68
	private GameObject _objAcceptTips; // 0x70
	private GameObject _finished; // 0x78
	private GameObject _unfinished; // 0x80
	private GameObject[] _characterStrenthenPanels; // 0x88
	private GameObject[] _nonCharacterStrenthenPanels; // 0x90
	private GameObject _hotSpot; // 0x98
	private Image _backgroundDownDecImage; // 0xa0
	private Image _backgroundImage; // 0xa8
	private GameObject _backgroundGlow; // 0xb0
	private GameObject _twoBackPart; // 0xb8
	private GameObject _threeBackPart; // 0xc0
	private GameObject _foldHotspot; // 0xc8
	private GameObject _foldBtn; // 0xd0
	private GameObject _foldBack; // 0xd8
	private Button _spreadBtn; // 0xe0
	private MainMissionTaskStyleHub _styleHub; // 0xe8
	private MissionViewModel m_dataCache; // 0xf0
	private UIStringEvent m_onFoldAction; // 0xf8
	private UIStringEvent m_onSpreadAction; // 0x100
	private static DelegateBridge __Hotfix0_get_taskID; // 0x0
	private static DelegateBridge __Hotfix0_OnClick; // 0x8
	private static DelegateBridge __Hotfix0_OnFinish; // 0x10
	private static DelegateBridge __Hotfix0__ApplyViewStyle; // 0x18
	private static DelegateBridge __Hotfix0_InitData; // 0x20
	private static DelegateBridge __Hotfix0_OnClickFold; // 0x28
	private static DelegateBridge __Hotfix0_OnClickSpread; // 0x30
	private static DelegateBridge __Hotfix0__ApplyStyle; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public String taskID { get; }

	// RVA: 0x273e394 VA: 0x7594d56394
	public String get_taskID() { }
	// RVA: 0x273e410 VA: 0x7594d56410
	public Void OnClick() { }
	// RVA: 0x273e488 VA: 0x7594d56488
	public Void OnFinish() { }
	// RVA: 0x273e508 VA: 0x7594d56508
	private Void _ApplyViewStyle(MainMissionTaskViewStyleConfig style) { }
	// RVA: 0x273d3f4 VA: 0x7594d553f4
	public Void InitData(MissionViewModel data, Option option) { }
	// RVA: 0x273e9f0 VA: 0x7594d569f0
	public Void OnClickFold() { }
	// RVA: 0x273ea90 VA: 0x7594d56a90
	public Void OnClickSpread() { }
	// RVA: 0x273e8e4 VA: 0x7594d568e4
	private Void _ApplyStyle(Boolean unfinish, Boolean useCustomStyle) { }
	// RVA: 0x273ecf4 VA: 0x7594d56cf4
	public Void .ctor() { }
}
```