# TuningProductViewModel

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `String m_selectOrcheId`

- `String m_selectOrcheName`

- `String m_orcheIconId`

- `Act29SideOrcheType m_selectOrcheType`

- `Act29SideProductType m_selectProductType`

- `String m_selectProductTypeId`

- `String m_selectProductTypeName`

- `String m_selectProductTypeDescColor`

- `String m_productEyeIconId`

- `String m_selectFormDesc`

- `String m_selectFormId`

- `Boolean m_selectFormHasBeenMade`

- `Act29SideData m_actData`

- `ProductStatus m_productStatus`

- `Boolean m_haveNewForm`

- `Boolean m_haveFormUnlock`

- `Int32 m_enterSequenceNum`

- `String m_formSegmentId`

- `Int32 m_formSegmentNum`

- `Single m_formSegmentRotateSecond`

- `String m_curMainMusicId`

- `String m_curOrcheMusicId`

- `String m_actId`


## Properties

- `String selectOrcheId`

- `String selectOrcheName`

- `String selectProductTypeId`

- `String selectProductTypeName`

- `String selectProductTypeDescColor`

- `Act29SideProductType selectProductType`

- `String selectFormDesc`

- `Boolean selectFormHasBeenMade`

- `ProductStatus productStatus`

- `String formSegmentId`

- `Int32 formSegmentNum`

- `Single formSegmentRotateSecond`

- `Boolean haveNewForm`

- `Boolean haveFormUnlock`

- `String curMainMusicId`

- `String curOrcheMusicId`

- `String orcheIconId`

- `Act29SideOrcheType selectOrcheType`

- `String productEyeIconId`

- `Int32 enterSequenceNum`


## Methods

- `String get_selectOrcheId()`

- `String get_selectOrcheName()`

- `String get_selectProductTypeId()`

- `String get_selectProductTypeName()`

- `String get_selectProductTypeDescColor()`

- `Act29SideProductType get_selectProductType()`

- `String get_selectFormDesc()`

- `Boolean get_selectFormHasBeenMade()`

- `ProductStatus get_productStatus()`

- `String get_formSegmentId()`

- `Int32 get_formSegmentNum()`

- `Single get_formSegmentRotateSecond()`

- `Boolean get_haveNewForm()`

- `Boolean get_haveFormUnlock()`

- `String get_curMainMusicId()`

- `String get_curOrcheMusicId()`

- `String get_orcheIconId()`

- `Act29SideOrcheType get_selectOrcheType()`

- `String get_productEyeIconId()`

- `Int32 get_enterSequenceNum()`

- `Void InitData(String, Int32)`

- `Void UpdateData()`

- `Boolean TrySelectFrag(String)`

- `Boolean TrySelectOrche(String)`

- `Boolean TryTransToSelectOrche()`

- `Boolean TryTransToSelectFrag()`

- `Void ClearSelectFrag()`

- `Boolean CheckHasSelectedEnoughFrag()`

- `Boolean CheckHasEnoughFragToProduct()`

- `Void SyncCurMusicId()`

- `String GetFragFormIconId(String)`

- `String GetFragSmallIconId(String)`

- `Void _LoadOrcheData()`

- `Void _LoadFragData()`

- `Void _UpdateFragNum(PlayerAct29SideActivity)`

- `Void _SetRightForm()`

- `Boolean _CheckIfFragListEqual(List`1)`

- `Void _SortSelectFragListUsedCheckProduct()`

- `Void _SetFormProperty(Act29SideFormData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningProductViewModel : IHotfixable
{
	private const Int32 PRODUCT_NEED_FRAG_NUM; // 0x0
	private ListDict`2 m_fragModelListDict; // 0x10
	private ListDict`2 m_orcheModelListDict; // 0x18
	private List`1 m_selectFragList; // 0x20
	private String m_selectOrcheId; // 0x28
	private String m_selectOrcheName; // 0x30
	private String m_orcheIconId; // 0x38
	private Act29SideOrcheType m_selectOrcheType; // 0x40
	private Act29SideProductType m_selectProductType; // 0x44
	private String m_selectProductTypeId; // 0x48
	private String m_selectProductTypeName; // 0x50
	private String m_selectProductTypeDescColor; // 0x58
	private String m_productEyeIconId; // 0x60
	private String m_selectFormDesc; // 0x68
	private String m_selectFormId; // 0x70
	private Boolean m_selectFormHasBeenMade; // 0x78
	private Act29SideData m_actData; // 0x80
	private ProductStatus m_productStatus; // 0x88
	private Boolean m_haveNewForm; // 0x8c
	private Boolean m_haveFormUnlock; // 0x8d
	private Int32 m_enterSequenceNum; // 0x90
	private String m_formSegmentId; // 0x98
	private Int32 m_formSegmentNum; // 0xa0
	private Single m_formSegmentRotateSecond; // 0xa4
	private String m_curMainMusicId; // 0xa8
	private String m_curOrcheMusicId; // 0xb0
	private String m_actId; // 0xb8
	private List`1 m_selectFragListUsedCheckProduct; // 0xc0
	private static DelegateBridge __Hotfix0_get_fragModelListDict; // 0x0
	private static DelegateBridge __Hotfix0_get_orcheModelListDict; // 0x8
	private static DelegateBridge __Hotfix0_get_selectFragList; // 0x10
	private static DelegateBridge __Hotfix0_get_selectOrcheId; // 0x18
	private static DelegateBridge __Hotfix0_get_selectOrcheName; // 0x20
	private static DelegateBridge __Hotfix0_get_selectProductTypeId; // 0x28
	private static DelegateBridge __Hotfix0_get_selectProductTypeName; // 0x30
	private static DelegateBridge __Hotfix0_get_selectProductTypeDescColor; // 0x38
	private static DelegateBridge __Hotfix0_get_selectProductType; // 0x40
	private static DelegateBridge __Hotfix0_get_selectFormDesc; // 0x48
	private static DelegateBridge __Hotfix0_get_selectFormHasBeenMade; // 0x50
	private static DelegateBridge __Hotfix0_get_productStatus; // 0x58
	private static DelegateBridge __Hotfix0_get_formSegmentId; // 0x60
	private static DelegateBridge __Hotfix0_get_formSegmentNum; // 0x68
	private static DelegateBridge __Hotfix0_get_formSegmentRotateSecond; // 0x70
	private static DelegateBridge __Hotfix0_get_haveNewForm; // 0x78
	private static DelegateBridge __Hotfix0_get_haveFormUnlock; // 0x80
	private static DelegateBridge __Hotfix0_get_curMainMusicId; // 0x88
	private static DelegateBridge __Hotfix0_get_curOrcheMusicId; // 0x90
	private static DelegateBridge __Hotfix0_get_orcheIconId; // 0x98
	private static DelegateBridge __Hotfix0_get_selectOrcheType; // 0xa0
	private static DelegateBridge __Hotfix0_get_productEyeIconId; // 0xa8
	private static DelegateBridge __Hotfix0_get_enterSequenceNum; // 0xb0
	private static DelegateBridge __Hotfix0_InitData; // 0xb8
	private static DelegateBridge __Hotfix0_UpdateData; // 0xc0
	private static DelegateBridge __Hotfix0_TrySelectFrag; // 0xc8
	private static DelegateBridge __Hotfix0_TrySelectOrche; // 0xd0
	private static DelegateBridge __Hotfix0_TryTransToSelectOrche; // 0xd8
	private static DelegateBridge __Hotfix0_TryTransToSelectFrag; // 0xe0
	private static DelegateBridge __Hotfix0_ClearSelectFrag; // 0xe8
	private static DelegateBridge __Hotfix0_CheckHasSelectedEnoughFrag; // 0xf0
	private static DelegateBridge __Hotfix0_CheckHasEnoughFragToProduct; // 0xf8
	private static DelegateBridge __Hotfix0_SyncCurMusicId; // 0x100
	private static DelegateBridge __Hotfix0_GetFragFormIconId; // 0x108
	private static DelegateBridge __Hotfix0_GetFragSmallIconId; // 0x110
	private static DelegateBridge __Hotfix0__LoadOrcheData; // 0x118
	private static DelegateBridge __Hotfix0__LoadFragData; // 0x120
	private static DelegateBridge __Hotfix0__UpdateFragNum; // 0x128
	private static DelegateBridge __Hotfix0__SetRightForm; // 0x130
	private static DelegateBridge __Hotfix0__CheckIfFragListEqual; // 0x138
	private static DelegateBridge __Hotfix0__SortSelectFragListUsedCheckProduct; // 0x140
	private static DelegateBridge __Hotfix0__SetFormProperty; // 0x148
	private static DelegateBridge _c__Hotfix0_ctor; // 0x150

	public ListDict`2 fragModelListDict { get; }
	public ListDict`2 orcheModelListDict { get; }
	public List`1 selectFragList { get; }
	public String selectOrcheId { get; }
	public String selectOrcheName { get; }
	public String selectProductTypeId { get; }
	public String selectProductTypeName { get; }
	public String selectProductTypeDescColor { get; }
	public Act29SideProductType selectProductType { get; }
	public String selectFormDesc { get; }
	public Boolean selectFormHasBeenMade { get; }
	public ProductStatus productStatus { get; }
	public String formSegmentId { get; }
	public Int32 formSegmentNum { get; }
	public Single formSegmentRotateSecond { get; }
	public Boolean haveNewForm { get; }
	public Boolean haveFormUnlock { get; }
	public String curMainMusicId { get; }
	public String curOrcheMusicId { get; }
	public String orcheIconId { get; }
	public Act29SideOrcheType selectOrcheType { get; }
	public String productEyeIconId { get; }
	public Int32 enterSequenceNum { get; }

	// RVA: 0x2334f8c VA: 0x759494cf8c
	public ListDict`2 get_fragModelListDict() { }
	// RVA: 0x23365f8 VA: 0x759494e5f8
	public ListDict`2 get_orcheModelListDict() { }
	// RVA: 0x2335174 VA: 0x759494d174
	public List`1 get_selectFragList() { }
	// RVA: 0x2339d60 VA: 0x7594951d60
	public String get_selectOrcheId() { }
	// RVA: 0x2335e28 VA: 0x759494de28
	public String get_selectOrcheName() { }
	// RVA: 0x2335c20 VA: 0x759494dc20
	public String get_selectProductTypeId() { }
	// RVA: 0x2335c88 VA: 0x759494dc88
	public String get_selectProductTypeName() { }
	// RVA: 0x2335dc0 VA: 0x759494ddc0
	public String get_selectProductTypeDescColor() { }
	// RVA: 0x233ae38 VA: 0x7594952e38
	public Act29SideProductType get_selectProductType() { }
	// RVA: 0x2335cf0 VA: 0x759494dcf0
	public String get_selectFormDesc() { }
	// RVA: 0x2335d58 VA: 0x759494dd58
	public Boolean get_selectFormHasBeenMade() { }
	// RVA: 0x23354dc VA: 0x759494d4dc
	public ProductStatus get_productStatus() { }
	// RVA: 0x233b00c VA: 0x759495300c
	public String get_formSegmentId() { }
	// RVA: 0x233b074 VA: 0x7594953074
	public Int32 get_formSegmentNum() { }
	// RVA: 0x233b0dc VA: 0x75949530dc
	public Single get_formSegmentRotateSecond() { }
	// RVA: 0x233b1ac VA: 0x75949531ac
	public Boolean get_haveNewForm() { }
	// RVA: 0x233b144 VA: 0x7594953144
	public Boolean get_haveFormUnlock() { }
	// RVA: 0x2339028 VA: 0x7594951028
	public String get_curMainMusicId() { }
	// RVA: 0x2339090 VA: 0x7594951090
	public String get_curOrcheMusicId() { }
	// RVA: 0x2335b50 VA: 0x759494db50
	public String get_orcheIconId() { }
	// RVA: 0x2336660 VA: 0x759494e660
	public Act29SideOrcheType get_selectOrcheType() { }
	// RVA: 0x2335bb8 VA: 0x759494dbb8
	public String get_productEyeIconId() { }
	// RVA: 0x2336590 VA: 0x759494e590
	public Int32 get_enterSequenceNum() { }
	// RVA: 0x233b4f4 VA: 0x75949534f4
	public Void InitData(String actId, Int32 enterSequenceNum) { }
	// RVA: 0x233bbe4 VA: 0x7594953be4
	public Void UpdateData() { }
	// RVA: 0x23390f8 VA: 0x75949510f8
	public Boolean TrySelectFrag(String selectFragId) { }
	// RVA: 0x2339404 VA: 0x7594951404
	public Boolean TrySelectOrche(String iSelectOrcheId) { }
	// RVA: 0x2339b44 VA: 0x7594951b44
	public Boolean TryTransToSelectOrche() { }
	// RVA: 0x2339ac4 VA: 0x7594951ac4
	public Boolean TryTransToSelectFrag() { }
	// RVA: 0x233952c VA: 0x759495152c
	public Void ClearSelectFrag() { }
	// RVA: 0x2335450 VA: 0x759494d450
	public Boolean CheckHasSelectedEnoughFrag() { }
	// RVA: 0x2339c5c VA: 0x7594951c5c
	public Boolean CheckHasEnoughFragToProduct() { }
	// RVA: 0x2338eb8 VA: 0x7594950eb8
	public Void SyncCurMusicId() { }
	// RVA: 0x233b214 VA: 0x7594953214
	public String GetFragFormIconId(String fragId) { }
	// RVA: 0x23359a4 VA: 0x759494d9a4
	public String GetFragSmallIconId(String fragId) { }
	// RVA: 0x233b68c VA: 0x759495368c
	private Void _LoadOrcheData() { }
	// RVA: 0x233b938 VA: 0x7594953938
	private Void _LoadFragData() { }
	// RVA: 0x233bd50 VA: 0x7594953d50
	private Void _UpdateFragNum(PlayerAct29SideActivity playerData) { }
	// RVA: 0x233bfe8 VA: 0x7594953fe8
	private Void _SetRightForm() { }
	// RVA: 0x233c404 VA: 0x7594954404
	private Boolean _CheckIfFragListEqual(List`1 fragIdList) { }
	// RVA: 0x233bec0 VA: 0x7594953ec0
	private Void _SortSelectFragListUsedCheckProduct() { }
	// RVA: 0x233c120 VA: 0x7594954120
	private Void _SetFormProperty(Act29SideFormData formData) { }
	// RVA: 0x233c528 VA: 0x7594954528
	public Void .ctor() { }
}
```