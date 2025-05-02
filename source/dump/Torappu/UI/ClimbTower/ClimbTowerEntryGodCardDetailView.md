# ClimbTowerEntryGodCardDetailView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `Text _seasonNumberTxt`

- `Image _imgCardIcon`

- `Text _textCardName`

- `Text _textCardDesc`

- `GameObject _panelTip`

- `Text _textBindTowerName`

- `TwoStateToggle _toggleGradient`

- `SimpleLayoutContent _towerContent`

- `GameObject _unCompleteObj`

- `GameObject _completeObj`

- `Boolean m_hasInited`

- `Adapter m_adapter`

- `UIPage <page>k__BackingField`


## Properties

- `UIPage page`


## Methods

- `UIPage get_page()`

- `Void set_page(UIPage)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerEntryGodCardDetailView : DataBinder`1, IHotfixable
{
	private Text _seasonNumberTxt; // 0x20
	private Image _imgCardIcon; // 0x28
	private Text _textCardName; // 0x30
	private Text _textCardDesc; // 0x38
	private GameObject _panelTip; // 0x40
	private Text _textBindTowerName; // 0x48
	private ClimbTowerEntryGodCardSubCardView[] _panelSubCardView; // 0x50
	private TwoStateToggle _toggleGradient; // 0x58
	private SimpleLayoutContent _towerContent; // 0x60
	private GameObject _unCompleteObj; // 0x68
	private GameObject _completeObj; // 0x70
	private Boolean m_hasInited; // 0x78
	private List`1 m_towerStatus; // 0x80
	private Adapter m_adapter; // 0x88
	private UIPage <page>k__BackingField; // 0x90
	private static DelegateBridge __Hotfix0_get_page; // 0x0
	private static DelegateBridge __Hotfix0_set_page; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private UIPage page { get; set; }

	// RVA: 0x2c65ca8 VA: 0x759527dca8
	private UIPage get_page() { }
	// RVA: 0x2c65d10 VA: 0x759527dd10
	public Void set_page(UIPage value) { }
	// RVA: 0x2c65d94 VA: 0x759527dd94
	public override Void OnValueChanged(ClimbTowerEntryGodCardDetailProperty property) { }
	// RVA: 0x2c660bc VA: 0x759527e0bc
	private Void _InitIfNot() { }
	// RVA: 0x2c664fc VA: 0x759527e4fc
	public Void .ctor() { }
}
```