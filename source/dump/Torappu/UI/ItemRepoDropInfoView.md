# ItemRepoDropInfoView

**Namespace:** `Torappu.UI`


## Fields

- `UIItemDescFloatStageDropDetail _stageDropDetail`

- `Transform _stageDropContainer`

- `UIItemDescFloatBuildingProduct _buildingProduct`

- `Transform _buildingProductContainer`

- `UIItemDescFloatVoucherRelation _voucherRelationPrefab`

- `Transform _voucherRelationContainer`

- `Text _textObtain`

- `GameObject _titleOthers`

- `UIItemDescFloatStageDropDetail m_campaignDrop`

- `UIItemDescFloatStageDropDetail m_climbTowerDrop`

- `Options m_options`


## Methods

- `Void Init(Options)`

- `Void UpdateItemDropInfo(UIItemViewModel, UIItemDescViewModel)`

- `Void _DestroyViews(IDictionary`2)`

- `UIItemDescFloatStageDropDetail _CreateStageDropView()`

- `UIItemDescFloatBuildingProduct _CreateBuildingProductView()`

- `UIItemDescFloatVoucherRelation _CreateVoucherRelationView()`

- `Boolean _UpdateStageDropInfo(UIItemViewModel, UIItemDescViewModel)`

- `Boolean _UpdateBuildingProductInfo(UIItemViewModel, UIItemDescViewModel)`

- `Boolean _UpdateVoucherRelationInfo(UIItemViewModel, UIItemDescViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class ItemRepoDropInfoView : MonoBehaviour, IHotfixable
{
	private const String VOUCHER_INST_FORMAT; // 0x0
	private UIItemDescFloatStageDropDetail _stageDropDetail; // 0x18
	private Transform _stageDropContainer; // 0x20
	private UIItemDescFloatBuildingProduct _buildingProduct; // 0x28
	private Transform _buildingProductContainer; // 0x30
	private UIItemDescFloatVoucherRelation _voucherRelationPrefab; // 0x38
	private Transform _voucherRelationContainer; // 0x40
	private Text _textObtain; // 0x48
	private GameObject _titleOthers; // 0x50
	private ListDict`2 m_zoneDropList; // 0x58
	private ListDict`2 m_stageDropList; // 0x60
	private UIItemDescFloatStageDropDetail m_campaignDrop; // 0x68
	private UIItemDescFloatStageDropDetail m_climbTowerDrop; // 0x70
	private ListDict`2 m_buildingProductList; // 0x78
	private List`1 m_campaignStages; // 0x80
	private ListDict`2 m_voucherRelationList; // 0x88
	private Options m_options; // 0x90
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_UpdateItemDropInfo; // 0x8
	private static DelegateBridge __Hotfix0__DestroyViews; // 0x10
	private static DelegateBridge __Hotfix0__CreateStageDropView; // 0x18
	private static DelegateBridge __Hotfix0__CreateBuildingProductView; // 0x20
	private static DelegateBridge __Hotfix0__CreateVoucherRelationView; // 0x28
	private static DelegateBridge __Hotfix0__UpdateStageDropInfo; // 0x30
	private static DelegateBridge __Hotfix0__UpdateBuildingProductInfo; // 0x38
	private static DelegateBridge __Hotfix0__UpdateVoucherRelationInfo; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x226f028 VA: 0x7594887028
	public Void Init(Options options) { }
	// RVA: 0x226f0d8 VA: 0x75948870d8
	public Void UpdateItemDropInfo(UIItemViewModel itemModel, UIItemDescViewModel descModel) { }
	// RVA: 0x VA: 0x0
	private Void _DestroyViews(IDictionary`2 views) { }
	// RVA: 0x2270154 VA: 0x7594888154
	private UIItemDescFloatStageDropDetail _CreateStageDropView() { }
	// RVA: 0x227022c VA: 0x759488822c
	private UIItemDescFloatBuildingProduct _CreateBuildingProductView() { }
	// RVA: 0x2270304 VA: 0x7594888304
	private UIItemDescFloatVoucherRelation _CreateVoucherRelationView() { }
	// RVA: 0x226f528 VA: 0x7594887528
	private Boolean _UpdateStageDropInfo(UIItemViewModel itemModel, UIItemDescViewModel descModel) { }
	// RVA: 0x226f24c VA: 0x759488724c
	private Boolean _UpdateBuildingProductInfo(UIItemViewModel itemModel, UIItemDescViewModel descModel) { }
	// RVA: 0x226fd4c VA: 0x7594887d4c
	private Boolean _UpdateVoucherRelationInfo(UIItemViewModel itemModel, UIItemDescViewModel descModel) { }
	// RVA: 0x22703dc VA: 0x75948883dc
	public Void .ctor() { }
}
```