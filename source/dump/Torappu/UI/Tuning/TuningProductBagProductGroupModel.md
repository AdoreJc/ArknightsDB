# TuningProductBagProductGroupModel

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `String m_productTypeSmallName`

- `String m_productTypeId`

- `Boolean m_isSelect`

- `Boolean m_isLock`

- `Boolean m_isAnswer`

- `Int32 m_sortId`

- `Boolean m_isHidden`

- `String m_themeColor`

- `TuningProductBagCardModel m_hiddenCardModel`

- `Act29SideData m_actData`


## Properties

- `String productTypeSmallName`

- `String productTypeId`

- `Boolean isSelect`

- `Boolean isLock`

- `Boolean isAnswer`

- `Boolean isHidden`

- `TuningProductBagCardModel hiddenCardModel`

- `String themeColor`

- `Int32 sortId`


## Methods

- `String get_productTypeSmallName()`

- `String get_productTypeId()`

- `Boolean get_isSelect()`

- `Boolean get_isLock()`

- `Boolean get_isAnswer()`

- `Boolean get_isHidden()`

- `TuningProductBagCardModel get_hiddenCardModel()`

- `String get_themeColor()`

- `Int32 get_sortId()`

- `Void InitData(Act29SideData, Act29SideProductGroupData)`

- `Void AddProduct(String, Act29SideProductData, Int32, Boolean)`

- `Void SortListDict()`

- `Void ClearProduct()`

- `Void SetLock(Boolean)`

- `Void SetSelect(Boolean)`

- `Void SetAnswer(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningProductBagProductGroupModel : IHotfixable
{
	private String m_productTypeSmallName; // 0x10
	private String m_productTypeId; // 0x18
	private Boolean m_isSelect; // 0x20
	private Boolean m_isLock; // 0x21
	private Boolean m_isAnswer; // 0x22
	private Int32 m_sortId; // 0x24
	private Boolean m_isHidden; // 0x28
	private String m_themeColor; // 0x30
	private ListDict`2 m_formListDict; // 0x38
	private TuningProductBagCardModel m_hiddenCardModel; // 0x40
	private Act29SideData m_actData; // 0x48
	private static DelegateBridge __Hotfix0_get_productTypeSmallName; // 0x0
	private static DelegateBridge __Hotfix0_get_productTypeId; // 0x8
	private static DelegateBridge __Hotfix0_get_isSelect; // 0x10
	private static DelegateBridge __Hotfix0_get_isLock; // 0x18
	private static DelegateBridge __Hotfix0_get_isAnswer; // 0x20
	private static DelegateBridge __Hotfix0_get_isHidden; // 0x28
	private static DelegateBridge __Hotfix0_get_formListDict; // 0x30
	private static DelegateBridge __Hotfix0_get_hiddenCardModel; // 0x38
	private static DelegateBridge __Hotfix0_get_themeColor; // 0x40
	private static DelegateBridge __Hotfix0_get_sortId; // 0x48
	private static DelegateBridge __Hotfix0_InitData; // 0x50
	private static DelegateBridge __Hotfix0_AddProduct; // 0x58
	private static DelegateBridge __Hotfix0_SortListDict; // 0x60
	private static DelegateBridge __Hotfix0_ClearProduct; // 0x68
	private static DelegateBridge __Hotfix0_SetLock; // 0x70
	private static DelegateBridge __Hotfix0_SetSelect; // 0x78
	private static DelegateBridge __Hotfix0_SetAnswer; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88

	public String productTypeSmallName { get; }
	public String productTypeId { get; }
	public Boolean isSelect { get; }
	public Boolean isLock { get; }
	public Boolean isAnswer { get; }
	public Boolean isHidden { get; }
	public ListDict`2 formListDict { get; }
	public TuningProductBagCardModel hiddenCardModel { get; }
	public String themeColor { get; }
	public Int32 sortId { get; }

	// RVA: 0x233fc18 VA: 0x7594957c18
	public String get_productTypeSmallName() { }
	// RVA: 0x233fa78 VA: 0x7594957a78
	public String get_productTypeId() { }
	// RVA: 0x233fbb0 VA: 0x7594957bb0
	public Boolean get_isSelect() { }
	// RVA: 0x233fb48 VA: 0x7594957b48
	public Boolean get_isLock() { }
	// RVA: 0x233fc80 VA: 0x7594957c80
	public Boolean get_isAnswer() { }
	// RVA: 0x2340800 VA: 0x7594958800
	public Boolean get_isHidden() { }
	// RVA: 0x23408d0 VA: 0x75949588d0
	public ListDict`2 get_formListDict() { }
	// RVA: 0x2340868 VA: 0x7594958868
	public TuningProductBagCardModel get_hiddenCardModel() { }
	// RVA: 0x233fae0 VA: 0x7594957ae0
	public String get_themeColor() { }
	// RVA: 0x2344334 VA: 0x759495c334
	public Int32 get_sortId() { }
	// RVA: 0x2343b78 VA: 0x759495bb78
	public Void InitData(Act29SideData actData, Act29SideProductGroupData groupData) { }
	// RVA: 0x2343cf0 VA: 0x759495bcf0
	public Void AddProduct(String actId, Act29SideProductData productData, Int32 productNum, Boolean isCardInteractable) { }
	// RVA: 0x2342b80 VA: 0x759495ab80
	public Void SortListDict() { }
	// RVA: 0x2343fec VA: 0x759495bfec
	public Void ClearProduct() { }
	// RVA: 0x2343c70 VA: 0x759495bc70
	public Void SetLock(Boolean iIsLock) { }
	// RVA: 0x234329c VA: 0x759495b29c
	public Void SetSelect(Boolean iIsSelect) { }
	// RVA: 0x2343f6c VA: 0x759495bf6c
	public Void SetAnswer(Boolean iIsAnswer) { }
	// RVA: 0x2343ab4 VA: 0x759495bab4
	public Void .ctor() { }
}
```