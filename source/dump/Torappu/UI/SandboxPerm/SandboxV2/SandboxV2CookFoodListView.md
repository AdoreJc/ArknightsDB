# SandboxV2CookFoodListView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SimpleLayoutContent _materialContent`

- `GameObject _filterFalsePanel`

- `GameObject _filterTruePanel`

- `GameObject _itemsPanel`

- `GameObject _emptyPanel`

- `SandboxV2CookFoodListLoopAdapter _loopAdapter`

- `LoopVerticalScrollRect _itemScrollRect`

- `Boolean m_hasInited`

- `Adapter m_adapter`

- `String m_cachedTopicId`

- `Boolean m_cachedCanCookFilter`


## Methods

- `Void set_selectItemEvent(Action`1)`

- `Void OnSetCanCookFilterEvent()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2CookFoodListView : SandboxV2AdminMainContentViewBase`1
{
	private SimpleLayoutContent _materialContent; // 0x38
	private GameObject _filterFalsePanel; // 0x40
	private GameObject _filterTruePanel; // 0x48
	private GameObject _itemsPanel; // 0x50
	private GameObject _emptyPanel; // 0x58
	private SandboxV2CookFoodListLoopAdapter _loopAdapter; // 0x60
	private LoopVerticalScrollRect _itemScrollRect; // 0x68
	private Boolean m_hasInited; // 0x70
	private Adapter m_adapter; // 0x78
	private String m_cachedTopicId; // 0x80
	private List`1 m_cachedMaterials; // 0x88
	private List`1 m_cachedAllItems; // 0x90
	private List`1 m_cachedCanCookItems; // 0x98
	private Boolean m_cachedCanCookFilter; // 0xa0
	private Action`1 <selectItemEvent>k__BackingField; // 0xa8
	private static DelegateBridge __Hotfix0_get_selectItemEvent; // 0x0
	private static DelegateBridge __Hotfix0_set_selectItemEvent; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0_OnShow; // 0x18
	private static DelegateBridge __Hotfix0_OnSetCanCookFilterEvent; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private Action`1 selectItemEvent { get; set; }

	// RVA: 0x24c7e5c VA: 0x7594adfe5c
	private Action`1 get_selectItemEvent() { }
	// RVA: 0x24c7ec4 VA: 0x7594adfec4
	public Void set_selectItemEvent(Action`1 value) { }
	// RVA: 0x24c7f48 VA: 0x7594adff48
	public override Void OnValueChanged(SandboxV2AdminMainCookPanelModelProperty property) { }
	// RVA: 0x24c82c8 VA: 0x7594ae02c8
	protected override Void OnShow() { }
	// RVA: 0x24c8344 VA: 0x7594ae0344
	public Void OnSetCanCookFilterEvent() { }
	// RVA: 0x24c8170 VA: 0x7594ae0170
	private Void _InitIfNot() { }
	// RVA: 0x24c8500 VA: 0x7594ae0500
	public Void .ctor() { }
}
```