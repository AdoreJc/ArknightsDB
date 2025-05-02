# CrisisV2MapBagModel

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `String m_bagId`

- `CrisisV2BagData m_bagData`

- `BagState m_bagState`


## Properties

- `BagState bagState`

- `Boolean hasReward`

- `String bagId`

- `Int32 sortId`

- `String shortName`

- `String fullName`

- `Int32 rewardScore`

- `Int32 dimension`

- `Boolean isDaily`

- `String previewTitle`

- `String previewDesc`

- `Boolean isComplete`


## Methods

- `BagState get_bagState()`

- `Boolean get_hasReward()`

- `String get_bagId()`

- `Int32 get_sortId()`

- `String get_shortName()`

- `String get_fullName()`

- `Int32 get_rewardScore()`

- `Int32 get_dimension()`

- `Boolean get_isDaily()`

- `String get_previewTitle()`

- `String get_previewDesc()`

- `Boolean get_isComplete()`

- `Void Load(String, CrisisV2BagData, CrisisV2MapDetailData)`

- `Void UpdatePlayerData(BasicMapInfo)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2MapBagModel : IHotfixable
{
	private String m_bagId; // 0x10
	private CrisisV2BagData m_bagData; // 0x18
	private List`1 m_nodeList; // 0x20
	private BagState m_bagState; // 0x28
	private static DelegateBridge __Hotfix0_get_bagState; // 0x0
	private static DelegateBridge __Hotfix0_get_hasReward; // 0x8
	private static DelegateBridge __Hotfix0_get_bagId; // 0x10
	private static DelegateBridge __Hotfix0_get_sortId; // 0x18
	private static DelegateBridge __Hotfix0_get_shortName; // 0x20
	private static DelegateBridge __Hotfix0_get_fullName; // 0x28
	private static DelegateBridge __Hotfix0_get_rewardScore; // 0x30
	private static DelegateBridge __Hotfix0_get_nodeList; // 0x38
	private static DelegateBridge __Hotfix0_get_dimension; // 0x40
	private static DelegateBridge __Hotfix0_get_isDaily; // 0x48
	private static DelegateBridge __Hotfix0_get_previewTitle; // 0x50
	private static DelegateBridge __Hotfix0_get_previewDesc; // 0x58
	private static DelegateBridge __Hotfix0_get_isComplete; // 0x60
	private static DelegateBridge __Hotfix0_GenRewardList; // 0x68
	private static DelegateBridge __Hotfix0_Load; // 0x70
	private static DelegateBridge __Hotfix0_UpdatePlayerData; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80

	public BagState bagState { get; }
	public Boolean hasReward { get; }
	public String bagId { get; }
	public Int32 sortId { get; }
	public String shortName { get; }
	public String fullName { get; }
	public Int32 rewardScore { get; }
	public List`1 nodeList { get; }
	public Int32 dimension { get; }
	public Boolean isDaily { get; }
	public String previewTitle { get; }
	public String previewDesc { get; }
	public Boolean isComplete { get; }

	// RVA: 0x2bee340 VA: 0x7595206340
	public BagState get_bagState() { }
	// RVA: 0x2bee2a4 VA: 0x75952062a4
	public Boolean get_hasReward() { }
	// RVA: 0x2beaa50 VA: 0x7595202a50
	public String get_bagId() { }
	// RVA: 0x2bf31d4 VA: 0x759520b1d4
	public Int32 get_sortId() { }
	// RVA: 0x2bf324c VA: 0x759520b24c
	public String get_shortName() { }
	// RVA: 0x2bf32c0 VA: 0x759520b2c0
	public String get_fullName() { }
	// RVA: 0x2bed53c VA: 0x759520553c
	public Int32 get_rewardScore() { }
	// RVA: 0x2bee6b4 VA: 0x75952066b4
	public List`1 get_nodeList() { }
	// RVA: 0x2bed4c4 VA: 0x75952054c4
	public Int32 get_dimension() { }
	// RVA: 0x2bf3334 VA: 0x759520b334
	public Boolean get_isDaily() { }
	// RVA: 0x2bea728 VA: 0x7595202728
	public String get_previewTitle() { }
	// RVA: 0x2bea7bc VA: 0x75952027bc
	public String get_previewDesc() { }
	// RVA: 0x2bf33b4 VA: 0x759520b3b4
	public Boolean get_isComplete() { }
	// RVA: 0x2bea850 VA: 0x7595202850
	public List`1 GenRewardList() { }
	// RVA: 0x2bf1830 VA: 0x7595209830
	public Void Load(String bagId, CrisisV2BagData bagData, CrisisV2MapDetailData mapDetailData) { }
	// RVA: 0x2bee3a8 VA: 0x75952063a8
	public Void UpdatePlayerData(BasicMapInfo playerMapInfo) { }
	// RVA: 0x2bf176c VA: 0x759520976c
	public Void .ctor() { }
}
```