# SiracusaCharCardModel

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `SiracusaData m_siracusaData`

- `String m_charCardId`

- `CharCardData m_charCardData`

- `DisplayEnum m_displayStatus`

- `Color m_themeColor`

- `SiracusaCharTaskRingModel m_doingTaskRing`

- `Int32 m_selectIdx`

- `Boolean m_haveOperaItem`

- `Boolean m_isReplay`


## Properties

- `Int32 selectIdx`

- `SiracusaCharTaskRingModel selectRingModel`

- `DisplayEnum displayStatus`

- `String charCardId`

- `CharCardData charCardData`

- `Boolean isBagEmpty`

- `ItemInfoData bagItemInfoData`

- `Color themeColor`

- `String currentTaskDesc`

- `SiracusaCharTaskRingModel doingRingModel`

- `Int32 totalRingCount`

- `Int32 currentRingCount`


## Methods

- `Int32 get_selectIdx()`

- `Void set_selectIdx(Int32)`

- `SiracusaCharTaskRingModel get_selectRingModel()`

- `DisplayEnum get_displayStatus()`

- `String get_charCardId()`

- `CharCardData get_charCardData()`

- `Boolean get_isBagEmpty()`

- `ItemInfoData get_bagItemInfoData()`

- `Color get_themeColor()`

- `String get_currentTaskDesc()`

- `SiracusaCharTaskRingModel get_doingRingModel()`

- `Int32 get_totalRingCount()`

- `Int32 get_currentRingCount()`

- `Void Init(SiracusaData, PlayerSiracusaMap)`

- `SiracusaCharTaskRingModel FindTaskRingAndSelect(String)`

- `Void _ClearData()`

- `Void UpdateModel(PlayerSiracusaMap)`

- `Void UpdateReplayModel(PlayerSiracusaMap, String)`

- `Void UpdateWhenBackToBigMap(PlayerSiracusaMap)`

- `Void _UpdateModel(PlayerSiracusaMap, String)`

- `Void _ResetSelectIdxToDefault()`

- `DisplayEnum _CalcDisplayStatus(SiracusaData, PlayerSiracusaMap, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaCharCardModel : IHotfixable
{
	private SiracusaData m_siracusaData; // 0x10
	private String m_charCardId; // 0x18
	private CharCardData m_charCardData; // 0x20
	private DisplayEnum m_displayStatus; // 0x28
	private Color m_themeColor; // 0x2c
	private List`1 m_taskRingList; // 0x40
	private SiracusaCharTaskRingModel m_doingTaskRing; // 0x48
	private Int32 m_selectIdx; // 0x50
	private Boolean m_haveOperaItem; // 0x54
	private Boolean m_isReplay; // 0x55
	private static DelegateBridge __Hotfix0_get_selectIdx; // 0x0
	private static DelegateBridge __Hotfix0_set_selectIdx; // 0x8
	private static DelegateBridge __Hotfix0_get_selectRingModel; // 0x10
	private static DelegateBridge __Hotfix0_get_taskRingList; // 0x18
	private static DelegateBridge __Hotfix0_get_displayStatus; // 0x20
	private static DelegateBridge __Hotfix0_get_charCardId; // 0x28
	private static DelegateBridge __Hotfix0_get_charCardData; // 0x30
	private static DelegateBridge __Hotfix0_get_isBagEmpty; // 0x38
	private static DelegateBridge __Hotfix0_get_bagItemInfoData; // 0x40
	private static DelegateBridge __Hotfix0_get_themeColor; // 0x48
	private static DelegateBridge __Hotfix0_get_currentTaskDesc; // 0x50
	private static DelegateBridge __Hotfix0_get_doingRingModel; // 0x58
	private static DelegateBridge __Hotfix0_get_totalRingCount; // 0x60
	private static DelegateBridge __Hotfix0_get_currentRingCount; // 0x68
	private static DelegateBridge __Hotfix0_Init; // 0x70
	private static DelegateBridge __Hotfix0_FindTaskRingAndSelect; // 0x78
	private static DelegateBridge __Hotfix0__ClearData; // 0x80
	private static DelegateBridge __Hotfix0_UpdateModel; // 0x88
	private static DelegateBridge __Hotfix0_UpdateReplayModel; // 0x90
	private static DelegateBridge __Hotfix0_UpdateWhenBackToBigMap; // 0x98
	private static DelegateBridge __Hotfix0__UpdateModel; // 0xa0
	private static DelegateBridge __Hotfix0__ResetSelectIdxToDefault; // 0xa8
	private static DelegateBridge __Hotfix0__CalcDisplayStatus; // 0xb0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb8

	public Int32 selectIdx { get; set; }
	public SiracusaCharTaskRingModel selectRingModel { get; }
	public List`1 taskRingList { get; }
	public DisplayEnum displayStatus { get; }
	public String charCardId { get; }
	public CharCardData charCardData { get; }
	public Boolean isBagEmpty { get; }
	public ItemInfoData bagItemInfoData { get; }
	public Color themeColor { get; }
	public String currentTaskDesc { get; }
	public SiracusaCharTaskRingModel doingRingModel { get; }
	public Int32 totalRingCount { get; }
	public Int32 currentRingCount { get; }

	// RVA: 0x23e6504 VA: 0x75949fe504
	public Int32 get_selectIdx() { }
	// RVA: 0x23e656c VA: 0x75949fe56c
	public Void set_selectIdx(Int32 value) { }
	// RVA: 0x23e65e8 VA: 0x75949fe5e8
	public SiracusaCharTaskRingModel get_selectRingModel() { }
	// RVA: 0x23e6670 VA: 0x75949fe670
	public List`1 get_taskRingList() { }
	// RVA: 0x23e66d8 VA: 0x75949fe6d8
	public DisplayEnum get_displayStatus() { }
	// RVA: 0x23e6740 VA: 0x75949fe740
	public String get_charCardId() { }
	// RVA: 0x23e67a8 VA: 0x75949fe7a8
	public CharCardData get_charCardData() { }
	// RVA: 0x23e48a4 VA: 0x75949fc8a4
	public Boolean get_isBagEmpty() { }
	// RVA: 0x23e4914 VA: 0x75949fc914
	public ItemInfoData get_bagItemInfoData() { }
	// RVA: 0x23e49dc VA: 0x75949fc9dc
	public Color get_themeColor() { }
	// RVA: 0x23e6810 VA: 0x75949fe810
	public String get_currentTaskDesc() { }
	// RVA: 0x23e68a8 VA: 0x75949fe8a8
	public SiracusaCharTaskRingModel get_doingRingModel() { }
	// RVA: 0x23e6910 VA: 0x75949fe910
	public Int32 get_totalRingCount() { }
	// RVA: 0x23e699c VA: 0x75949fe99c
	public Int32 get_currentRingCount() { }
	// RVA: 0x23e6a1c VA: 0x75949fea1c
	public Void Init(SiracusaData siracusaData, PlayerSiracusaMap playerSiracusa) { }
	// RVA: 0x23e6b54 VA: 0x75949feb54
	public SiracusaCharTaskRingModel FindTaskRingAndSelect(String ringId) { }
	// RVA: 0x23e6c7c VA: 0x75949fec7c
	private Void _ClearData() { }
	// RVA: 0x23e6ad0 VA: 0x75949fead0
	public Void UpdateModel(PlayerSiracusaMap playerSiracusa) { }
	// RVA: 0x23e72b8 VA: 0x75949ff2b8
	public Void UpdateReplayModel(PlayerSiracusaMap playerSiracusa, String charCardId) { }
	// RVA: 0x23e7344 VA: 0x75949ff344
	public Void UpdateWhenBackToBigMap(PlayerSiracusaMap playerSiracusa) { }
	// RVA: 0x23e6d58 VA: 0x75949fed58
	private Void _UpdateModel(PlayerSiracusaMap playerSiracusa, String charCardId) { }
	// RVA: 0x23e73e4 VA: 0x75949ff3e4
	private Void _ResetSelectIdxToDefault() { }
	// RVA: 0x23e7500 VA: 0x75949ff500
	private DisplayEnum _CalcDisplayStatus(SiracusaData siracusaData, PlayerSiracusaMap playerSiracusa, Boolean isReplay) { }
	// RVA: 0x23e76b8 VA: 0x75949ff6b8
	public Void .ctor() { }
}
```