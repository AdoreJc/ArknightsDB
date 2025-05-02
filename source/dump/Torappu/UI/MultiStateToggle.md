# MultiStateToggle

**Namespace:** `Torappu.UI`


## Fields

- `Boolean _interactable`

- `GameObject _nonInteractiveNode`

- `Int32 m_selectIdx`

- `Boolean m_init`


## Properties

- `Boolean interactable`

- `Boolean selected`

- `Int32 selectIdx`

- `String selectedId`


## Methods

- `Void InitIfNot()`

- `Boolean get_interactable()`

- `Void set_interactable(Boolean)`

- `Boolean get_selected()`

- `Void set_selected(Boolean)`

- `Int32 get_selectIdx()`

- `Void set_selectIdx(Int32)`

- `Boolean SetSelectedID(String)`

- `String get_selectedId()`

- `Void OnPointerClick(PointerEventData)`

- `Void _SetSelect(Int32)`

- `Void <>xLuaBaseProxy_Awake()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class MultiStateToggle : UIBehaviour, IPointerClickHandler, IEventSystemHandler, IHotfixable
{
	private const Int32 UNSELECTED_IDX; // 0x0
	private MultiStateItem[] _states; // 0x18
	private Boolean _interactable; // 0x20
	private GameObject _nonInteractiveNode; // 0x28
	private Int32 m_selectIdx; // 0x30
	public Action`1 eSelecteChanged; // 0x38
	private Boolean m_init; // 0x40
	private static DelegateBridge __Hotfix0_Awake; // 0x0
	private static DelegateBridge __Hotfix0_InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_get_interactable; // 0x10
	private static DelegateBridge __Hotfix0_set_interactable; // 0x18
	private static DelegateBridge __Hotfix0_get_selected; // 0x20
	private static DelegateBridge __Hotfix0_set_selected; // 0x28
	private static DelegateBridge __Hotfix0_get_selectIdx; // 0x30
	private static DelegateBridge __Hotfix0_set_selectIdx; // 0x38
	private static DelegateBridge __Hotfix0_SetSelectedID; // 0x40
	private static DelegateBridge __Hotfix0_get_selectedId; // 0x48
	private static DelegateBridge __Hotfix0_OnPointerClick; // 0x50
	private static DelegateBridge __Hotfix0__SetSelect; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public Boolean interactable { get; set; }
	public Boolean selected { get; set; }
	public Int32 selectIdx { get; set; }
	public String selectedId { get; }

	// RVA: 0x22354b4 VA: 0x759484d4b4
	protected override Void Awake() { }
	// RVA: 0x223551c VA: 0x759484d51c
	public Void InitIfNot() { }
	// RVA: 0x2235660 VA: 0x759484d660
	public Boolean get_interactable() { }
	// RVA: 0x22356c8 VA: 0x759484d6c8
	public Void set_interactable(Boolean value) { }
	// RVA: 0x2235778 VA: 0x759484d778
	public Boolean get_selected() { }
	// RVA: 0x22357e8 VA: 0x759484d7e8
	public Void set_selected(Boolean value) { }
	// RVA: 0x2235a24 VA: 0x759484da24
	public Int32 get_selectIdx() { }
	// RVA: 0x2235a8c VA: 0x759484da8c
	public Void set_selectIdx(Int32 value) { }
	// RVA: 0x2235b0c VA: 0x759484db0c
	public Boolean SetSelectedID(String id) { }
	// RVA: 0x2235bf0 VA: 0x759484dbf0
	public String get_selectedId() { }
	// RVA: 0x2235c88 VA: 0x759484dc88
	public Void OnPointerClick(PointerEventData eventData) { }
	// RVA: 0x223587c VA: 0x759484d87c
	private Void _SetSelect(Int32 idx) { }
	// RVA: 0x2235d44 VA: 0x759484dd44
	public Void .ctor() { }
	// RVA: 0x2235dbc VA: 0x759484ddbc
	private Void <>xLuaBaseProxy_Awake() { }
}
```