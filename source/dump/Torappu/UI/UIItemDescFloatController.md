# UIItemDescFloatController

**Namespace:** `Torappu.UI`


## Fields

- `UIItemDescFloat _floatPrefab`

- `RectTransform _descBound`

- `RectTransform _floatHolder`

- `Boolean m_isInited`

- `UIItemDescFloat m_floatInst`

- `UIItemDescViewModel m_viewModel`


## Properties

- `UIItemDescFloat floatPrefab`


## Methods

- `Void _OnCloseDescPanel(ClosePanelRequest)`

- `UIItemDescFloat get_floatPrefab()`

- `Void _ShowItemDesc(GameObject, UIItemViewModel, Single, Boolean, Boolean)`

- `Void _TryCloseItemDesc()`

- `Void <>xLuaBaseProxy_OnCreate()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIItemDescFloatController : PageSingleComponent
{
	private UIItemDescFloat _floatPrefab; // 0x20
	private RectTransform _descBound; // 0x28
	private RectTransform _floatHolder; // 0x30
	private Boolean m_isInited; // 0x38
	private UIItemDescFloat m_floatInst; // 0x40
	private UIItemDescViewModel m_viewModel; // 0x48
	private static DelegateBridge __Hotfix0_ShowItemDesc; // 0x0
	private static DelegateBridge __Hotfix1_ShowItemDesc; // 0x8
	private static DelegateBridge __Hotfix0_CloseAll; // 0x10
	private static DelegateBridge __Hotfix0__ShowItemDescImpl; // 0x18
	private static DelegateBridge __Hotfix0_OnCreate; // 0x20
	private static DelegateBridge __Hotfix0__OnCloseDescPanel; // 0x28
	private static DelegateBridge __Hotfix0_get_floatPrefab; // 0x30
	private static DelegateBridge __Hotfix0__ShowItemDesc; // 0x38
	private static DelegateBridge __Hotfix0__TryCloseItemDesc; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	protected UIItemDescFloat floatPrefab { get; }

	// RVA: 0x2191898 VA: 0x75947a9898
	public static Void ShowItemDesc(GameObject itemView, UIItemViewModel itemModel, Boolean enableDropRoute) { }
	// RVA: 0x2189dc4 VA: 0x75947a1dc4
	public static Void ShowItemDesc(GameObject itemView, UIItemViewModel itemModel, Single itemViewScaling, Boolean enableDropRoute, Boolean enableVoucherRoute) { }
	// RVA: 0x2191b34 VA: 0x75947a9b34
	public static Void CloseAll(UIPage page) { }
	// RVA: 0x219192c VA: 0x75947a992c
	private static Void _ShowItemDescImpl(GameObject itemView, UIItemViewModel itemModel, Single itemViewScaling, Boolean enableDropRoute, Boolean enableVoucherRoute) { }
	// RVA: 0x2191e34 VA: 0x75947a9e34
	protected override Void OnCreate() { }
	// RVA: 0x2192084 VA: 0x75947aa084
	private Void _OnCloseDescPanel(ClosePanelRequest unused) { }
	// RVA: 0x2191fa8 VA: 0x75947a9fa8
	protected UIItemDescFloat get_floatPrefab() { }
	// RVA: 0x2191d20 VA: 0x75947a9d20
	private Void _ShowItemDesc(GameObject itemView, UIItemViewModel itemModel, Single itemViewScaling, Boolean enableDropRoute, Boolean enableVoucherRoute) { }
	// RVA: 0x2191c8c VA: 0x75947a9c8c
	private Void _TryCloseItemDesc() { }
	// RVA: 0x2192100 VA: 0x75947aa100
	public Void .ctor() { }
	// RVA: 0x21921c4 VA: 0x75947aa1c4
	private Void <>xLuaBaseProxy_OnCreate() { }
}
```