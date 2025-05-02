# TuningProductBagFormModel

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `String m_formDesc`

- `Int32 m_sortId`

- `Act29SideData m_actData`


## Properties

- `String formDesc`

- `Int32 sortId`


## Methods

- `String get_formDesc()`

- `Int32 get_sortId()`

- `Void InitData(Act29SideData, String)`

- `Void AddProduct(String, Act29SideProductData, Int32, Boolean)`

- `Void SortListDict()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningProductBagFormModel : IHotfixable
{
	private String m_formDesc; // 0x10
	private List`1 m_fragmentIconList; // 0x18
	private ListDict`2 m_cardListDict; // 0x20
	private Int32 m_sortId; // 0x28
	private Act29SideData m_actData; // 0x30
	private static DelegateBridge __Hotfix0_get_formDesc; // 0x0
	private static DelegateBridge __Hotfix0_get_fragmentIconList; // 0x8
	private static DelegateBridge __Hotfix0_get_cardListDict; // 0x10
	private static DelegateBridge __Hotfix0_get_sortId; // 0x18
	private static DelegateBridge __Hotfix0_InitData; // 0x20
	private static DelegateBridge __Hotfix0_AddProduct; // 0x28
	private static DelegateBridge __Hotfix0_SortListDict; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public String formDesc { get; }
	public List`1 fragmentIconList { get; }
	public ListDict`2 cardListDict { get; }
	public Int32 sortId { get; }

	// RVA: 0x233ed30 VA: 0x7594956d30
	public String get_formDesc() { }
	// RVA: 0x2344cac VA: 0x759495ccac
	public List`1 get_fragmentIconList() { }
	// RVA: 0x233ef7c VA: 0x7594956f7c
	public ListDict`2 get_cardListDict() { }
	// RVA: 0x2344c44 VA: 0x759495cc44
	public Int32 get_sortId() { }
	// RVA: 0x234468c VA: 0x759495c68c
	public Void InitData(Act29SideData actData, String formId) { }
	// RVA: 0x23448a8 VA: 0x759495c8a8
	public Void AddProduct(String actId, Act29SideProductData productData, Int32 productNum, Boolean isCardInteractable) { }
	// RVA: 0x2344a10 VA: 0x759495ca10
	public Void SortListDict() { }
	// RVA: 0x2344578 VA: 0x759495c578
	public Void .ctor() { }
}
```