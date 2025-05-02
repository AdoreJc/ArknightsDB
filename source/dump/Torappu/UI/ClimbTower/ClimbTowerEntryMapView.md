# ClimbTowerEntryMapView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `SimpleLayoutContent _content`

- `RectTransform _viewPort`

- `Adpter m_adapter`

- `Boolean m_hasInited`

- `Boolean m_isContentPosInited`

- `UIPage <page>k__BackingField`


## Properties

- `UIPage page`


## Methods

- `Void set_onTowerClicked(Action`2)`

- `UIPage get_page()`

- `Void set_page(UIPage)`

- `IEnumerator RefreshContentPosition(Boolean)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerEntryMapView : DataBinder`1
{
	private const Int32 CONTENT_X_DELTA_IF_TRAIN_COMPLETE; // 0x0
	private SimpleLayoutContent _content; // 0x20
	private RectTransform _viewPort; // 0x28
	private SizeConfig[] _towerSizeConfigs; // 0x30
	private Adpter m_adapter; // 0x38
	private Boolean m_hasInited; // 0x40
	private Boolean m_isContentPosInited; // 0x41
	private Dictionary`2 m_itemSizeConfigMap; // 0x48
	private Action`2 <onTowerClicked>k__BackingField; // 0x50
	private UIPage <page>k__BackingField; // 0x58
	private static DelegateBridge __Hotfix0_get_onTowerClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onTowerClicked; // 0x8
	private static DelegateBridge __Hotfix0_get_page; // 0x10
	private static DelegateBridge __Hotfix0_set_page; // 0x18
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x20
	private static DelegateBridge __Hotfix0_RefreshContentPosition; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	private Action`2 onTowerClicked { get; set; }
	private UIPage page { get; set; }

	// RVA: 0x2c668c0 VA: 0x759527e8c0
	private Action`2 get_onTowerClicked() { }
	// RVA: 0x2c66928 VA: 0x759527e928
	public Void set_onTowerClicked(Action`2 value) { }
	// RVA: 0x2c669ac VA: 0x759527e9ac
	private UIPage get_page() { }
	// RVA: 0x2c66a14 VA: 0x759527ea14
	public Void set_page(UIPage value) { }
	// RVA: 0x2c66a98 VA: 0x759527ea98
	public override Void OnValueChanged(ClimbTowerEntryMapProperty property) { }
	// RVA: 0x2c66d84 VA: 0x759527ed84
	private IEnumerator RefreshContentPosition(Boolean isTrainComplete) { }
	// RVA: 0x2c66bb8 VA: 0x759527ebb8
	private Void _InitIfNot() { }
	// RVA: 0x2c66f08 VA: 0x759527ef08
	public Void .ctor() { }
}
```