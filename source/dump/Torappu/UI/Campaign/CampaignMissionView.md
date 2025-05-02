# CampaignMissionView

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `SimpleLayoutContent _permObjLayoutContent`

- `SimpleLayoutContent _commonObjLayoutContent`

- `RectTransform _panelCommonMissionList`

- `RectTransform _panelNoCommonMission`

- `Button _buttonRedirect`

- `Text _textProgress`

- `Slider _sliderProgress`

- `Text _textRemainTime`

- `Boolean m_inited`

- `PermanentObjAdapter m_permObjAdapter`

- `CommonObjAdapter m_commonObjAdapter`


## Methods

- `Void set_onPermObjClicked(Action`1)`

- `Void set_onCommonObjClicked(Action`1)`

- `Void Render(CampaignMissionStateBean)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class CampaignMissionView : MonoBehaviour, IHotfixable
{
	private const String TEXT_PROGRESS_FORMAT; // 0x0
	private SimpleLayoutContent _permObjLayoutContent; // 0x18
	private SimpleLayoutContent _commonObjLayoutContent; // 0x20
	private RectTransform _panelCommonMissionList; // 0x28
	private RectTransform _panelNoCommonMission; // 0x30
	private Button _buttonRedirect; // 0x38
	private Text _textProgress; // 0x40
	private Slider _sliderProgress; // 0x48
	private Text _textRemainTime; // 0x50
	private Boolean m_inited; // 0x58
	private PermanentObjAdapter m_permObjAdapter; // 0x60
	private CommonObjAdapter m_commonObjAdapter; // 0x68
	private Action`1 <onPermObjClicked>k__BackingField; // 0x70
	private Action`1 <onCommonObjClicked>k__BackingField; // 0x78
	private static DelegateBridge __Hotfix0_get_onPermObjClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onPermObjClicked; // 0x8
	private static DelegateBridge __Hotfix0_get_onCommonObjClicked; // 0x10
	private static DelegateBridge __Hotfix0_set_onCommonObjClicked; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Action`1 onPermObjClicked { get; set; }
	public Action`1 onCommonObjClicked { get; set; }

	// RVA: 0x2dd077c VA: 0x75953e877c
	public Action`1 get_onPermObjClicked() { }
	// RVA: 0x2dcf0e4 VA: 0x75953e70e4
	public Void set_onPermObjClicked(Action`1 value) { }
	// RVA: 0x2dd07e4 VA: 0x75953e87e4
	public Action`1 get_onCommonObjClicked() { }
	// RVA: 0x2dcf168 VA: 0x75953e7168
	public Void set_onCommonObjClicked(Action`1 value) { }
	// RVA: 0x2dce9ec VA: 0x75953e69ec
	public Void Render(CampaignMissionStateBean stateBean) { }
	// RVA: 0x2dd084c VA: 0x75953e884c
	private Void _InitIfNot() { }
	// RVA: 0x2dd0b3c VA: 0x75953e8b3c
	public Void .ctor() { }
}
```