# ClimbTowerEntryMissionItemView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `Image _imgTowerIcon`

- `GameObject _imgSeasonTitle`

- `Text _seasonNumTxt`

- `Text _seasonNameTxt`

- `GameObject _panelGodCard`

- `Image _imgGodCardIcon`

- `Slider _sliderProgress`

- `Text _textProgress`

- `Text _textDesc`

- `UIColorGraphic _graphicHotSpot`

- `GameObject _panelOutLight`

- `SimpleLayoutContent _rewardItemContent`

- `GameObject _panelReceived`

- `GameObject _panelNeedReceive`

- `Single _itemCardScale`

- `String m_cachedMissionId`

- `Boolean m_hasInited`

- `Adapter m_adapter`


## Methods

- `Void set_onClicked(Action`1)`

- `Void Render(ClimbTowerEntryMissionItemViewModel, UIPage)`

- `Void OnClick()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerEntryMissionItemView : MonoBehaviour, IHotfixable
{
	private const String PROGRESS_RICH_FORMAT; // 0x0
	private Image _imgTowerIcon; // 0x18
	private GameObject _imgSeasonTitle; // 0x20
	private Text _seasonNumTxt; // 0x28
	private Text _seasonNameTxt; // 0x30
	private GameObject _panelGodCard; // 0x38
	private Image _imgGodCardIcon; // 0x40
	private TwoStateToggle[] _toggleComplete; // 0x48
	private Slider _sliderProgress; // 0x50
	private Text _textProgress; // 0x58
	private Text _textDesc; // 0x60
	private UIColorGraphic _graphicHotSpot; // 0x68
	private GameObject _panelOutLight; // 0x70
	private SimpleLayoutContent _rewardItemContent; // 0x78
	private GameObject _panelReceived; // 0x80
	private GameObject _panelNeedReceive; // 0x88
	private Single _itemCardScale; // 0x90
	private String m_cachedMissionId; // 0x98
	private Boolean m_hasInited; // 0xa0
	private Adapter m_adapter; // 0xa8
	private List`1 m_rewardList; // 0xb0
	private Action`1 <onClicked>k__BackingField; // 0xb8
	private static DelegateBridge __Hotfix0_get_onClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onClicked; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_OnClick; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Action`1 onClicked { get; set; }

	// RVA: 0x2c6959c VA: 0x759528159c
	private Action`1 get_onClicked() { }
	// RVA: 0x2c68554 VA: 0x7595280554
	public Void set_onClicked(Action`1 value) { }
	// RVA: 0x2c685d8 VA: 0x75952805d8
	public Void Render(ClimbTowerEntryMissionItemViewModel viewModel, UIPage page) { }
	// RVA: 0x2c696d4 VA: 0x75952816d4
	public Void OnClick() { }
	// RVA: 0x2c69604 VA: 0x7595281604
	private Void _InitIfNot() { }
	// RVA: 0x2c69818 VA: 0x7595281818
	public Void .ctor() { }
}
```