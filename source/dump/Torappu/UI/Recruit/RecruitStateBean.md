# RecruitStateBean

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `Output gachaOutput`

- `String gachaPoolDetailId`

- `Boolean detailNeedScroll`

- `Int32 detailScrollIndex`

- `GachaObjGroupType detailGroupType`

- `BuildSlotGroupViewProperty slotGroupProperty`

- `BuildInfoViewProperty buildInfoProperty`

- `ResourceBarViewProperty _resourceBarProperty`

- `Boolean m_isInited`

- `Boolean m_needForceGetDetail`


## Properties

- `Int64 currentGold`


## Methods

- `Int64 get_currentGold()`

- `Void InitDataIfNeeded()`

- `Void LoadBuildData()`

- `Void UpdateResource()`

- `Void MarkForcePoolDetail()`

- `Boolean ConsumeForcePoolDetail()`

- `Int64 CalcFastFinishGold(Int32)`

- `Boolean CheckIfCanFastFinish(Int32)`

- `Boolean HasEnoughResourceToGacha(String)`

- `Boolean HasEnoughResourceToTenGacha(String)`

- `Void _UpdateResource()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitStateBean : PageSingleComponent, ISingletonNotAutoCreate, IStateBean, IHotfixable, IDataBindWrapper
{
	public const Int32 BUILD_SLOT_COUNT; // 0x0
	public GachaResult[] gachaResult; // 0x20
	public Output gachaOutput; // 0x28
	public String gachaPoolDetailId; // 0x80
	public Boolean detailNeedScroll; // 0x88
	public Int32 detailScrollIndex; // 0x8c
	public GachaObjGroupType detailGroupType; // 0x90
	public BuildSlotGroupViewProperty slotGroupProperty; // 0x98
	public BuildInfoViewProperty buildInfoProperty; // 0xa0
	private ResourceBarViewProperty _resourceBarProperty; // 0xa8
	private Boolean m_isInited; // 0xb0
	private Boolean m_needForceGetDetail; // 0xb1
	private static DelegateBridge __Hotfix0_get_currentGold; // 0x0
	private static DelegateBridge __Hotfix0_InitDataIfNeeded; // 0x8
	private static DelegateBridge __Hotfix0_LoadBuildData; // 0x10
	private static DelegateBridge __Hotfix0_UpdateResource; // 0x18
	private static DelegateBridge __Hotfix0_MarkForcePoolDetail; // 0x20
	private static DelegateBridge __Hotfix0_ConsumeForcePoolDetail; // 0x28
	private static DelegateBridge __Hotfix0_CalcCommonRecruitBuildCost; // 0x30
	private static DelegateBridge __Hotfix0_GetRecruitBuildMaxMillsec; // 0x38
	private static DelegateBridge __Hotfix0_CheckIsSpecialTag; // 0x40
	private static DelegateBridge __Hotfix0_CalcFastFinishGold; // 0x48
	private static DelegateBridge __Hotfix0_CheckIfCanFastFinish; // 0x50
	private static DelegateBridge __Hotfix0_HasEnoughResourceToGacha; // 0x58
	private static DelegateBridge __Hotfix0_HasEnoughResourceToTenGacha; // 0x60
	private static DelegateBridge __Hotfix0__UpdateResource; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	public Int64 currentGold { get; }

	// RVA: 0x26fe170 VA: 0x7594d16170
	public Int64 get_currentGold() { }
	// RVA: 0x26f93a8 VA: 0x7594d113a8
	public Void InitDataIfNeeded() { }
	// RVA: 0x26f86ac VA: 0x7594d106ac
	public Void LoadBuildData() { }
	// RVA: 0x26f29f8 VA: 0x7594d0a9f8
	public Void UpdateResource() { }
	// RVA: 0x26fa8dc VA: 0x7594d128dc
	public Void MarkForcePoolDetail() { }
	// RVA: 0x26f8d34 VA: 0x7594d10d34
	public Boolean ConsumeForcePoolDetail() { }
	// RVA: 0x26fd02c VA: 0x7594d1502c
	public static KeyValuePair`2 CalcCommonRecruitBuildCost(Int64 costTimeMillsec, Int32 selectedTagNum) { }
	// RVA: 0x26fde0c VA: 0x7594d15e0c
	public static Int64 GetRecruitBuildMaxMillsec() { }
	// RVA: 0x26fdeac VA: 0x7594d15eac
	public static Boolean CheckIsSpecialTag(Int32 tagId) { }
	// RVA: 0x26fe31c VA: 0x7594d1631c
	public Int64 CalcFastFinishGold(Int32 slotIndex) { }
	// RVA: 0x26f7b84 VA: 0x7594d0fb84
	public Boolean CheckIfCanFastFinish(Int32 slotIndex) { }
	// RVA: 0x26f9c64 VA: 0x7594d11c64
	public Boolean HasEnoughResourceToGacha(String gachaPoolId) { }
	// RVA: 0x26fe6ec VA: 0x7594d166ec
	public Boolean HasEnoughResourceToTenGacha(String gachaPoolId) { }
	// RVA: 0x26fe234 VA: 0x7594d16234
	private Void _UpdateResource() { }
	// RVA: 0x26fe7b8 VA: 0x7594d167b8
	public Void .ctor() { }
}
```