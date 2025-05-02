# SandboxV2CookFreeCookView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `GameObject _knownPanel`

- `GameObject _unknownPanel`

- `GameObject _stockPanel`

- `GameObject _mainNormalPanel`

- `GameObject _mainNoWaterPanel`

- `GameObject _mainLackPanel`

- `GameObject _mainFullPanel`

- `GameObject _subItemsPanel`

- `GameObject _subEmptyPanel`

- `GameObject _clearValidPanel`

- `GameObject _clearInvalidPanel`

- `GameObject _makeValidPanel`

- `GameObject _makeInvalidPanel`

- `SandboxV2CookDeckView _deckPrefab`

- `Transform _deckHolder`

- `SimpleLayoutContent _mainMatContent`

- `SimpleLayoutContent _subMatContent`

- `Single _itemCardScale`

- `Text _foodNameText`

- `Text _foodStockText`

- `Text _mainMatProgressText`

- `Text _subMatProgressText`

- `ScrollRect _rightScrollRect`

- `Boolean m_hasInited`

- `SandboxV2CookDeckView m_deckView`

- `Adapter m_mainMatAdapter`

- `Adapter m_subMatAdapter`

- `String m_cachedFoodId`

- `SandboxV2FoodData m_cachedFoodData`

- `String m_cachedFoodFallbackName`

- `String m_cachedWaterId`

- `Action <clearMatEvent>k__BackingField`

- `Action <makeEvent>k__BackingField`


## Properties

- `Action clearMatEvent`

- `Action makeEvent`


## Methods

- `Void set_selectMainMatEvent(Action`1)`

- `Void set_selectSubMatEvent(Action`1)`

- `Void set_deselectMainMatEvent(Action`1)`

- `Void set_deselectSubMatEvent(Action`1)`

- `Action get_clearMatEvent()`

- `Void set_clearMatEvent(Action)`

- `Action get_makeEvent()`

- `Void set_makeEvent(Action)`

- `Void OnClearMatEvent()`

- `Void OnMakeEvent()`

- `Void _InitIfNot()`

- `Void _OnSelectMainMatEvent(Int32)`

- `Void _OnSelectSubMatEvent(Int32)`

- `Void _OnDeselectMainMatEvent(Int32)`

- `Void _OnDeselectSubMatEvent(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2CookFreeCookView : SandboxV2AdminMainContentViewBase`1
{
	private const String MAT_PROGRESS_FORMAT; // 0x0
	private GameObject _knownPanel; // 0x38
	private GameObject _unknownPanel; // 0x40
	private GameObject _stockPanel; // 0x48
	private GameObject _mainNormalPanel; // 0x50
	private GameObject _mainNoWaterPanel; // 0x58
	private GameObject _mainLackPanel; // 0x60
	private GameObject _mainFullPanel; // 0x68
	private GameObject _subItemsPanel; // 0x70
	private GameObject _subEmptyPanel; // 0x78
	private GameObject _clearValidPanel; // 0x80
	private GameObject _clearInvalidPanel; // 0x88
	private GameObject _makeValidPanel; // 0x90
	private GameObject _makeInvalidPanel; // 0x98
	private SandboxV2CookDeckView _deckPrefab; // 0xa0
	private Transform _deckHolder; // 0xa8
	private SimpleLayoutContent _mainMatContent; // 0xb0
	private SimpleLayoutContent _subMatContent; // 0xb8
	private Single _itemCardScale; // 0xc0
	private Text _foodNameText; // 0xc8
	private Text _foodStockText; // 0xd0
	private Text _mainMatProgressText; // 0xd8
	private Text _subMatProgressText; // 0xe0
	private ScrollRect _rightScrollRect; // 0xe8
	private Boolean m_hasInited; // 0xf0
	private SandboxV2CookDeckView m_deckView; // 0xf8
	private Adapter m_mainMatAdapter; // 0x100
	private Adapter m_subMatAdapter; // 0x108
	private String m_cachedFoodId; // 0x110
	private SandboxV2FoodData m_cachedFoodData; // 0x118
	private String m_cachedFoodFallbackName; // 0x120
	private String m_cachedWaterId; // 0x128
	private Action`1 <selectMainMatEvent>k__BackingField; // 0x130
	private Action`1 <selectSubMatEvent>k__BackingField; // 0x138
	private Action`1 <deselectMainMatEvent>k__BackingField; // 0x140
	private Action`1 <deselectSubMatEvent>k__BackingField; // 0x148
	private Action <clearMatEvent>k__BackingField; // 0x150
	private Action <makeEvent>k__BackingField; // 0x158
	private static DelegateBridge __Hotfix0_get_selectMainMatEvent; // 0x0
	private static DelegateBridge __Hotfix0_set_selectMainMatEvent; // 0x8
	private static DelegateBridge __Hotfix0_get_selectSubMatEvent; // 0x10
	private static DelegateBridge __Hotfix0_set_selectSubMatEvent; // 0x18
	private static DelegateBridge __Hotfix0_get_deselectMainMatEvent; // 0x20
	private static DelegateBridge __Hotfix0_set_deselectMainMatEvent; // 0x28
	private static DelegateBridge __Hotfix0_get_deselectSubMatEvent; // 0x30
	private static DelegateBridge __Hotfix0_set_deselectSubMatEvent; // 0x38
	private static DelegateBridge __Hotfix0_get_clearMatEvent; // 0x40
	private static DelegateBridge __Hotfix0_set_clearMatEvent; // 0x48
	private static DelegateBridge __Hotfix0_get_makeEvent; // 0x50
	private static DelegateBridge __Hotfix0_set_makeEvent; // 0x58
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x60
	private static DelegateBridge __Hotfix0_OnClearMatEvent; // 0x68
	private static DelegateBridge __Hotfix0_OnMakeEvent; // 0x70
	private static DelegateBridge __Hotfix0_OnShow; // 0x78
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x80
	private static DelegateBridge __Hotfix0__OnSelectMainMatEvent; // 0x88
	private static DelegateBridge __Hotfix0__OnSelectSubMatEvent; // 0x90
	private static DelegateBridge __Hotfix0__OnDeselectMainMatEvent; // 0x98
	private static DelegateBridge __Hotfix0__OnDeselectSubMatEvent; // 0xa0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa8

	private Action`1 selectMainMatEvent { get; set; }
	private Action`1 selectSubMatEvent { get; set; }
	private Action`1 deselectMainMatEvent { get; set; }
	private Action`1 deselectSubMatEvent { get; set; }
	private Action clearMatEvent { get; set; }
	private Action makeEvent { get; set; }

	// RVA: 0x24c8824 VA: 0x7594ae0824
	private Action`1 get_selectMainMatEvent() { }
	// RVA: 0x24c888c VA: 0x7594ae088c
	public Void set_selectMainMatEvent(Action`1 value) { }
	// RVA: 0x24c8910 VA: 0x7594ae0910
	private Action`1 get_selectSubMatEvent() { }
	// RVA: 0x24c8978 VA: 0x7594ae0978
	public Void set_selectSubMatEvent(Action`1 value) { }
	// RVA: 0x24c89fc VA: 0x7594ae09fc
	private Action`1 get_deselectMainMatEvent() { }
	// RVA: 0x24c8a64 VA: 0x7594ae0a64
	public Void set_deselectMainMatEvent(Action`1 value) { }
	// RVA: 0x24c8ae8 VA: 0x7594ae0ae8
	private Action`1 get_deselectSubMatEvent() { }
	// RVA: 0x24c8b50 VA: 0x7594ae0b50
	public Void set_deselectSubMatEvent(Action`1 value) { }
	// RVA: 0x24c8bd4 VA: 0x7594ae0bd4
	private Action get_clearMatEvent() { }
	// RVA: 0x24c8c3c VA: 0x7594ae0c3c
	public Void set_clearMatEvent(Action value) { }
	// RVA: 0x24c8cc0 VA: 0x7594ae0cc0
	private Action get_makeEvent() { }
	// RVA: 0x24c8d28 VA: 0x7594ae0d28
	public Void set_makeEvent(Action value) { }
	// RVA: 0x24c8dac VA: 0x7594ae0dac
	public override Void OnValueChanged(SandboxV2AdminMainCookPanelModelProperty property) { }
	// RVA: 0x24c9764 VA: 0x7594ae1764
	public Void OnClearMatEvent() { }
	// RVA: 0x24c9800 VA: 0x7594ae1800
	public Void OnMakeEvent() { }
	// RVA: 0x24c989c VA: 0x7594ae189c
	protected override Void OnShow() { }
	// RVA: 0x24c9408 VA: 0x7594ae1408
	private Void _InitIfNot() { }
	// RVA: 0x24c9ab0 VA: 0x7594ae1ab0
	private Void _OnSelectMainMatEvent(Int32 index) { }
	// RVA: 0x24c9b68 VA: 0x7594ae1b68
	private Void _OnSelectSubMatEvent(Int32 index) { }
	// RVA: 0x24c9c20 VA: 0x7594ae1c20
	private Void _OnDeselectMainMatEvent(Int32 index) { }
	// RVA: 0x24c9cd8 VA: 0x7594ae1cd8
	private Void _OnDeselectSubMatEvent(Int32 index) { }
	// RVA: 0x24c9d90 VA: 0x7594ae1d90
	public Void .ctor() { }
}
```