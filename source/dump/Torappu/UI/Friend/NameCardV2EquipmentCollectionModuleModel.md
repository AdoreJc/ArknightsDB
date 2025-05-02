# NameCardV2EquipmentCollectionModuleModel

**Namespace:** `Torappu.UI.Friend`


## Fields

- `UniEquipArchiveCollectionInfoViewModel m_selfCollectionInfoViewModel`

- `Boolean isSelf`

- `Boolean m_showFriendTotalInfo`

- `Boolean m_showSelfTotalInfo`


## Methods

- `Void SwitchShowType()`

- `Void _CalcFriendModuleInfoDatas(out, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class NameCardV2EquipmentCollectionModuleModel : NameCardV2RemovableModuleBaseModel
{
	private List`1 m_infoItemViewModelList; // 0x50
	private UniEquipArchiveCollectionInfoViewModel m_selfCollectionInfoViewModel; // 0x58
	public Boolean isSelf; // 0x60
	private Boolean m_showFriendTotalInfo; // 0x61
	private Boolean m_showSelfTotalInfo; // 0x62
	private static DelegateBridge __Hotfix0_get_infoItemViewModelList; // 0x0
	private static DelegateBridge __Hotfix0_get_moduleSubType; // 0x8
	private static DelegateBridge __Hotfix0_OnLoadFriendData; // 0x10
	private static DelegateBridge __Hotfix0_OnLoadSelfData; // 0x18
	private static DelegateBridge __Hotfix0_OnRefreshSelfData; // 0x20
	private static DelegateBridge __Hotfix0_SwitchShowType; // 0x28
	private static DelegateBridge __Hotfix0__CalcFriendModuleInfoDatas; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public List`1 infoItemViewModelList { get; }
	public override NameCardV2ModuleSubType moduleSubType { get; }

	// RVA: 0x28c53c0 VA: 0x7594edd3c0
	public List`1 get_infoItemViewModelList() { }
	// RVA: 0x28c5428 VA: 0x7594edd428
	public override NameCardV2ModuleSubType get_moduleSubType() { }
	// RVA: 0x28c5490 VA: 0x7594edd490
	protected override Void OnLoadFriendData(FriendDataWithNameCard data) { }
	// RVA: 0x28c5b0c VA: 0x7594eddb0c
	protected override Void OnLoadSelfData() { }
	// RVA: 0x28c5b70 VA: 0x7594eddb70
	protected override Void OnRefreshSelfData() { }
	// RVA: 0x28c5f78 VA: 0x7594eddf78
	public Void SwitchShowType() { }
	// RVA: 0x28c5830 VA: 0x7594edd830
	private Void _CalcFriendModuleInfoDatas(out Int32 equipTotalCountWithoutLimit, out Int32 charHasModuleCountWithoutLimit) { }
	// RVA: 0x28c6090 VA: 0x7594ede090
	public Void .ctor() { }
}
```