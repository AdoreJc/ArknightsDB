# ClimbTowerEntryTowerView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `Vector2 _normalUpPos`

- `Vector2 _normalDownPos`

- `RectTransform _rectNormalTower`

- `LayoutElement _layoutElement`

- `GameObject _panelTrain`

- `GameObject _trainInBattle`

- `GameObject _panelTower`

- `Image _stageIcon`

- `Image _towerIcon`

- `GameObject _panelTrackPoint`

- `GameObject _replicatedBg`

- `GameObject _replicatedNotCheckedTips`

- `TwoStateToggle _toggleInBattle`

- `Text _textTowerSubname`

- `TwoStateToggle _toggleProgress`

- `TwoStateToggle _toggleProgressComplete`

- `Text _textFloorCurr`

- `Text _textFloorTarget`

- `GameObject _panelProgress`

- `Image _godCardImage`

- `Text _textTrapCount`

- `Text _textCharCount`

- `CanvasGroup _selfCanvasGroup`

- `String m_towerId`

- `ClimbTowerTowerType m_towerType`

- `UIPage <page>k__BackingField`


## Properties

- `UIPage page`


## Methods

- `Void set_onTowerClicked(Action`2)`

- `UIPage get_page()`

- `Void set_page(UIPage)`

- `Void Render(ClimbTowerEntryMapTowerModel, Vector2, Int32)`

- `Void EventOnTowerClicked()`

- `Void _RenderTowerButton(ClimbTowerEntryMapTowerModel, Int32)`

- `Void _RenderTrainEntryButton(ClimbTowerEntryMapTowerModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerEntryTowerView : MonoBehaviour, IHotfixable
{
	private const String FLOOR_TARGET_FORMAT; // 0x0
	private Vector2 _normalUpPos; // 0x18
	private Vector2 _normalDownPos; // 0x20
	private RectTransform _rectNormalTower; // 0x28
	private LayoutElement _layoutElement; // 0x30
	private GameObject _panelTrain; // 0x38
	private GameObject _trainInBattle; // 0x40
	private GameObject _panelTower; // 0x48
	private Image _stageIcon; // 0x50
	private Image _towerIcon; // 0x58
	private GameObject _panelTrackPoint; // 0x60
	private GameObject _replicatedBg; // 0x68
	private GameObject _replicatedNotCheckedTips; // 0x70
	private TwoStateToggle _toggleInBattle; // 0x78
	private TwoStateToggle[] _toggleInBattleHard; // 0x80
	private Text[] _textTowerName; // 0x88
	private Text _textTowerSubname; // 0x90
	private ClimbTowerEntryTowerProgressView[] _progressView; // 0x98
	private TwoStateToggle _toggleProgress; // 0xa0
	private TwoStateToggle _toggleProgressComplete; // 0xa8
	private Text _textFloorCurr; // 0xb0
	private Text _textFloorTarget; // 0xb8
	private GameObject _panelProgress; // 0xc0
	private Image _godCardImage; // 0xc8
	private Text _textTrapCount; // 0xd0
	private Text _textCharCount; // 0xd8
	private CanvasGroup _selfCanvasGroup; // 0xe0
	private String m_towerId; // 0xe8
	private ClimbTowerTowerType m_towerType; // 0xf0
	private Action`2 <onTowerClicked>k__BackingField; // 0xf8
	private UIPage <page>k__BackingField; // 0x100
	private static DelegateBridge __Hotfix0_get_onTowerClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onTowerClicked; // 0x8
	private static DelegateBridge __Hotfix0_get_page; // 0x10
	private static DelegateBridge __Hotfix0_set_page; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge __Hotfix0_EventOnTowerClicked; // 0x28
	private static DelegateBridge __Hotfix0__RenderTowerButton; // 0x30
	private static DelegateBridge __Hotfix0__RenderTrainEntryButton; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	private Action`2 onTowerClicked { get; set; }
	private UIPage page { get; set; }

	// RVA: 0x2c6784c VA: 0x759527f84c
	private Action`2 get_onTowerClicked() { }
	// RVA: 0x2c67240 VA: 0x759527f240
	public Void set_onTowerClicked(Action`2 value) { }
	// RVA: 0x2c678b4 VA: 0x759527f8b4
	private UIPage get_page() { }
	// RVA: 0x2c672c4 VA: 0x759527f2c4
	public Void set_page(UIPage value) { }
	// RVA: 0x2c67348 VA: 0x759527f348
	public Void Render(ClimbTowerEntryMapTowerModel model, Vector2 size, Int32 position) { }
	// RVA: 0x2c67edc VA: 0x759527fedc
	public Void EventOnTowerClicked() { }
	// RVA: 0x2c6791c VA: 0x759527f91c
	private Void _RenderTowerButton(ClimbTowerEntryMapTowerModel model, Int32 position) { }
	// RVA: 0x2c67e08 VA: 0x759527fe08
	private Void _RenderTrainEntryButton(ClimbTowerEntryMapTowerModel model) { }
	// RVA: 0x2c67fb8 VA: 0x759527ffb8
	public Void .ctor() { }
}
```