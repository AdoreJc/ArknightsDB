# CharSelectAttrTabItem

**Namespace:** `Torappu.UI.CharSelect`


## Fields

- `CharAttrTabType _tabType`

- `CharAttrTabTypeMessage onSortTypeChanged`

- `Boolean m_isInited`

- `TwoStateToggle m_twoStateToggle`


## Properties

- `CharAttrTabType attrTabType`


## Methods

- `Void _InitIfNot()`

- `Void _OnToggle(State)`

- `CharAttrTabType get_attrTabType()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharSelect
public class CharSelectAttrTabItem : DataBinder`1
{
	private CharAttrTabType _tabType; // 0x20
	private CharAttrTabTypeMessage onSortTypeChanged; // 0x28
	private Boolean m_isInited; // 0x30
	private TwoStateToggle m_twoStateToggle; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__OnToggle; // 0x10
	private static DelegateBridge __Hotfix0_get_attrTabType; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public CharAttrTabType attrTabType { get; }

	// RVA: 0x2cf42b4 VA: 0x759530c2b4
	private Void _InitIfNot() { }
	// RVA: 0x2cf43c8 VA: 0x759530c3c8
	public override Void OnValueChanged(CharAttrViewProperty property) { }
	// RVA: 0x2cf4490 VA: 0x759530c490
	private Void _OnToggle(State state) { }
	// RVA: 0x2cf453c VA: 0x759530c53c
	public CharAttrTabType get_attrTabType() { }
	// RVA: 0x2cf45a4 VA: 0x759530c5a4
	public Void .ctor() { }
}
```