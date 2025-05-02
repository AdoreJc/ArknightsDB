# RecruitSpecialGachaViewModel

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `String poolId`

- `String detailTitle`

- `String detailInfo`

- `String homeIntroDesc`

- `Status status`

- `Boolean commonSingleTkt`

- `Boolean diamondSingle`

- `Boolean commonTenTkt`

- `Boolean commonTenSingleTkt`

- `Boolean diamondTen`

- `Boolean hasRemainFlag`

- `Int32 remainCnt`

- `Int32 advancedGachaCrystalCost`

- `Int32 m_guarantee5Avail`

- `Int32 m_guarantee5Count`

- `String gachaPoolName`

- `String gachaPoolSummary`


## Methods

- `Void LoadData(GachaPoolClientData)`

- `Void RefreshPlayerData()`

- `Void _RefreshGachaPolicy()`

- `Void _AddSelectCharIdList(JObjectWrapper, RarityRank)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitSpecialGachaViewModel : IHotfixable
{
	public const String CHAR_DICT_KEY; // 0x0
	private const String DETAIL_TITLE_KEY; // 0x0
	private const String DETAIL_INFO_KEY; // 0x0
	private const String HOME_INTRO_KEY; // 0x0
	public String poolId; // 0x10
	public String detailTitle; // 0x18
	public String detailInfo; // 0x20
	public String homeIntroDesc; // 0x28
	public Status status; // 0x30
	public Dictionary`2 selectCharIdDict; // 0x38
	public Dictionary`2 selectedCharIdDict; // 0x40
	public Boolean commonSingleTkt; // 0x48
	public Boolean diamondSingle; // 0x49
	public Boolean commonTenTkt; // 0x4a
	public Boolean commonTenSingleTkt; // 0x4b
	public Boolean diamondTen; // 0x4c
	public Boolean hasRemainFlag; // 0x4d
	public Int32 remainCnt; // 0x50
	public Int32 advancedGachaCrystalCost; // 0x54
	private Int32 m_guarantee5Avail; // 0x58
	private Int32 m_guarantee5Count; // 0x5c
	public String gachaPoolName; // 0x60
	public String gachaPoolSummary; // 0x68
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_RefreshPlayerData; // 0x8
	private static DelegateBridge __Hotfix0__RefreshGachaPolicy; // 0x10
	private static DelegateBridge __Hotfix0__AddSelectCharIdList; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x271d5e8 VA: 0x7594d355e8
	public Void LoadData(GachaPoolClientData clientData) { }
	// RVA: 0x271d194 VA: 0x7594d35194
	public Void RefreshPlayerData() { }
	// RVA: 0x271e024 VA: 0x7594d36024
	private Void _RefreshGachaPolicy() { }
	// RVA: 0x271de1c VA: 0x7594d35e1c
	private Void _AddSelectCharIdList(JObjectWrapper charDict, RarityRank rank) { }
	// RVA: 0x271e1f8 VA: 0x7594d361f8
	public Void .ctor() { }
}
```