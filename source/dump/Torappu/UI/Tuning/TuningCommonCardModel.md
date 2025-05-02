# TuningCommonCardModel

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `String m_productTypeBasePicId`

- `String m_orcheIconId`

- `String m_cachedProductTypeId`

- `String m_cachedOrcheId`

- `String m_cachedFormId`

- `Boolean m_isChanged`


## Properties

- `String productTypeBasePicId`

- `String orcheIconId`

- `Boolean isChanged`

- `String productTypeId`

- `String orcheId`

- `String formId`


## Methods

- `String get_productTypeBasePicId()`

- `String get_orcheIconId()`

- `Boolean get_isChanged()`

- `String get_productTypeId()`

- `String get_orcheId()`

- `String get_formId()`

- `Void LoadData(String, String, String, String)`

- `Boolean _CheckIsChanged(String, String, String)`

- `Void _ClearData()`

- `Void _LoadProductType(Act29SideData, String)`

- `Void _LoadOrche(Act29SideData, String)`

- `Void _LoadFragment(Act29SideData, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningCommonCardModel : IHotfixable
{
	private String m_productTypeBasePicId; // 0x10
	private String m_orcheIconId; // 0x18
	private List`1 m_fragmentIconIdList; // 0x20
	private String m_cachedProductTypeId; // 0x28
	private String m_cachedOrcheId; // 0x30
	private String m_cachedFormId; // 0x38
	private Boolean m_isChanged; // 0x40
	private static DelegateBridge __Hotfix0_get_productTypeBasePicId; // 0x0
	private static DelegateBridge __Hotfix0_get_orcheIconId; // 0x8
	private static DelegateBridge __Hotfix0_get_fragmentIconIdList; // 0x10
	private static DelegateBridge __Hotfix0_get_isChanged; // 0x18
	private static DelegateBridge __Hotfix0_get_productTypeId; // 0x20
	private static DelegateBridge __Hotfix0_get_orcheId; // 0x28
	private static DelegateBridge __Hotfix0_get_formId; // 0x30
	private static DelegateBridge __Hotfix0_LoadData; // 0x38
	private static DelegateBridge __Hotfix0__CheckIsChanged; // 0x40
	private static DelegateBridge __Hotfix0__ClearData; // 0x48
	private static DelegateBridge __Hotfix0__LoadProductType; // 0x50
	private static DelegateBridge __Hotfix0__LoadOrche; // 0x58
	private static DelegateBridge __Hotfix0__LoadFragment; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public String productTypeBasePicId { get; }
	public String orcheIconId { get; }
	public List`1 fragmentIconIdList { get; }
	public Boolean isChanged { get; }
	public String productTypeId { get; }
	public String orcheId { get; }
	public String formId { get; }

	// RVA: 0x23212c8 VA: 0x75949392c8
	public String get_productTypeBasePicId() { }
	// RVA: 0x2321330 VA: 0x7594939330
	public String get_orcheIconId() { }
	// RVA: 0x2321398 VA: 0x7594939398
	public List`1 get_fragmentIconIdList() { }
	// RVA: 0x2321260 VA: 0x7594939260
	public Boolean get_isChanged() { }
	// RVA: 0x2320fb8 VA: 0x7594938fb8
	public String get_productTypeId() { }
	// RVA: 0x2321088 VA: 0x7594939088
	public String get_orcheId() { }
	// RVA: 0x2321020 VA: 0x7594939020
	public String get_formId() { }
	// RVA: 0x2321470 VA: 0x7594939470
	public Void LoadData(String actId, String productTypeId, String orcheId, String formId) { }
	// RVA: 0x2321614 VA: 0x7594939614
	private Boolean _CheckIsChanged(String productTypeId, String orcheId, String formId) { }
	// RVA: 0x23216f0 VA: 0x75949396f0
	private Void _ClearData() { }
	// RVA: 0x2321784 VA: 0x7594939784
	private Void _LoadProductType(Act29SideData actData, String productTypeId) { }
	// RVA: 0x2321868 VA: 0x7594939868
	private Void _LoadOrche(Act29SideData actData, String orcheId) { }
	// RVA: 0x232194c VA: 0x759493994c
	private Void _LoadFragment(Act29SideData actData, String formId) { }
	// RVA: 0x2321c40 VA: 0x7594939c40
	public Void .ctor() { }
}
```