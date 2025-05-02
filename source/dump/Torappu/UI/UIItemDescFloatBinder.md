# UIItemDescFloatBinder

**Namespace:** `Torappu.UI`


## Fields

- `PrefabInstHolder _descFloatHolder`

- `RectTransform _descTextBound`

- `UnityEvent _eventCloseItemDesc`

- `UIItemDescViewModel m_viewModelCache`

- `UIItemDescFloat m_descFloat`

- `Boolean m_isInited`


## Properties

- `UIItemDescFloat itemDescFloat`


## Methods

- `Void _InitIfNot()`

- `UIItemDescFloat get_itemDescFloat()`

- `Void Clean()`

- `Void <_InitIfNot>b__6_0(GameObject)`

- `Void <_InitIfNot>b__6_1(ClosePanelRequest)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIItemDescFloatBinder : DataBinder`1
{
	private PrefabInstHolder _descFloatHolder; // 0x20
	private RectTransform _descTextBound; // 0x28
	private UnityEvent _eventCloseItemDesc; // 0x30
	private UIItemDescViewModel m_viewModelCache; // 0x38
	private UIItemDescFloat m_descFloat; // 0x40
	private Boolean m_isInited; // 0x48
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_get_itemDescFloat; // 0x8
	private static DelegateBridge __Hotfix0_Clean; // 0x10
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public UIItemDescFloat itemDescFloat { get; }

	// RVA: 0x2190d20 VA: 0x75947a8d20
	private Void _InitIfNot() { }
	// RVA: 0x2190e00 VA: 0x75947a8e00
	public UIItemDescFloat get_itemDescFloat() { }
	// RVA: 0x2190e68 VA: 0x75947a8e68
	public Void Clean() { }
	// RVA: 0x2190ee0 VA: 0x75947a8ee0
	public override Void OnValueChanged(UIItemDescViewProperty property) { }
	// RVA: 0x2190ff4 VA: 0x75947a8ff4
	public Void .ctor() { }
	// RVA: 0x2191084 VA: 0x75947a9084
	private Void <_InitIfNot>b__6_0(GameObject inst) { }
	// RVA: 0x21911d4 VA: 0x75947a91d4
	private Void <_InitIfNot>b__6_1(ClosePanelRequest _) { }
}
```