# CharacterLvlupViewModel

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `EvolvePhase evolvePhase`

- `String skinId`

- `Int32 potentialRank`

- `Int32 mainSkillLvl`

- `String powerId`

- `Sprite campLogo`

- `UplevelAttribute currentAttr`

- `Int32 currentLevel`

- `UplevelAttribute targetAttr`

- `Int32 targetLevel`

- `Int32 targetExp`

- `Int32 maxExp`

- `Single currentExpProgress`

- `Single targetExpProgress`

- `Int32 additionExpValue`

- `Boolean isMax`

- `Int32 maxValidLevel`

- `CharacterLvlupItemCollectionViewModel itemCollectionViewModel`

- `CharacterLvlupWheelViewModel wheelViewModel`

- `EditMode <editMode>k__BackingField`

- `Boolean <isCounting>k__BackingField`

- `PlayerCharacter m_playerChar`

- `CharacterData m_charData`

- `Int32 m_cachedMaxLevelExp`

- `ExpAndGoldSelectedStatus m_cachedStatus`


## Properties

- `EditMode editMode`

- `Boolean isCounting`

- `Boolean isScrollMode`

- `Int32 wasteExp`


## Methods

- `EditMode get_editMode()`

- `Void set_editMode(EditMode)`

- `Boolean get_isCounting()`

- `Void set_isCounting(Boolean)`

- `Boolean get_isScrollMode()`

- `Int32 get_wasteExp()`

- `Void SetEditModeAndCounting(EditMode, Boolean)`

- `Void LoadData(PlayerCharacter, CharacterData)`

- `Void ApplyAdditionalExp(Int32)`

- `Void TryModifyScrollIndex(Int32, out)`

- `Void TryModifyScrollToLevel(Int32, out)`

- `Int32 CalcCurrentAddExp()`

- `Void CacheExpAndGoldSelectedStatus()`

- `Void ConsumeCachedStatus()`

- `Boolean IsCurrentMaxLevel()`

- `Boolean IsCurrentMaxEvolve()`

- `Boolean CheckExpValid(out)`

- `Boolean CheckGoldValid(out)`

- `Boolean CalcEstimateLackExpCount(Int32, out, out)`

- `Void _ApplyAdditionWithTargetLevelInfo(LevelInfo)`

- `LevelInfo _CalcTargetLevel(Int32)`

- `Int32 _CalcExpsToTargetLevel(Int32)`

- `Int32 _CalcMaxValidLevel()`

- `ExpAndGoldSelectedStatus _CalcStatusToLevel(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterLvlupViewModel : IHotfixable
{
	public EvolvePhase evolvePhase; // 0x10
	public String skinId; // 0x18
	public Int32 potentialRank; // 0x20
	public Int32 mainSkillLvl; // 0x24
	public String powerId; // 0x28
	public Sprite campLogo; // 0x30
	public UplevelAttribute currentAttr; // 0x38
	public Int32 currentLevel; // 0x48
	public UplevelAttribute targetAttr; // 0x4c
	public Int32 targetLevel; // 0x5c
	public Int32 targetExp; // 0x60
	public Int32 maxExp; // 0x64
	public Single currentExpProgress; // 0x68
	public Single targetExpProgress; // 0x6c
	public Int32 additionExpValue; // 0x70
	public Boolean isMax; // 0x74
	public Int32 maxValidLevel; // 0x78
	public CharacterLvlupItemCollectionViewModel itemCollectionViewModel; // 0x80
	public CharacterLvlupWheelViewModel wheelViewModel; // 0x88
	private EditMode <editMode>k__BackingField; // 0x90
	private Boolean <isCounting>k__BackingField; // 0x94
	private PlayerCharacter m_playerChar; // 0x98
	private CharacterData m_charData; // 0xa0
	private Int32 m_cachedMaxLevelExp; // 0xa8
	private ExpAndGoldSelectedStatus m_cachedStatus; // 0xb0
	private static DelegateBridge __Hotfix0_get_editMode; // 0x0
	private static DelegateBridge __Hotfix0_set_editMode; // 0x8
	private static DelegateBridge __Hotfix0_get_isCounting; // 0x10
	private static DelegateBridge __Hotfix0_set_isCounting; // 0x18
	private static DelegateBridge __Hotfix0_get_isScrollMode; // 0x20
	private static DelegateBridge __Hotfix0_get_wasteExp; // 0x28
	private static DelegateBridge __Hotfix0_SetEditModeAndCounting; // 0x30
	private static DelegateBridge __Hotfix0_LoadData; // 0x38
	private static DelegateBridge __Hotfix0_ApplyAdditionalExp; // 0x40
	private static DelegateBridge __Hotfix0_TryModifyScrollIndex; // 0x48
	private static DelegateBridge __Hotfix0_TryModifyScrollToLevel; // 0x50
	private static DelegateBridge __Hotfix0_CalcCurrentAddExp; // 0x58
	private static DelegateBridge __Hotfix0_CacheExpAndGoldSelectedStatus; // 0x60
	private static DelegateBridge __Hotfix0_ConsumeCachedStatus; // 0x68
	private static DelegateBridge __Hotfix0_IsCurrentMaxLevel; // 0x70
	private static DelegateBridge __Hotfix0_IsCurrentMaxEvolve; // 0x78
	private static DelegateBridge __Hotfix0_CheckExpValid; // 0x80
	private static DelegateBridge __Hotfix0_CheckGoldValid; // 0x88
	private static DelegateBridge __Hotfix0_CalcEstimateLackExpCount; // 0x90
	private static DelegateBridge __Hotfix0__ApplyAdditionWithTargetLevelInfo; // 0x98
	private static DelegateBridge __Hotfix0__CalcTargetLevel; // 0xa0
	private static DelegateBridge __Hotfix0__CalcExpsToTargetLevel; // 0xa8
	private static DelegateBridge __Hotfix0__CalcMaxValidLevel; // 0xb0
	private static DelegateBridge __Hotfix0__CalcStatusToLevel; // 0xb8
	private static DelegateBridge __Hotfix0__CalcValidCountWithExpItemLimit; // 0xc0
	private static DelegateBridge __Hotfix0__CalcExpCountWithoutLimit; // 0xc8
	private static DelegateBridge __Hotfix0__CheckTargetExpReachable; // 0xd0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xd8

	public EditMode editMode { get; set; }
	public Boolean isCounting { get; set; }
	public Boolean isScrollMode { get; }
	public Int32 wasteExp { get; }

	// RVA: 0x2d5da74 VA: 0x7595375a74
	public EditMode get_editMode() { }
	// RVA: 0x2d603e4 VA: 0x75953783e4
	private Void set_editMode(EditMode value) { }
	// RVA: 0x2d5e430 VA: 0x7595376430
	public Boolean get_isCounting() { }
	// RVA: 0x2d60460 VA: 0x7595378460
	private Void set_isCounting(Boolean value) { }
	// RVA: 0x2d604e0 VA: 0x75953784e0
	public Boolean get_isScrollMode() { }
	// RVA: 0x2d60554 VA: 0x7595378554
	public Int32 get_wasteExp() { }
	// RVA: 0x2d5dbbc VA: 0x7595375bbc
	public Void SetEditModeAndCounting(EditMode mode, Boolean setCounting) { }
	// RVA: 0x2d5d258 VA: 0x7595375258
	public Void LoadData(PlayerCharacter playerChar, CharacterData charData) { }
	// RVA: 0x2d5d888 VA: 0x7595375888
	public Void ApplyAdditionalExp(Int32 addExp) { }
	// RVA: 0x2d5df24 VA: 0x7595375f24
	public Void TryModifyScrollIndex(Int32 index, out Boolean needNoMoreScroll) { }
	// RVA: 0x2d5e498 VA: 0x7595376498
	public Void TryModifyScrollToLevel(Int32 targetLevel, out Boolean isSameLevel) { }
	// RVA: 0x2d5d818 VA: 0x7595375818
	public Int32 CalcCurrentAddExp() { }
	// RVA: 0x2d5dadc VA: 0x7595375adc
	public Void CacheExpAndGoldSelectedStatus() { }
	// RVA: 0x2d5e22c VA: 0x759537622c
	public Void ConsumeCachedStatus() { }
	// RVA: 0x2d61d44 VA: 0x7595379d44
	public Boolean IsCurrentMaxLevel() { }
	// RVA: 0x2d61dd8 VA: 0x7595379dd8
	public Boolean IsCurrentMaxEvolve() { }
	// RVA: 0x2d5ea60 VA: 0x7595376a60
	public Boolean CheckExpValid(out Int32 lackExp) { }
	// RVA: 0x2d5e910 VA: 0x7595376910
	public Boolean CheckGoldValid(out Int64 lackGold) { }
	// RVA: 0x2d61e64 VA: 0x7595379e64
	public Boolean CalcEstimateLackExpCount(Int32 lackExp, out String expName, out Int32 expCount) { }
	// RVA: 0x2d6146c VA: 0x759537946c
	private Void _ApplyAdditionWithTargetLevelInfo(LevelInfo targetLevelInfo) { }
	// RVA: 0x2d60f58 VA: 0x7595378f58
	private LevelInfo _CalcTargetLevel(Int32 addExp) { }
	// RVA: 0x2d605c4 VA: 0x75953785c4
	private Int32 _CalcExpsToTargetLevel(Int32 level) { }
	// RVA: 0x2d606ac VA: 0x75953786ac
	private Int32 _CalcMaxValidLevel() { }
	// RVA: 0x2d617b4 VA: 0x75953797b4
	private ExpAndGoldSelectedStatus _CalcStatusToLevel(Int32 level) { }
	// RVA: 0x2d62154 VA: 0x759537a154
	private static Int32 _CalcValidCountWithExpItemLimit(CharacterLvlupItemCardViewModel[] expItems, Int32 totalExp, Int32[] expCountArray) { }
	// RVA: 0x2d6251c VA: 0x759537a51c
	private static Void _CalcExpCountWithoutLimit(CharacterLvlupItemCardViewModel[] expItems, Int32 leftExp, Int32[] expCountArray) { }
	// RVA: 0x2d62404 VA: 0x759537a404
	private static Boolean _CheckTargetExpReachable(CharacterLvlupItemCardViewModel[] expItems, Int32 targetExp) { }
	// RVA: 0x2d5d114 VA: 0x7595375114
	public Void .ctor() { }
}
```