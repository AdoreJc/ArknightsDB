# UIBattleLegionCharacterMenuPanel

**Namespace:** `Torappu.Battle.UI`


## Fields

- `EasyInstancePool _characterMenuDetailList`

- `Follower2D _follower`

- `Image _levelMaxImage`

- `Image _levelMaxImageHL`

- `Single m_openTweenTime`

- `Tween m_canvasTween`

- `Tween m_maxLevelTween`

- `Tween m_maxLevelBgTween`

- `Boolean m_isMaxLevel`

- `Boolean m_isDummy`

- `Boolean m_isOpen`


## Properties

- `Boolean isOpen`


## Methods

- `Boolean get_isOpen()`

- `Void set_isOpen(Boolean)`

- `Void Awake()`

- `Void OnDestroy()`

- `Void SetData(Character, List`1, Tile, Int32, Boolean)`

- `Void _ApplyMaxLevelTween()`

- `Void Hide()`

- `Void ShowHighLightProfessions(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIBattleLegionCharacterMenuPanel : MonoBehaviour, IHotfixable
{
	private EasyInstancePool _characterMenuDetailList; // 0x18
	private Follower2D _follower; // 0x20
	private Image _levelMaxImage; // 0x28
	private Image _levelMaxImageHL; // 0x30
	private Single m_openTweenTime; // 0x38
	private Dictionary`2 m_cachedLegionStatus; // 0x40
	private Tween m_canvasTween; // 0x48
	private Tween m_maxLevelTween; // 0x50
	private Tween m_maxLevelBgTween; // 0x58
	private Boolean m_isMaxLevel; // 0x60
	private Boolean m_isDummy; // 0x61
	private Boolean m_isOpen; // 0x62
	private readonly Vector3 TWEEN_MAXLEVEL_ICON_START_POS; // 0x64
	private readonly Single TWEEN_MAXLEVEL_ICON_CHECK_POINT_POS_Y; // 0x70
	private readonly Single TWEEN_MAXLEVEL_ICON_CHECK_POINT_DURATION; // 0x74
	private readonly Single TWEEN_MAXLEVEL_ICON_END_POS_Y; // 0x78
	private readonly Single TWEEN_MAXLEVEL_ICON_END_DURATION; // 0x7c
	private readonly Vector3 TWEEN_MAXLEVEL_BACK_START_SCALE; // 0x80
	private readonly Single TWEEN_MAXLEVEL_BACK_FINAL_SCALE; // 0x8c
	private readonly Single TWEEN_MAXLEVEL_BACK_FINAL_SCALE_DURATION; // 0x90
	private readonly Single TWEEN_MAXLEVEL_BACK_END_FADE_DURATION; // 0x94
	private readonly Single TWEEN_START_CANVSE_ALPHA_STEP1; // 0x98
	private readonly Single TWEEN_START_CANVSE_ALPHA_STEP2; // 0x9c
	private readonly Single TWEEN_START_CANVSE_ALPHA_STEP3; // 0xa0
	private readonly Single TWEEN_START_CANVSE_ALPHA_END; // 0xa4
	private readonly Single TWEEN_START_CANVSE_ALPHA_STEP1_PERCENT; // 0xa8
	private readonly Single TWEEN_START_CANVSE_ALPHA_STEP2_PERCENT; // 0xac
	private static DelegateBridge __Hotfix0_get_isOpen; // 0x0
	private static DelegateBridge __Hotfix0_set_isOpen; // 0x8
	private static DelegateBridge __Hotfix0_Awake; // 0x10
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x18
	private static DelegateBridge __Hotfix0_SetData; // 0x20
	private static DelegateBridge __Hotfix0__ApplyMaxLevelTween; // 0x28
	private static DelegateBridge __Hotfix0_Hide; // 0x30
	private static DelegateBridge __Hotfix0_ShowHighLightProfessions; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public Boolean isOpen { get; set; }

	// RVA: 0x203d5c0 VA: 0x75946555c0
	public Boolean get_isOpen() { }
	// RVA: 0x203d628 VA: 0x7594655628
	private Void set_isOpen(Boolean value) { }
	// RVA: 0x203d714 VA: 0x7594655714
	private Void Awake() { }
	// RVA: 0x203dc70 VA: 0x7594655c70
	private Void OnDestroy() { }
	// RVA: 0x203dd18 VA: 0x7594655d18
	public Void SetData(Character character, List`1 legionStatus, Tile followTile, Int32 maxLevel, Boolean isDummy) { }
	// RVA: 0x203e4c4 VA: 0x75946564c4
	private Void _ApplyMaxLevelTween() { }
	// RVA: 0x203e40c VA: 0x759465640c
	public Void Hide() { }
	// RVA: 0x203e76c VA: 0x759465676c
	public Void ShowHighLightProfessions(List`1 hlList) { }
	// RVA: 0x203e9a0 VA: 0x75946569a0
	public Void .ctor() { }
}
```