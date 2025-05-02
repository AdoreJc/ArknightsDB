# Act1ArcadeStageBadgeModel

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `Act1ArcadeBadgeBookItemViewModel ultimateBadge`

- `ActArcadeData m_arcadeData`

- `PlayerArcadeActivity m_playerData`

- `String m_curZoneId`


## Methods

- `Void LoadData(String, String)`

- `Void SetCurZoneId(String)`

- `Void UpdateBadgeTier()`

- `Void _RefreshRuneList()`

- `Void FillBuffRuneList(List`1)`

- `Act1ArcadeBadgeBookItemViewModel GetBadgeBookItemViewModelByZoneId(String)`

- `Int32 _GetBadgeMaxTier(Act1ArcadeBadgeBookItemViewModel)`

- `Act1ArcadeBadgeBookItemViewModel _LoadItem(ArcadeBadgeData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Act1ArcadeStageBadgeModel : IHotfixable
{
	public Act1ArcadeBadgeBookItemViewModel ultimateBadge; // 0x10
	private Dictionary`2 m_zoneBadgeDict; // 0x18
	public ListDict`2 commonBadges; // 0x20
	private List`1 m_curRuneList; // 0x28
	private ActArcadeData m_arcadeData; // 0x30
	private PlayerArcadeActivity m_playerData; // 0x38
	private String m_curZoneId; // 0x40
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_SetCurZoneId; // 0x8
	private static DelegateBridge __Hotfix0_UpdateBadgeTier; // 0x10
	private static DelegateBridge __Hotfix0__RefreshRuneList; // 0x18
	private static DelegateBridge __Hotfix0_FillBuffRuneList; // 0x20
	private static DelegateBridge __Hotfix0_GetBadgeBookItemViewModelByZoneId; // 0x28
	private static DelegateBridge __Hotfix0__GetBadgeMaxTier; // 0x30
	private static DelegateBridge __Hotfix0__LoadItem; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x340d898 VA: 0x7595a25898
	public Void LoadData(String actId, String curZoneId) { }
	// RVA: 0x340dc80 VA: 0x7595a25c80
	public Void SetCurZoneId(String curZoneId) { }
	// RVA: 0x340e03c VA: 0x7595a2603c
	public Void UpdateBadgeTier() { }
	// RVA: 0x340e45c VA: 0x7595a2645c
	private Void _RefreshRuneList() { }
	// RVA: 0x340e880 VA: 0x7595a26880
	public Void FillBuffRuneList(List`1 runeList) { }
	// RVA: 0x340ea20 VA: 0x7595a26a20
	public Act1ArcadeBadgeBookItemViewModel GetBadgeBookItemViewModelByZoneId(String zoneId) { }
	// RVA: 0x340e220 VA: 0x7595a26220
	private Int32 _GetBadgeMaxTier(Act1ArcadeBadgeBookItemViewModel bookItemViewModel) { }
	// RVA: 0x340dd04 VA: 0x7595a25d04
	private Act1ArcadeBadgeBookItemViewModel _LoadItem(ArcadeBadgeData data) { }
	// RVA: 0x340ead0 VA: 0x7595a26ad0
	public Void .ctor() { }
}
```