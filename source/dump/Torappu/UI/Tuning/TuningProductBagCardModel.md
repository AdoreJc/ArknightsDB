# TuningProductBagCardModel

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `TuningCommonCardModel m_cardModel`

- `Int32 m_productNum`

- `String m_productId`

- `String m_productTypeId`

- `Boolean m_isCardInteractable`

- `String m_displayName`

- `Int32 m_sortId`

- `Boolean m_isSelect`

- `Boolean m_isAnswer`

- `Boolean m_isHidden`


## Properties

- `TuningCommonCardModel cardModel`

- `String productId`

- `Int32 productNum`

- `String productTypeId`

- `String displayName`

- `Boolean isSelect`

- `Boolean isAnswer`

- `Boolean isCardInteractable`

- `Int32 sortId`


## Methods

- `TuningCommonCardModel get_cardModel()`

- `String get_productId()`

- `Int32 get_productNum()`

- `String get_productTypeId()`

- `String get_displayName()`

- `Boolean get_isSelect()`

- `Boolean get_isAnswer()`

- `Boolean get_isCardInteractable()`

- `Int32 get_sortId()`

- `Void InitData(String, Act29SideData, Act29SideProductData, Int32, Boolean, Boolean)`

- `Void _LoadNormalCardData(String, Act29SideData)`

- `Void _LoadHiddenCardData(Act29SideData)`

- `Void SetSelect(Boolean)`

- `Void SetAnswer(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningProductBagCardModel : IHotfixable
{
	private TuningCommonCardModel m_cardModel; // 0x10
	private Int32 m_productNum; // 0x18
	private String m_productId; // 0x20
	private String m_productTypeId; // 0x28
	private Boolean m_isCardInteractable; // 0x30
	private String m_displayName; // 0x38
	private Int32 m_sortId; // 0x40
	private Boolean m_isSelect; // 0x44
	private Boolean m_isAnswer; // 0x45
	private Boolean m_isHidden; // 0x46
	private static DelegateBridge __Hotfix0_get_cardModel; // 0x0
	private static DelegateBridge __Hotfix0_get_productId; // 0x8
	private static DelegateBridge __Hotfix0_get_productNum; // 0x10
	private static DelegateBridge __Hotfix0_get_productTypeId; // 0x18
	private static DelegateBridge __Hotfix0_get_displayName; // 0x20
	private static DelegateBridge __Hotfix0_get_isSelect; // 0x28
	private static DelegateBridge __Hotfix0_get_isAnswer; // 0x30
	private static DelegateBridge __Hotfix0_get_isCardInteractable; // 0x38
	private static DelegateBridge __Hotfix0_get_sortId; // 0x40
	private static DelegateBridge __Hotfix0_InitData; // 0x48
	private static DelegateBridge __Hotfix0__LoadNormalCardData; // 0x50
	private static DelegateBridge __Hotfix0__LoadHiddenCardData; // 0x58
	private static DelegateBridge __Hotfix0_SetSelect; // 0x60
	private static DelegateBridge __Hotfix0_SetAnswer; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public TuningCommonCardModel cardModel { get; }
	public String productId { get; }
	public Int32 productNum { get; }
	public String productTypeId { get; }
	public String displayName { get; }
	public Boolean isSelect { get; }
	public Boolean isAnswer { get; }
	public Boolean isCardInteractable { get; }
	public Int32 sortId { get; }

	// RVA: 0x233f3d8 VA: 0x75949573d8
	public TuningCommonCardModel get_cardModel() { }
	// RVA: 0x233f370 VA: 0x7594957370
	public String get_productId() { }
	// RVA: 0x233f4a8 VA: 0x75949574a8
	public Int32 get_productNum() { }
	// RVA: 0x2344118 VA: 0x759495c118
	public String get_productTypeId() { }
	// RVA: 0x233f440 VA: 0x7594957440
	public String get_displayName() { }
	// RVA: 0x233f578 VA: 0x7594957578
	public Boolean get_isSelect() { }
	// RVA: 0x233f510 VA: 0x7594957510
	public Boolean get_isAnswer() { }
	// RVA: 0x233f5e0 VA: 0x75949575e0
	public Boolean get_isCardInteractable() { }
	// RVA: 0x2344e04 VA: 0x759495ce04
	public Int32 get_sortId() { }
	// RVA: 0x234444c VA: 0x759495c44c
	public Void InitData(String actId, Act29SideData actData, Act29SideProductData productData, Int32 iProductNum, Boolean iIsCardInteractable, Boolean isHidden) { }
	// RVA: 0x2344f10 VA: 0x759495cf10
	private Void _LoadNormalCardData(String orcheId, Act29SideData actData) { }
	// RVA: 0x2344e6c VA: 0x759495ce6c
	private Void _LoadHiddenCardData(Act29SideData actData) { }
	// RVA: 0x2343eec VA: 0x759495beec
	public Void SetSelect(Boolean iIsSelect) { }
	// RVA: 0x2344098 VA: 0x759495c098
	public Void SetAnswer(Boolean iIsAnswer) { }
	// RVA: 0x234439c VA: 0x759495c39c
	public Void .ctor() { }
}
```