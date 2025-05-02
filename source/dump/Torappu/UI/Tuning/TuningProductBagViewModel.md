# TuningProductBagViewModel

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `String m_selectProductType`

- `TuningProductBagProductGroupModel m_selectGroupModel`

- `Boolean m_isSelectGroupEmpty`

- `String m_selectProductId`

- `Boolean m_isChatState`

- `Boolean m_isPanelShow`

- `Boolean m_hasAnswer`

- `Boolean m_hasSetAnswer`

- `String m_themeColor`

- `String m_actId`

- `Act29SideData m_actData`


## Properties

- `String selectProductType`

- `TuningProductBagProductGroupModel selectGroupModel`

- `Boolean isSelectGroupEmpty`

- `Boolean isChatState`

- `Boolean isPanelShow`

- `Boolean hasAnswer`

- `Boolean hasSetAnswer`

- `String themeColor`


## Methods

- `String get_selectProductType()`

- `TuningProductBagProductGroupModel get_selectGroupModel()`

- `Boolean get_isSelectGroupEmpty()`

- `Boolean get_isChatState()`

- `Boolean get_isPanelShow()`

- `Boolean get_hasAnswer()`

- `Boolean get_hasSetAnswer()`

- `String get_themeColor()`

- `Void InitData(String, Boolean)`

- `Void UpdateData()`

- `Boolean TrySelectProductGroup(String)`

- `Boolean TrySelectCard(String)`

- `Void SetAnswer(AnswerParam)`

- `Boolean TrySetShow(Boolean)`

- `TuningProductBagCardModel GetSelectCardModel()`

- `Void _InitProductGroupDict()`

- `Void _UpdateProductGroupDict(PlayerAct29SideActivity)`

- `Void _CheckProductGroupDictLock(PlayerAct29SideActivity)`

- `Void _SetDefaultProductType()`

- `TuningProductBagCardModel _GetCardModelByProductId(String)`

- `Void _SetProductIsSelect(String, Boolean)`

- `Void _CheckSelectProductTypeEmpty()`

- `Void _ClearProductGroupData()`

- `Void _SetAnswerByProductId(AnswerParam)`

- `Void _SetAnswerByProductTypeAndOrche(AnswerParam)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningProductBagViewModel : IHotfixable
{
	private ListDict`2 m_productGroupListDict; // 0x10
	private String m_selectProductType; // 0x18
	private TuningProductBagProductGroupModel m_selectGroupModel; // 0x20
	private Boolean m_isSelectGroupEmpty; // 0x28
	private String m_selectProductId; // 0x30
	private Boolean m_isChatState; // 0x38
	private Boolean m_isPanelShow; // 0x39
	private Boolean m_hasAnswer; // 0x3a
	private Boolean m_hasSetAnswer; // 0x3b
	private String m_themeColor; // 0x40
	private String m_actId; // 0x48
	private Act29SideData m_actData; // 0x50
	private static DelegateBridge __Hotfix0_get_productGroupListDict; // 0x0
	private static DelegateBridge __Hotfix0_get_selectProductType; // 0x8
	private static DelegateBridge __Hotfix0_get_selectGroupModel; // 0x10
	private static DelegateBridge __Hotfix0_get_isSelectGroupEmpty; // 0x18
	private static DelegateBridge __Hotfix0_get_isChatState; // 0x20
	private static DelegateBridge __Hotfix0_get_isPanelShow; // 0x28
	private static DelegateBridge __Hotfix0_get_hasAnswer; // 0x30
	private static DelegateBridge __Hotfix0_get_hasSetAnswer; // 0x38
	private static DelegateBridge __Hotfix0_get_themeColor; // 0x40
	private static DelegateBridge __Hotfix0_InitData; // 0x48
	private static DelegateBridge __Hotfix0_UpdateData; // 0x50
	private static DelegateBridge __Hotfix0_TrySelectProductGroup; // 0x58
	private static DelegateBridge __Hotfix0_TrySelectCard; // 0x60
	private static DelegateBridge __Hotfix0_SetAnswer; // 0x68
	private static DelegateBridge __Hotfix0_TrySetShow; // 0x70
	private static DelegateBridge __Hotfix0_GetSelectCardModel; // 0x78
	private static DelegateBridge __Hotfix0__InitProductGroupDict; // 0x80
	private static DelegateBridge __Hotfix0__UpdateProductGroupDict; // 0x88
	private static DelegateBridge __Hotfix0__CheckProductGroupDictLock; // 0x90
	private static DelegateBridge __Hotfix0__SetDefaultProductType; // 0x98
	private static DelegateBridge __Hotfix0__GetCardModelByProductId; // 0xa0
	private static DelegateBridge __Hotfix0__SetProductIsSelect; // 0xa8
	private static DelegateBridge __Hotfix0__CheckSelectProductTypeEmpty; // 0xb0
	private static DelegateBridge __Hotfix0__ClearProductGroupData; // 0xb8
	private static DelegateBridge __Hotfix0__SetAnswerByProductId; // 0xc0
	private static DelegateBridge __Hotfix0__SetAnswerByProductTypeAndOrche; // 0xc8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xd0

	public ListDict`2 productGroupListDict { get; }
	public String selectProductType { get; }
	public TuningProductBagProductGroupModel selectGroupModel { get; }
	public Boolean isSelectGroupEmpty { get; }
	public Boolean isChatState { get; }
	public Boolean isPanelShow { get; }
	public Boolean hasAnswer { get; }
	public Boolean hasSetAnswer { get; }
	public String themeColor { get; }

	// RVA: 0x234104c VA: 0x759495904c
	public ListDict`2 get_productGroupListDict() { }
	// RVA: 0x2342050 VA: 0x759495a050
	public String get_selectProductType() { }
	// RVA: 0x2340798 VA: 0x7594958798
	public TuningProductBagProductGroupModel get_selectGroupModel() { }
	// RVA: 0x2340730 VA: 0x7594958730
	public Boolean get_isSelectGroupEmpty() { }
	// RVA: 0x23405f8 VA: 0x75949585f8
	public Boolean get_isChatState() { }
	// RVA: 0x2340590 VA: 0x7594958590
	public Boolean get_isPanelShow() { }
	// RVA: 0x23406c8 VA: 0x75949586c8
	public Boolean get_hasAnswer() { }
	// RVA: 0x2340660 VA: 0x7594958660
	public Boolean get_hasSetAnswer() { }
	// RVA: 0x23420b8 VA: 0x759495a0b8
	public String get_themeColor() { }
	// RVA: 0x2342120 VA: 0x759495a120
	public Void InitData(String actId, Boolean iIsChatState) { }
	// RVA: 0x2342544 VA: 0x759495a544
	public Void UpdateData() { }
	// RVA: 0x2341954 VA: 0x7594959954
	public Boolean TrySelectProductGroup(String productTypeId) { }
	// RVA: 0x234331c VA: 0x759495b31c
	public Boolean TrySelectCard(String productId) { }
	// RVA: 0x2343490 VA: 0x759495b490
	public Void SetAnswer(AnswerParam answerParam) { }
	// RVA: 0x2343820 VA: 0x759495b820
	public Boolean TrySetShow(Boolean isShow) { }
	// RVA: 0x23438bc VA: 0x759495b8bc
	public TuningProductBagCardModel GetSelectCardModel() { }
	// RVA: 0x234224c VA: 0x759495a24c
	private Void _InitProductGroupDict() { }
	// RVA: 0x23428ac VA: 0x759495a8ac
	private Void _UpdateProductGroupDict(PlayerAct29SideActivity playerActData) { }
	// RVA: 0x2342d44 VA: 0x759495ad44
	private Void _CheckProductGroupDictLock(PlayerAct29SideActivity playerActData) { }
	// RVA: 0x2343028 VA: 0x759495b028
	private Void _SetDefaultProductType() { }
	// RVA: 0x2343928 VA: 0x759495b928
	private TuningProductBagCardModel _GetCardModelByProductId(String productId) { }
	// RVA: 0x23433ec VA: 0x759495b3ec
	private Void _SetProductIsSelect(String productId, Boolean isSelect) { }
	// RVA: 0x23431c0 VA: 0x759495b1c0
	private Void _CheckSelectProductTypeEmpty() { }
	// RVA: 0x23426f4 VA: 0x759495a6f4
	private Void _ClearProductGroupData() { }
	// RVA: 0x2343558 VA: 0x759495b558
	private Void _SetAnswerByProductId(AnswerParam answerParam) { }
	// RVA: 0x2343650 VA: 0x759495b650
	private Void _SetAnswerByProductTypeAndOrche(AnswerParam answerParam) { }
	// RVA: 0x2344180 VA: 0x759495c180
	public Void .ctor() { }
}
```