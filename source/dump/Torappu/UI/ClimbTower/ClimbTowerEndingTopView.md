# ClimbTowerEndingTopView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `Image _imgTowerIcon`

- `GameObject _imgBkgNormal`

- `GameObject _imgBkgHard`

- `TwoStateToggle _finishToggle`

- `Text _textFloorCurr`

- `Text _textFloorTarget`

- `Image _imgBkgLight`

- `ClimbTowerTowerLayerStack _layerStackPrefab`

- `RectTransform _layerStackViewHolder`

- `AnimationWrapper _animShow`

- `ClimbTowerTowerLayerSelectArrowSimple _selectArrowPrefab`

- `ClimbTowerTowerLayerGodCardTipsWithAttach _godCardTipsPrefab`

- `Color _colorHard`

- `Color _colorNormal`

- `Int32 m_currFloor`

- `Boolean m_inited`

- `Adapter m_adapter`

- `ClimbTowerEndingTopViewModel m_cachedModel`

- `ClimbTowerTowerLayerStack m_TowerlayerStack`

- `String m_cachedTowerId`

- `Boolean m_canClick`

- `Boolean m_cachedIsHardMode`

- `ClimbTowerEndingTopState <state>k__BackingField`

- `UIPage <page>k__BackingField`


## Properties

- `Boolean canClick`

- `ClimbTowerEndingTopState state`

- `UIPage page`


## Methods

- `Boolean get_canClick()`

- `ClimbTowerEndingTopState get_state()`

- `Void set_state(ClimbTowerEndingTopState)`

- `UIPage get_page()`

- `Void set_page(UIPage)`

- `Void _InitIfNot()`

- `Void Render(ClimbTowerEndingTopViewModel)`

- `IEnumerator ShowCoroutine()`

- `IEnumerator _PlayFlashSoundFx()`

- `IEnumerator _FloorTextAnimCoroutine()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerEndingTopView : MonoBehaviour, IHotfixable
{
	private const String FLOOR_TARGET_FORMAT; // 0x0
	private const String ANIM_SHOW_NAME; // 0x0
	private Image _imgTowerIcon; // 0x18
	private GameObject _imgBkgNormal; // 0x20
	private GameObject _imgBkgHard; // 0x28
	private TwoStateToggle _finishToggle; // 0x30
	private Text _textFloorCurr; // 0x38
	private Text _textFloorTarget; // 0x40
	private Image _imgBkgLight; // 0x48
	private ClimbTowerTowerLayerStack _layerStackPrefab; // 0x50
	private RectTransform _layerStackViewHolder; // 0x58
	private AnimationWrapper _animShow; // 0x60
	private ClimbTowerTowerLayerSelectArrowSimple _selectArrowPrefab; // 0x68
	private ClimbTowerTowerLayerGodCardTipsWithAttach _godCardTipsPrefab; // 0x70
	private Color _colorHard; // 0x78
	private Color _colorNormal; // 0x88
	private Int32 m_currFloor; // 0x98
	private Boolean m_inited; // 0x9c
	private Adapter m_adapter; // 0xa0
	private ClimbTowerEndingTopViewModel m_cachedModel; // 0xa8
	private ClimbTowerTowerLayerStack m_TowerlayerStack; // 0xb0
	private String m_cachedTowerId; // 0xb8
	private Boolean m_canClick; // 0xc0
	private Boolean m_cachedIsHardMode; // 0xc1
	private ClimbTowerEndingTopState <state>k__BackingField; // 0xc8
	private UIPage <page>k__BackingField; // 0xd0
	private static DelegateBridge __Hotfix0_get_canClick; // 0x0
	private static DelegateBridge __Hotfix0_get_state; // 0x8
	private static DelegateBridge __Hotfix0_set_state; // 0x10
	private static DelegateBridge __Hotfix0_get_page; // 0x18
	private static DelegateBridge __Hotfix0_set_page; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0_Render; // 0x30
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x38
	private static DelegateBridge __Hotfix0__PlayFlashSoundFx; // 0x40
	private static DelegateBridge __Hotfix0__FloorTextAnimCoroutine; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public Boolean canClick { get; }
	private ClimbTowerEndingTopState state { get; set; }
	private UIPage page { get; set; }

	// RVA: 0x2c9f770 VA: 0x75952b7770
	public Boolean get_canClick() { }
	// RVA: 0x2c9fb38 VA: 0x75952b7b38
	private ClimbTowerEndingTopState get_state() { }
	// RVA: 0x2c9ee7c VA: 0x75952b6e7c
	public Void set_state(ClimbTowerEndingTopState value) { }
	// RVA: 0x2c9fba0 VA: 0x75952b7ba0
	private UIPage get_page() { }
	// RVA: 0x2c9ef00 VA: 0x75952b6f00
	public Void set_page(UIPage value) { }
	// RVA: 0x2c9fc08 VA: 0x75952b7c08
	private Void _InitIfNot() { }
	// RVA: 0x2c9ef84 VA: 0x75952b6f84
	public Void Render(ClimbTowerEndingTopViewModel viewModel) { }
	// RVA: 0x2c9f458 VA: 0x75952b7458
	public IEnumerator ShowCoroutine() { }
	// RVA: 0x2c9fe18 VA: 0x75952b7e18
	private IEnumerator _PlayFlashSoundFx() { }
	// RVA: 0x2c9fedc VA: 0x75952b7edc
	private IEnumerator _FloorTextAnimCoroutine() { }
	// RVA: 0x2c9ffb0 VA: 0x75952b7fb0
	public Void .ctor() { }
}
```