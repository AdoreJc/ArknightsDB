# SandboxV2AdminMainScienceTypeSelector

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SimpleLayoutContent _layout`

- `LayoutAdapter m_adapter`

- `Int32 m_selected`


## Properties

- `Int32 selected`


## Methods

- `Void add_eSelectChanged(Action`1)`

- `Void remove_eSelectChanged(Action`1)`

- `Void Init(IList`1)`

- `Int32 get_selected()`

- `Void set_selected(Int32)`

- `Void _SetSelect(Int32)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminMainScienceTypeSelector : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _layout; // 0x18
	private LayoutAdapter m_adapter; // 0x20
	private IList`1 m_typeList; // 0x28
	private Int32 m_selected; // 0x30
	private Action`1 eSelectChanged; // 0x38
	private static DelegateBridge __Hotfix0_add_eSelectChanged; // 0x0
	private static DelegateBridge __Hotfix0_remove_eSelectChanged; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge __Hotfix0_get_selected; // 0x18
	private static DelegateBridge __Hotfix0_set_selected; // 0x20
	private static DelegateBridge __Hotfix0__SetSelect; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Int32 selected { get; set; }

	// RVA: 0x24e67c0 VA: 0x7594afe7c0
	public Void add_eSelectChanged(Action`1 value) { }
	// RVA: 0x24e68b4 VA: 0x7594afe8b4
	public Void remove_eSelectChanged(Action`1 value) { }
	// RVA: 0x24e69a8 VA: 0x7594afe9a8
	public Void Init(IList`1 typeList) { }
	// RVA: 0x24e6b18 VA: 0x7594afeb18
	public Int32 get_selected() { }
	// RVA: 0x24e6b80 VA: 0x7594afeb80
	public Void set_selected(Int32 value) { }
	// RVA: 0x24e6c00 VA: 0x7594afec00
	private Void _SetSelect(Int32 selectedIdx) { }
	// RVA: 0x24e6a4c VA: 0x7594afea4c
	private Void _InitIfNot() { }
	// RVA: 0x24e6d5c VA: 0x7594afed5c
	public Void .ctor() { }
}
```