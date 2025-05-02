# SandboxV2AdminMainTypeSelector

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SimpleLayoutContent _layout`

- `GameObject _panelRacingBtn`

- `Text _textRacerBagName`

- `LayoutAdapter m_adapter`

- `Color m_selBgClr`

- `Color m_selTitleClr`

- `Int32 m_selected`

- `UIStateFinder m_stateFinder`


## Properties

- `Int32 selected`


## Methods

- `Void add_eSelectChanged(Action`1)`

- `Void remove_eSelectChanged(Action`1)`

- `Void set_checkIfShowRacingBtn(Func`1)`

- `Void SetRacerBagNameText(String)`

- `Void Render(IList`1, Color, Color)`

- `Void EventOnRacingBtnClicked()`

- `Int32 get_selected()`

- `Void set_selected(Int32)`

- `Void _SetSelect(Int32)`

- `Void _InitIfNot()`

- `GameObject TutorialOnly_GetItemButtonGO(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminMainTypeSelector : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _layout; // 0x18
	private GameObject _panelRacingBtn; // 0x20
	private Text _textRacerBagName; // 0x28
	private LayoutAdapter m_adapter; // 0x30
	private IList`1 m_typeList; // 0x38
	private Color m_selBgClr; // 0x40
	private Color m_selTitleClr; // 0x50
	private Int32 m_selected; // 0x60
	private UIStateFinder m_stateFinder; // 0x68
	private Action`1 eSelectChanged; // 0x78
	private Func`1 <checkIfShowRacingBtn>k__BackingField; // 0x80
	private static DelegateBridge __Hotfix0_add_eSelectChanged; // 0x0
	private static DelegateBridge __Hotfix0_remove_eSelectChanged; // 0x8
	private static DelegateBridge __Hotfix0_get_checkIfShowRacingBtn; // 0x10
	private static DelegateBridge __Hotfix0_set_checkIfShowRacingBtn; // 0x18
	private static DelegateBridge __Hotfix0_SetRacerBagNameText; // 0x20
	private static DelegateBridge __Hotfix0_Render; // 0x28
	private static DelegateBridge __Hotfix0_EventOnRacingBtnClicked; // 0x30
	private static DelegateBridge __Hotfix0_get_selected; // 0x38
	private static DelegateBridge __Hotfix0_set_selected; // 0x40
	private static DelegateBridge __Hotfix0__SetSelect; // 0x48
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x50
	private static DelegateBridge __Hotfix0_TutorialOnly_GetItemButtonGO; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	private Func`1 checkIfShowRacingBtn { get; set; }
	public Int32 selected { get; set; }

	// RVA: 0x24b7228 VA: 0x7594acf228
	public Void add_eSelectChanged(Action`1 value) { }
	// RVA: 0x24b731c VA: 0x7594acf31c
	public Void remove_eSelectChanged(Action`1 value) { }
	// RVA: 0x24b7410 VA: 0x7594acf410
	private Func`1 get_checkIfShowRacingBtn() { }
	// RVA: 0x24b7478 VA: 0x7594acf478
	public Void set_checkIfShowRacingBtn(Func`1 value) { }
	// RVA: 0x24b74fc VA: 0x7594acf4fc
	public Void SetRacerBagNameText(String racerBagName) { }
	// RVA: 0x24b7590 VA: 0x7594acf590
	public Void Render(IList`1 typeList, Color selBgClr, Color selTitleClr) { }
	// RVA: 0x24b77c0 VA: 0x7594acf7c0
	public Void EventOnRacingBtnClicked() { }
	// RVA: 0x24b7864 VA: 0x7594acf864
	public Int32 get_selected() { }
	// RVA: 0x24b78cc VA: 0x7594acf8cc
	public Void set_selected(Int32 value) { }
	// RVA: 0x24b794c VA: 0x7594acf94c
	private Void _SetSelect(Int32 selectedIdx) { }
	// RVA: 0x24b76f4 VA: 0x7594acf6f4
	private Void _InitIfNot() { }
	// RVA: 0x24b7ad4 VA: 0x7594acfad4
	public GameObject TutorialOnly_GetItemButtonGO(Int32 index) { }
	// RVA: 0x24b7c18 VA: 0x7594acfc18
	public Void .ctor() { }
}
```