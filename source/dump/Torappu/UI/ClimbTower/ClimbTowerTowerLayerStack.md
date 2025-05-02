# ClimbTowerTowerLayerStack

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `ClimbTowerLayerCard _prefabNormal`

- `ClimbTowerLayerCard _prefabSpecial`

- `ClimbTowerLayerCard _prefabBoss`

- `Int32 _paddingTop`

- `Int32 _paddingBottom`

- `RectTransform _transLayerCardHolder`

- `UIAtlasImage _imgLayerBg`

- `UIAtlasObject _layerBgAtlas`

- `RectTransform _transArrowHolder`

- `Int32 _paddingBeforeGod`

- `Int32 _godCardOffset`

- `RectTransform _transGodCardTipsHolder`

- `Single m_sizeOnAxis`

- `Tween m_arrowMoveTween`

- `ClimbTowerTowerLayerBaseSelectArrow m_selectArrow`

- `ClimbTowerTowerLayerBaseGodCardTips m_godCardTips`

- `ClimbTowerTowerLayerStackAdapter m_adapter`


## Properties

- `Single minWidth`

- `Single minHeight`

- `Single flexibleWidth`

- `Single flexibleHeight`

- `Int32 layoutPriority`

- `Single preferredWidth`

- `Single preferredHeight`

- `ClimbTowerTowerLayerStackAdapter adapter`

- `UIAtlasImage imgLayerBg`


## Methods

- `Single get_minWidth()`

- `Single get_minHeight()`

- `Single get_flexibleWidth()`

- `Single get_flexibleHeight()`

- `Int32 get_layoutPriority()`

- `Single get_preferredWidth()`

- `Single get_preferredHeight()`

- `Void CalculateLayoutInputHorizontal()`

- `Void CalculateLayoutInputVertical()`

- `Void set_adapter(ClimbTowerTowerLayerStackAdapter)`

- `UIAtlasImage get_imgLayerBg()`

- `Void _ObserveAdapterConstructed(ClimbTowerTowerLayerStackAdapter)`

- `Void _ObserverAdapterUpdated(ClimbTowerTowerLayerStackAdapter)`

- `Void _ConstructViews()`

- `Void _RefreshViews()`

- `Void _RenderArrow(Boolean)`

- `Void _RenderGodCardLayerTips()`

- `Void _RenderBg()`

- `Void <_RenderArrow>b__43_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerTowerLayerStack : MonoBehaviour, ILayoutElement, IHotfixable
{
	private const Single ARROW_MOVE_DURATION; // 0x0
	private ClimbTowerLayerCard _prefabNormal; // 0x18
	private ClimbTowerLayerCard _prefabSpecial; // 0x20
	private ClimbTowerLayerCard _prefabBoss; // 0x28
	private Int32 _paddingTop; // 0x30
	private Int32 _paddingBottom; // 0x34
	private RectTransform _transLayerCardHolder; // 0x38
	private UIAtlasImage _imgLayerBg; // 0x40
	private UIAtlasObject _layerBgAtlas; // 0x48
	private RectTransform _transArrowHolder; // 0x50
	private Int32 _paddingBeforeGod; // 0x58
	private Int32 _godCardOffset; // 0x5c
	private RectTransform _transGodCardTipsHolder; // 0x60
	private const String TOWER_BG_PREFIX; // 0x0
	private Single m_sizeOnAxis; // 0x68
	private Tween m_arrowMoveTween; // 0x70
	private ClimbTowerTowerLayerBaseSelectArrow m_selectArrow; // 0x78
	private ClimbTowerTowerLayerBaseGodCardTips m_godCardTips; // 0x80
	private ClimbTowerTowerLayerStackAdapter m_adapter; // 0x88
	private static DelegateBridge __Hotfix0_get_minWidth; // 0x0
	private static DelegateBridge __Hotfix0_get_minHeight; // 0x8
	private static DelegateBridge __Hotfix0_get_flexibleWidth; // 0x10
	private static DelegateBridge __Hotfix0_get_flexibleHeight; // 0x18
	private static DelegateBridge __Hotfix0_get_layoutPriority; // 0x20
	private static DelegateBridge __Hotfix0_get_preferredWidth; // 0x28
	private static DelegateBridge __Hotfix0_get_preferredHeight; // 0x30
	private static DelegateBridge __Hotfix0_CalculateLayoutInputHorizontal; // 0x38
	private static DelegateBridge __Hotfix0_CalculateLayoutInputVertical; // 0x40
	private static DelegateBridge __Hotfix0_set_adapter; // 0x48
	private static DelegateBridge __Hotfix0_get_imgLayerBg; // 0x50
	private static DelegateBridge __Hotfix0__ObserveAdapterConstructed; // 0x58
	private static DelegateBridge __Hotfix0__ObserverAdapterUpdated; // 0x60
	private static DelegateBridge __Hotfix0__ConstructViews; // 0x68
	private static DelegateBridge __Hotfix0__RefreshViews; // 0x70
	private static DelegateBridge __Hotfix0__RenderArrow; // 0x78
	private static DelegateBridge __Hotfix0__RenderGodCardLayerTips; // 0x80
	private static DelegateBridge __Hotfix0__RenderBg; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90

	public Single minWidth { get; }
	public Single minHeight { get; }
	public Single flexibleWidth { get; }
	public Single flexibleHeight { get; }
	public Int32 layoutPriority { get; }
	public Single preferredWidth { get; }
	public Single preferredHeight { get; }
	public ClimbTowerTowerLayerStackAdapter adapter { set; }
	public UIAtlasImage imgLayerBg { get; }

	// RVA: 0x2c7b820 VA: 0x7595293820
	public Single get_minWidth() { }
	// RVA: 0x2c7b888 VA: 0x7595293888
	public Single get_minHeight() { }
	// RVA: 0x2c7b8f0 VA: 0x75952938f0
	public Single get_flexibleWidth() { }
	// RVA: 0x2c7b958 VA: 0x7595293958
	public Single get_flexibleHeight() { }
	// RVA: 0x2c7b9c0 VA: 0x75952939c0
	public Int32 get_layoutPriority() { }
	// RVA: 0x2c7ba24 VA: 0x7595293a24
	public Single get_preferredWidth() { }
	// RVA: 0x2c7ba8c VA: 0x7595293a8c
	public Single get_preferredHeight() { }
	// RVA: 0x2c7baf4 VA: 0x7595293af4
	public Void CalculateLayoutInputHorizontal() { }
	// RVA: 0x2c7bb58 VA: 0x7595293b58
	public Void CalculateLayoutInputVertical() { }
	// RVA: 0x2c73d74 VA: 0x759528bd74
	public Void set_adapter(ClimbTowerTowerLayerStackAdapter value) { }
	// RVA: 0x2c7a0e4 VA: 0x75952920e4
	public UIAtlasImage get_imgLayerBg() { }
	// RVA: 0x2c7bbbc VA: 0x7595293bbc
	private Void _ObserveAdapterConstructed(ClimbTowerTowerLayerStackAdapter adapter) { }
	// RVA: 0x2c7bf54 VA: 0x7595293f54
	private Void _ObserverAdapterUpdated(ClimbTowerTowerLayerStackAdapter adapter) { }
	// RVA: 0x2c7bc54 VA: 0x7595293c54
	private Void _ConstructViews() { }
	// RVA: 0x2c7bfec VA: 0x7595293fec
	private Void _RefreshViews() { }
	// RVA: 0x2c7c0b0 VA: 0x75952940b0
	private Void _RenderArrow(Boolean fastMode) { }
	// RVA: 0x2c7c440 VA: 0x7595294440
	private Void _RenderGodCardLayerTips() { }
	// RVA: 0x2c7c6cc VA: 0x75952946cc
	private Void _RenderBg() { }
	// RVA: 0x2c7c8b4 VA: 0x75952948b4
	public Void .ctor() { }
	// RVA: 0x2c7c924 VA: 0x7595294924
	private Void <_RenderArrow>b__43_0() { }
}
```