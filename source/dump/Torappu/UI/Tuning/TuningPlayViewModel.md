# TuningPlayViewModel

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `String m_selectOrcheId`

- `Act29SideOrcheType m_selectOrcheType`

- `SelectOrcheStatus m_selectOrcheStatus`

- `String m_selectProductTypeId`

- `String m_selectProductTypeTintColor`

- `Act29SideProductType m_selectProductType`

- `Boolean m_hasNewProductType`

- `String m_selectProductTypeName`

- `String m_formSegmentId`

- `Int32 m_formSegmentNum`

- `Single m_formRotateSecond`

- `String m_curMainMusicId`

- `String m_curOrcheMusicId`

- `Act29SideData m_actData`

- `String m_actId`

- `Int32 m_enterSequenceNum`

- `Int32 m_cardChangeSequenceNum`

- `Int32 m_eyeShowSequenceNum`

- `TuningCommonCardModel m_cardModel`


## Properties

- `String selectOrcheId`

- `Act29SideOrcheType selectOrcheType`

- `SelectOrcheStatus selectOrcheStatus`

- `Boolean hasNewProductType`

- `String selectProductTypeId`

- `String selectProductTypeTintColor`

- `Act29SideProductType selectProductType`

- `String selectProductTypeName`

- `String formSegmentId`

- `Int32 formSegmentNum`

- `Single formRotateSecond`

- `Int32 enterSequenceNum`

- `Int32 eyeShowSequenceNum`

- `Int32 cardChangeSequenceNum`

- `String curMainMusicId`

- `String curOrcheMusicId`

- `TuningCommonCardModel cardModel`


## Methods

- `String get_selectOrcheId()`

- `Act29SideOrcheType get_selectOrcheType()`

- `SelectOrcheStatus get_selectOrcheStatus()`

- `Boolean get_hasNewProductType()`

- `String get_selectProductTypeId()`

- `String get_selectProductTypeTintColor()`

- `Act29SideProductType get_selectProductType()`

- `String get_selectProductTypeName()`

- `String get_formSegmentId()`

- `Int32 get_formSegmentNum()`

- `Single get_formRotateSecond()`

- `Int32 get_enterSequenceNum()`

- `Int32 get_eyeShowSequenceNum()`

- `Int32 get_cardChangeSequenceNum()`

- `String get_curMainMusicId()`

- `String get_curOrcheMusicId()`

- `TuningCommonCardModel get_cardModel()`

- `Void InitData(String, Int32, Int32)`

- `Void UpdateData(String, Int32, Int32)`

- `Boolean TrySelectOrche(String)`

- `Boolean TryCloseOrche()`

- `Boolean TryOpenOrche()`

- `Void SyncCurMusicId()`

- `Void _UpdateModel()`

- `Void _LoadOrcheData()`

- `Void _CheckOutDefaultProductType(Dictionary`2)`

- `Void _SetProductDisplayProperty()`

- `Void _SetOrcheType()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningPlayViewModel : IHotfixable
{
	private ListDict`2 m_orcheModelListDict; // 0x10
	private String m_selectOrcheId; // 0x18
	private Act29SideOrcheType m_selectOrcheType; // 0x20
	private SelectOrcheStatus m_selectOrcheStatus; // 0x24
	private String m_selectProductTypeId; // 0x28
	private String m_selectProductTypeTintColor; // 0x30
	private Act29SideProductType m_selectProductType; // 0x38
	private Boolean m_hasNewProductType; // 0x3c
	private String m_selectProductTypeName; // 0x40
	private String m_formSegmentId; // 0x48
	private Int32 m_formSegmentNum; // 0x50
	private Single m_formRotateSecond; // 0x54
	private String m_curMainMusicId; // 0x58
	private String m_curOrcheMusicId; // 0x60
	private Act29SideData m_actData; // 0x68
	private String m_actId; // 0x70
	private Int32 m_enterSequenceNum; // 0x78
	private Int32 m_cardChangeSequenceNum; // 0x7c
	private Int32 m_eyeShowSequenceNum; // 0x80
	private TuningCommonCardModel m_cardModel; // 0x88
	private static DelegateBridge __Hotfix0_get_orcheModelListDict; // 0x0
	private static DelegateBridge __Hotfix0_get_selectOrcheId; // 0x8
	private static DelegateBridge __Hotfix0_get_selectOrcheType; // 0x10
	private static DelegateBridge __Hotfix0_get_selectOrcheStatus; // 0x18
	private static DelegateBridge __Hotfix0_get_hasNewProductType; // 0x20
	private static DelegateBridge __Hotfix0_get_selectProductTypeId; // 0x28
	private static DelegateBridge __Hotfix0_get_selectProductTypeTintColor; // 0x30
	private static DelegateBridge __Hotfix0_get_selectProductType; // 0x38
	private static DelegateBridge __Hotfix0_get_selectProductTypeName; // 0x40
	private static DelegateBridge __Hotfix0_get_formSegmentId; // 0x48
	private static DelegateBridge __Hotfix0_get_formSegmentNum; // 0x50
	private static DelegateBridge __Hotfix0_get_formRotateSecond; // 0x58
	private static DelegateBridge __Hotfix0_get_enterSequenceNum; // 0x60
	private static DelegateBridge __Hotfix0_get_eyeShowSequenceNum; // 0x68
	private static DelegateBridge __Hotfix0_get_cardChangeSequenceNum; // 0x70
	private static DelegateBridge __Hotfix0_get_curMainMusicId; // 0x78
	private static DelegateBridge __Hotfix0_get_curOrcheMusicId; // 0x80
	private static DelegateBridge __Hotfix0_get_cardModel; // 0x88
	private static DelegateBridge __Hotfix0_InitData; // 0x90
	private static DelegateBridge __Hotfix0_UpdateData; // 0x98
	private static DelegateBridge __Hotfix0_TrySelectOrche; // 0xa0
	private static DelegateBridge __Hotfix0_TryCloseOrche; // 0xa8
	private static DelegateBridge __Hotfix0_TryOpenOrche; // 0xb0
	private static DelegateBridge __Hotfix0_SyncCurMusicId; // 0xb8
	private static DelegateBridge __Hotfix0__UpdateModel; // 0xc0
	private static DelegateBridge __Hotfix0__LoadOrcheData; // 0xc8
	private static DelegateBridge __Hotfix0__CheckOutDefaultProductType; // 0xd0
	private static DelegateBridge __Hotfix0__SetProductDisplayProperty; // 0xd8
	private static DelegateBridge __Hotfix0__SetOrcheType; // 0xe0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xe8

	public ListDict`2 orcheModelListDict { get; }
	public String selectOrcheId { get; }
	public Act29SideOrcheType selectOrcheType { get; }
	public SelectOrcheStatus selectOrcheStatus { get; }
	public Boolean hasNewProductType { get; }
	public String selectProductTypeId { get; }
	public String selectProductTypeTintColor { get; }
	public Act29SideProductType selectProductType { get; }
	public String selectProductTypeName { get; }
	public String formSegmentId { get; }
	public Int32 formSegmentNum { get; }
	public Single formRotateSecond { get; }
	public Int32 enterSequenceNum { get; }
	public Int32 eyeShowSequenceNum { get; }
	public Int32 cardChangeSequenceNum { get; }
	public String curMainMusicId { get; }
	public String curOrcheMusicId { get; }
	public TuningCommonCardModel cardModel { get; }

	// RVA: 0x2331900 VA: 0x7594949900
	public ListDict`2 get_orcheModelListDict() { }
	// RVA: 0x2332898 VA: 0x759494a898
	public String get_selectOrcheId() { }
	// RVA: 0x23323b8 VA: 0x759494a3b8
	public Act29SideOrcheType get_selectOrcheType() { }
	// RVA: 0x232f220 VA: 0x7594947220
	public SelectOrcheStatus get_selectOrcheStatus() { }
	// RVA: 0x232f31c VA: 0x759494731c
	public Boolean get_hasNewProductType() { }
	// RVA: 0x2331190 VA: 0x7594949190
	public String get_selectProductTypeId() { }
	// RVA: 0x2331fac VA: 0x7594949fac
	public String get_selectProductTypeTintColor() { }
	// RVA: 0x23324b4 VA: 0x759494a4b4
	public Act29SideProductType get_selectProductType() { }
	// RVA: 0x232f780 VA: 0x7594947780
	public String get_selectProductTypeName() { }
	// RVA: 0x2332014 VA: 0x759494a014
	public String get_formSegmentId() { }
	// RVA: 0x233207c VA: 0x759494a07c
	public Int32 get_formSegmentNum() { }
	// RVA: 0x23320e4 VA: 0x759494a0e4
	public Single get_formRotateSecond() { }
	// RVA: 0x23316a4 VA: 0x75949496a4
	public Int32 get_enterSequenceNum() { }
	// RVA: 0x2331ccc VA: 0x7594949ccc
	public Int32 get_eyeShowSequenceNum() { }
	// RVA: 0x232f6b0 VA: 0x75949476b0
	public Int32 get_cardChangeSequenceNum() { }
	// RVA: 0x2330c0c VA: 0x7594948c0c
	public String get_curMainMusicId() { }
	// RVA: 0x2330c74 VA: 0x7594948c74
	public String get_curOrcheMusicId() { }
	// RVA: 0x232f718 VA: 0x7594947718
	public TuningCommonCardModel get_cardModel() { }
	// RVA: 0x2332900 VA: 0x759494a900
	public Void InitData(String actId, Int32 iEnterSequenceNum, Int32 iEyeShowSequenceNum) { }
	// RVA: 0x2333190 VA: 0x759494b190
	public Void UpdateData(String inputProductTypeId, Int32 iEyeShowSequenceNum, Int32 iCardChangeSequenceNum) { }
	// RVA: 0x2330fb4 VA: 0x7594948fb4
	public Boolean TrySelectOrche(String iSelectOrcheId) { }
	// RVA: 0x2330dfc VA: 0x7594948dfc
	public Boolean TryCloseOrche() { }
	// RVA: 0x2330cdc VA: 0x7594948cdc
	public Boolean TryOpenOrche() { }
	// RVA: 0x2330a9c VA: 0x7594948a9c
	public Void SyncCurMusicId() { }
	// RVA: 0x23330a8 VA: 0x759494b0a8
	private Void _UpdateModel() { }
	// RVA: 0x2332aac VA: 0x759494aaac
	private Void _LoadOrcheData() { }
	// RVA: 0x2332d58 VA: 0x759494ad58
	private Void _CheckOutDefaultProductType(Dictionary`2 melodyNax) { }
	// RVA: 0x233331c VA: 0x759494b31c
	private Void _SetProductDisplayProperty() { }
	// RVA: 0x2333268 VA: 0x759494b268
	private Void _SetOrcheType() { }
	// RVA: 0x2333470 VA: 0x759494b470
	public Void .ctor() { }
}
```