# TuningProductConfirmViewModel

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `String m_formId`

- `String m_formDesc`

- `String m_productTypeId`

- `String m_productTypeName`

- `Act29SideProductType m_productType`

- `String m_orcheId`

- `String m_orcheName`

- `Act29SideOrcheType m_orcheType`

- `String m_productTypeTintColor`

- `String m_productTypeDescColor`

- `String m_formSegmentId`

- `Int32 m_formSegmentNum`

- `Single m_formSegmentRotateSecond`

- `Boolean m_isHiddenProduct`

- `Boolean m_isNewProductType`

- `Int32 m_enterSequenceNum`

- `String m_curMainMusicId`

- `String m_curOrcheMusicId`

- `TuningCommonCardModel m_cardModel`

- `String m_actId`


## Properties

- `String formDesc`

- `String productTypeName`

- `String productTypeId`

- `Act29SideProductType productType`

- `String orcheName`

- `String orcheId`

- `Act29SideOrcheType orcheType`

- `String productTypeTintColor`

- `String productTypeDescColor`

- `String formSegmentId`

- `Int32 formSegmentNum`

- `Single formSegmentRotateSecond`

- `Boolean isHiddenProduct`

- `Boolean isNewProductType`

- `Int32 enterSequenceNum`

- `String curMainMusicId`

- `String curOrcheMusicId`

- `TuningCommonCardModel cardModel`


## Methods

- `String get_formDesc()`

- `String get_productTypeName()`

- `String get_productTypeId()`

- `Act29SideProductType get_productType()`

- `String get_orcheName()`

- `String get_orcheId()`

- `Act29SideOrcheType get_orcheType()`

- `String get_productTypeTintColor()`

- `String get_productTypeDescColor()`

- `String get_formSegmentId()`

- `Int32 get_formSegmentNum()`

- `Single get_formSegmentRotateSecond()`

- `Boolean get_isHiddenProduct()`

- `Boolean get_isNewProductType()`

- `Int32 get_enterSequenceNum()`

- `String get_curMainMusicId()`

- `String get_curOrcheMusicId()`

- `TuningCommonCardModel get_cardModel()`

- `Void InitData(String, String, Int32, Boolean)`

- `Void SyncMusicId()`

- `Void _SetProductGroupProperty(Act29SideData)`

- `Void _SetNormalProductProperty(Act29SideData)`

- `Void _SetCircleProperty(Act29SideData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningProductConfirmViewModel : IHotfixable
{
	private String m_formId; // 0x10
	private String m_formDesc; // 0x18
	private String m_productTypeId; // 0x20
	private String m_productTypeName; // 0x28
	private Act29SideProductType m_productType; // 0x30
	private String m_orcheId; // 0x38
	private String m_orcheName; // 0x40
	private Act29SideOrcheType m_orcheType; // 0x48
	private String m_productTypeTintColor; // 0x50
	private String m_productTypeDescColor; // 0x58
	private String m_formSegmentId; // 0x60
	private Int32 m_formSegmentNum; // 0x68
	private Single m_formSegmentRotateSecond; // 0x6c
	private Boolean m_isHiddenProduct; // 0x70
	private Boolean m_isNewProductType; // 0x71
	private Int32 m_enterSequenceNum; // 0x74
	private String m_curMainMusicId; // 0x78
	private String m_curOrcheMusicId; // 0x80
	private TuningCommonCardModel m_cardModel; // 0x88
	private String m_actId; // 0x90
	private static DelegateBridge __Hotfix0_get_formDesc; // 0x0
	private static DelegateBridge __Hotfix0_get_productTypeName; // 0x8
	private static DelegateBridge __Hotfix0_get_productTypeId; // 0x10
	private static DelegateBridge __Hotfix0_get_productType; // 0x18
	private static DelegateBridge __Hotfix0_get_orcheName; // 0x20
	private static DelegateBridge __Hotfix0_get_orcheId; // 0x28
	private static DelegateBridge __Hotfix0_get_orcheType; // 0x30
	private static DelegateBridge __Hotfix0_get_productTypeTintColor; // 0x38
	private static DelegateBridge __Hotfix0_get_productTypeDescColor; // 0x40
	private static DelegateBridge __Hotfix0_get_formSegmentId; // 0x48
	private static DelegateBridge __Hotfix0_get_formSegmentNum; // 0x50
	private static DelegateBridge __Hotfix0_get_formSegmentRotateSecond; // 0x58
	private static DelegateBridge __Hotfix0_get_isHiddenProduct; // 0x60
	private static DelegateBridge __Hotfix0_get_isNewProductType; // 0x68
	private static DelegateBridge __Hotfix0_get_enterSequenceNum; // 0x70
	private static DelegateBridge __Hotfix0_get_curMainMusicId; // 0x78
	private static DelegateBridge __Hotfix0_get_curOrcheMusicId; // 0x80
	private static DelegateBridge __Hotfix0_get_cardModel; // 0x88
	private static DelegateBridge __Hotfix0_InitData; // 0x90
	private static DelegateBridge __Hotfix0_SyncMusicId; // 0x98
	private static DelegateBridge __Hotfix0__SetProductGroupProperty; // 0xa0
	private static DelegateBridge __Hotfix0__SetNormalProductProperty; // 0xa8
	private static DelegateBridge __Hotfix0__SetCircleProperty; // 0xb0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb8

	public String formDesc { get; }
	public String productTypeName { get; }
	public String productTypeId { get; }
	public Act29SideProductType productType { get; }
	public String orcheName { get; }
	public String orcheId { get; }
	public Act29SideOrcheType orcheType { get; }
	public String productTypeTintColor { get; }
	public String productTypeDescColor { get; }
	public String formSegmentId { get; }
	public Int32 formSegmentNum { get; }
	public Single formSegmentRotateSecond { get; }
	public Boolean isHiddenProduct { get; }
	public Boolean isNewProductType { get; }
	public Int32 enterSequenceNum { get; }
	public String curMainMusicId { get; }
	public String curOrcheMusicId { get; }
	public TuningCommonCardModel cardModel { get; }

	// RVA: 0x2346cc0 VA: 0x759495ecc0
	public String get_formDesc() { }
	// RVA: 0x2346b88 VA: 0x759495eb88
	public String get_productTypeName() { }
	// RVA: 0x2346ec4 VA: 0x759495eec4
	public String get_productTypeId() { }
	// RVA: 0x23466f8 VA: 0x759495e6f8
	public Act29SideProductType get_productType() { }
	// RVA: 0x2346c58 VA: 0x759495ec58
	public String get_orcheName() { }
	// RVA: 0x2346f2c VA: 0x759495ef2c
	public String get_orcheId() { }
	// RVA: 0x2346b20 VA: 0x759495eb20
	public Act29SideOrcheType get_orcheType() { }
	// RVA: 0x2346980 VA: 0x759495e980
	public String get_productTypeTintColor() { }
	// RVA: 0x2346d28 VA: 0x759495ed28
	public String get_productTypeDescColor() { }
	// RVA: 0x23469e8 VA: 0x759495e9e8
	public String get_formSegmentId() { }
	// RVA: 0x2346a50 VA: 0x759495ea50
	public Int32 get_formSegmentNum() { }
	// RVA: 0x2346ab8 VA: 0x759495eab8
	public Single get_formSegmentRotateSecond() { }
	// RVA: 0x2346bf0 VA: 0x759495ebf0
	public Boolean get_isHiddenProduct() { }
	// RVA: 0x23468b0 VA: 0x759495e8b0
	public Boolean get_isNewProductType() { }
	// RVA: 0x2346184 VA: 0x759495e184
	public Int32 get_enterSequenceNum() { }
	// RVA: 0x2345c10 VA: 0x759495dc10
	public String get_curMainMusicId() { }
	// RVA: 0x2345c78 VA: 0x759495dc78
	public String get_curOrcheMusicId() { }
	// RVA: 0x2346918 VA: 0x759495e918
	public TuningCommonCardModel get_cardModel() { }
	// RVA: 0x2346f94 VA: 0x759495ef94
	public Void InitData(String actId, String productId, Int32 iEnterSequenceNum, Boolean isNew) { }
	// RVA: 0x2345aac VA: 0x759495daac
	public Void SyncMusicId() { }
	// RVA: 0x23471bc VA: 0x759495f1bc
	private Void _SetProductGroupProperty(Act29SideData actData) { }
	// RVA: 0x23472b8 VA: 0x759495f2b8
	private Void _SetNormalProductProperty(Act29SideData actData) { }
	// RVA: 0x2347400 VA: 0x759495f400
	private Void _SetCircleProperty(Act29SideData actData) { }
	// RVA: 0x2347728 VA: 0x759495f728
	public Void .ctor() { }
}
```