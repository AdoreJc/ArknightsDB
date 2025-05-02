# SandboxV2DungeonViewConfig

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `UIAtlasObject _atlasObject`

- `SandboxV2LineView _lineViewPrefab`

- `SandboxV2EnemyRushLineView _enemyRushLineViewPrefab`

- `SandboxV2ZoneView _zoneViewPrefab`

- `SandboxV2NodeFloatViewHolder _nodeFloatViewHolderPrefab`

- `SandboxV2DungeonHomeTipView _homeTipViewPrefab`

- `Color _defaultItemColor`

- `HomeAppearanceData _homeAppearanceDataNormal`

- `HomeAppearanceData _homeAppearanceDataEnemyRush`


## Properties

- `SandboxV2LineView lineViewPrefab`

- `SandboxV2EnemyRushLineView enemyRushLineViewPrefab`

- `SandboxV2ZoneView zoneViewPrefab`

- `SandboxV2NodeFloatViewHolder nodeFloatViewHolderPrefab`

- `SandboxV2DungeonHomeTipView homeTipViewPrefab`

- `Color defaultItemColor`


## Methods

- `SandboxV2LineView get_lineViewPrefab()`

- `SandboxV2EnemyRushLineView get_enemyRushLineViewPrefab()`

- `SandboxV2ZoneView get_zoneViewPrefab()`

- `SandboxV2NodeFloatViewHolder get_nodeFloatViewHolderPrefab()`

- `SandboxV2DungeonHomeTipView get_homeTipViewPrefab()`

- `Color get_defaultItemColor()`

- `Boolean _TryGetWeatherIconData(SandboxV2WeatherType, out)`

- `Boolean _TryGetNodeViewPrefab(SandboxV2NodeType, out)`

- `SandboxV2AbstractNodeView GetNodeViewPrefab(SandboxV2NodeType)`

- `SandboxV2NodeShadowView GetNodeShadowPrefab(SandboxV2NodeType)`

- `SpriteRenderData GetNodeAppearanceBkg(SandboxV2NodeType, SandboxV2NodeAppearanceType)`

- `NodeViewAppearanceData GetNodeAppearanceData(SandboxV2NodeType, SandboxV2NodeAppearanceType)`

- `WeatherIconData GetWeatherIconData(SandboxV2WeatherType)`

- `SpriteRenderData GetConstructTipSprite(SandboxV2ConstructTipType)`

- `SpriteRenderData GetZoneWeatherIcon(SandboxV2WeatherType)`

- `SeasonData GetSeasonData(SandboxV2SeasonType)`

- `FloatSpriteData GetFloatSpriteData(SandboxV2FloatAppearanceType)`

- `FloatBadgeSpriteData GetFloatBadgeSpriteData(SandboxV2QuestLineBadgeType)`

- `String GetFloatEnemyRushStackSpriteData(Int32)`

- `ItemIconData GetItemIconData(String)`

- `HomeHpAppearanceData GetHomeHpAppearanceData(SandboxV2ConstructHpType, Boolean)`

- `SpriteRenderData GetHomeBkgSprite(SandboxV2ConstructHpType, Boolean)`

- `SpriteRenderData GetHomeTipIconSprite(SandboxV2ConstructHpType, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonViewConfig : ScriptableObject, IHotfixable
{
	private UIAtlasObject _atlasObject; // 0x18
	private List`1 _dungeonBackgroundData; // 0x20
	private List`1 _nodeViewPrefabData; // 0x28
	private SandboxV2LineView _lineViewPrefab; // 0x30
	private SandboxV2EnemyRushLineView _enemyRushLineViewPrefab; // 0x38
	private SandboxV2ZoneView _zoneViewPrefab; // 0x40
	private SandboxV2NodeFloatViewHolder _nodeFloatViewHolderPrefab; // 0x48
	private SandboxV2DungeonHomeTipView _homeTipViewPrefab; // 0x50
	private List`1 _weatherIconData; // 0x58
	private List`1 _constructTipIconData; // 0x60
	private List`1 _seasonData; // 0x68
	private List`1 _floatSpriteData; // 0x70
	private List`1 _floatBadgeSpriteData; // 0x78
	private List`1 _floatEnemyRushStackSpriteData; // 0x80
	private Color _defaultItemColor; // 0x88
	private List`1 _customItemColors; // 0x98
	private HomeAppearanceData _homeAppearanceDataNormal; // 0xa0
	private HomeAppearanceData _homeAppearanceDataEnemyRush; // 0xa8
	private Dictionary`2 m_weatherIconDict; // 0xb0
	private Dictionary`2 m_nodeViewPrefabDict; // 0xb8
	private static DelegateBridge __Hotfix0_get_lineViewPrefab; // 0x0
	private static DelegateBridge __Hotfix0_get_enemyRushLineViewPrefab; // 0x8
	private static DelegateBridge __Hotfix0_get_zoneViewPrefab; // 0x10
	private static DelegateBridge __Hotfix0_get_nodeFloatViewHolderPrefab; // 0x18
	private static DelegateBridge __Hotfix0_get_homeTipViewPrefab; // 0x20
	private static DelegateBridge __Hotfix0_get_defaultItemColor; // 0x28
	private static DelegateBridge __Hotfix0__TryGetWeatherIconData; // 0x30
	private static DelegateBridge __Hotfix0__TryGetNodeViewPrefab; // 0x38
	private static DelegateBridge __Hotfix0_GetBackgroundPrefabList; // 0x40
	private static DelegateBridge __Hotfix0_GetNodeViewPrefab; // 0x48
	private static DelegateBridge __Hotfix0_GetNodeShadowPrefab; // 0x50
	private static DelegateBridge __Hotfix0_GetNodeAppearanceBkg; // 0x58
	private static DelegateBridge __Hotfix0_GetNodeAppearanceData; // 0x60
	private static DelegateBridge __Hotfix0_GetWeatherIconData; // 0x68
	private static DelegateBridge __Hotfix0_GetConstructTipSprite; // 0x70
	private static DelegateBridge __Hotfix0_GetZoneWeatherIcon; // 0x78
	private static DelegateBridge __Hotfix0_GetSeasonData; // 0x80
	private static DelegateBridge __Hotfix0_GetFloatSpriteData; // 0x88
	private static DelegateBridge __Hotfix0_GetFloatBadgeSpriteData; // 0x90
	private static DelegateBridge __Hotfix0_GetFloatEnemyRushStackSpriteData; // 0x98
	private static DelegateBridge __Hotfix0_GetItemIconData; // 0xa0
	private static DelegateBridge __Hotfix0_GetHomeHpAppearanceData; // 0xa8
	private static DelegateBridge __Hotfix0_GetHomeBkgSprite; // 0xb0
	private static DelegateBridge __Hotfix0_GetHomeTipIconSprite; // 0xb8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc0

	public SandboxV2LineView lineViewPrefab { get; }
	public SandboxV2EnemyRushLineView enemyRushLineViewPrefab { get; }
	public SandboxV2ZoneView zoneViewPrefab { get; }
	public SandboxV2NodeFloatViewHolder nodeFloatViewHolderPrefab { get; }
	public SandboxV2DungeonHomeTipView homeTipViewPrefab { get; }
	public Color defaultItemColor { get; }

	// RVA: 0x25af57c VA: 0x7594bc757c
	public SandboxV2LineView get_lineViewPrefab() { }
	// RVA: 0x25af5e4 VA: 0x7594bc75e4
	public SandboxV2EnemyRushLineView get_enemyRushLineViewPrefab() { }
	// RVA: 0x25af64c VA: 0x7594bc764c
	public SandboxV2ZoneView get_zoneViewPrefab() { }
	// RVA: 0x25ae088 VA: 0x7594bc6088
	public SandboxV2NodeFloatViewHolder get_nodeFloatViewHolderPrefab() { }
	// RVA: 0x25ae790 VA: 0x7594bc6790
	public SandboxV2DungeonHomeTipView get_homeTipViewPrefab() { }
	// RVA: 0x25af6b4 VA: 0x7594bc76b4
	public Color get_defaultItemColor() { }
	// RVA: 0x25af71c VA: 0x7594bc771c
	private Boolean _TryGetWeatherIconData(SandboxV2WeatherType weatherType, out WeatherIconData weatherIconData) { }
	// RVA: 0x25af970 VA: 0x7594bc7970
	private Boolean _TryGetNodeViewPrefab(SandboxV2NodeType nodeType, out NodeViewPrefabData nodeViewPrefabData) { }
	// RVA: 0x25afc44 VA: 0x7594bc7c44
	public ListDict`2 GetBackgroundPrefabList(String backgroundId) { }
	// RVA: 0x25afde4 VA: 0x7594bc7de4
	public SandboxV2AbstractNodeView GetNodeViewPrefab(SandboxV2NodeType nodeType) { }
	// RVA: 0x25afe88 VA: 0x7594bc7e88
	public SandboxV2NodeShadowView GetNodeShadowPrefab(SandboxV2NodeType nodeType) { }
	// RVA: 0x25aff2c VA: 0x7594bc7f2c
	public SpriteRenderData GetNodeAppearanceBkg(SandboxV2NodeType nodeType, SandboxV2NodeAppearanceType nodeAppearanceType) { }
	// RVA: 0x25b0044 VA: 0x7594bc8044
	public NodeViewAppearanceData GetNodeAppearanceData(SandboxV2NodeType nodeType, SandboxV2NodeAppearanceType nodeAppearanceType) { }
	// RVA: 0x25b0284 VA: 0x7594bc8284
	public WeatherIconData GetWeatherIconData(SandboxV2WeatherType weatherType) { }
	// RVA: 0x25b0318 VA: 0x7594bc8318
	public SpriteRenderData GetConstructTipSprite(SandboxV2ConstructTipType tipType) { }
	// RVA: 0x25b04a8 VA: 0x7594bc84a8
	public SpriteRenderData GetZoneWeatherIcon(SandboxV2WeatherType weatherType) { }
	// RVA: 0x25b05b8 VA: 0x7594bc85b8
	public SeasonData GetSeasonData(SandboxV2SeasonType seasonType) { }
	// RVA: 0x25b06d4 VA: 0x7594bc86d4
	public FloatSpriteData GetFloatSpriteData(SandboxV2FloatAppearanceType appearanceType) { }
	// RVA: 0x25b07f0 VA: 0x7594bc87f0
	public FloatBadgeSpriteData GetFloatBadgeSpriteData(SandboxV2QuestLineBadgeType badgeType) { }
	// RVA: 0x25b090c VA: 0x7594bc890c
	public String GetFloatEnemyRushStackSpriteData(Int32 stackCount) { }
	// RVA: 0x25b0a24 VA: 0x7594bc8a24
	public ItemIconData GetItemIconData(String itemId) { }
	// RVA: 0x25b0b48 VA: 0x7594bc8b48
	public HomeHpAppearanceData GetHomeHpAppearanceData(SandboxV2ConstructHpType hpType, Boolean isEnemyRush) { }
	// RVA: 0x25b0cc4 VA: 0x7594bc8cc4
	public SpriteRenderData GetHomeBkgSprite(SandboxV2ConstructHpType hpType, Boolean isEnemyRush) { }
	// RVA: 0x25b0ddc VA: 0x7594bc8ddc
	public SpriteRenderData GetHomeTipIconSprite(SandboxV2ConstructHpType hpType, Boolean isEnemyRush) { }
	// RVA: 0x25b0ef4 VA: 0x7594bc8ef4
	public Void .ctor() { }
}
```