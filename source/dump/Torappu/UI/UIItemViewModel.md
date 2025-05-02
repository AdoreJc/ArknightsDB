# UIItemViewModel

**Namespace:** `Torappu.UI`


## Fields

- `String itemId`

- `String itemIconId`

- `String stackIconId`

- `ItemType type`

- `String name`

- `String description`

- `String usage`

- `String obtainApproach`

- `Int32 sortId`

- `ItemRarity rarity`

- `RarityRank charRarity`

- `ItemClassifyType classifyType`

- `Int32 furnitureRarity`

- `CharmRarity charmRarity`

- `Boolean hideInItemGet`

- `IItemViewModelPlugin <extPlugin>k__BackingField`

- `Int64 maxItemCount`

- `Int64 selectedCount`

- `Int64 requireCount`

- `Int64 itemCount`

- `Int64 validTs`

- `Int32 instId`

- `String m_loadedId`

- `String m_loadedIconId`

- `ItemRarity m_loadedRarity`

- `Sprite m_iconSprite`


## Properties

- `IItemViewModelPlugin extPlugin`

- `Sprite iconSprite`


## Methods

- `IItemViewModelPlugin get_extPlugin()`

- `Void set_extPlugin(IItemViewModelPlugin)`

- `Sprite get_iconSprite()`

- `ItemType GetItemType()`

- `String GetItemId()`

- `Int32 GetItemCount()`

- `Void SetItemCount(Int32)`

- `Boolean HasValidTs()`

- `Int32 GetExp()`

- `Int32 GetAp()`

- `Void LoadGameData(String, ItemType)`

- `Void LoadSpritesIfNeeded()`

- `Boolean CheckPlugin()`

- `Void SetPlugin(IItemViewModelPlugin)`

- `T GetPlugin()`

- `T GetPluginNotNull()`

- `Void _LoadDataItem(String, ItemType)`

- `Void _LoadFurnitureAsItem(String)`

- `Void _LoadCharAsItem(String)`

- `Void _LoadSkinAsItem(String)`

- `Void _LoadPlayerAvatarItem(String)`

- `Void _LoadCharmItem(String)`

- `Void _LoadSandboxV2Item(String)`

- `Void _LoadCarItem(String)`

- `Void _LoadHomeBackgroundItem(String)`

- `Void _LoadHomeThemeItem(String)`

- `Void _LoadNameCardSkinItem(String)`

- `Void _AddMetaValue(String, Int32)`

- `Int32 _GetMetaValue(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIItemViewModel : ISharedItemModel
{
	public const Int64 UNLIMITED_VALID_TS; // 0x0
	private const String GAIN_EXP; // 0x0
	private const String GAIN_AP; // 0x0
	public String itemId; // 0x10
	public String itemIconId; // 0x18
	public String stackIconId; // 0x20
	public ItemType type; // 0x28
	public String name; // 0x30
	public String description; // 0x38
	public String usage; // 0x40
	public String obtainApproach; // 0x48
	public Int32 sortId; // 0x50
	public ItemRarity rarity; // 0x54
	public RarityRank charRarity; // 0x58
	public ItemClassifyType classifyType; // 0x5c
	public Int32 furnitureRarity; // 0x60
	public CharmRarity charmRarity; // 0x64
	public List`1 dropMap; // 0x68
	public List`1 stageDrop; // 0x70
	public List`1 buildingProduct; // 0x78
	public List`1 voucherRelate; // 0x80
	public List`1 itemPackContent; // 0x88
	private ListDict`2 m_metaValue; // 0x90
	public Boolean hideInItemGet; // 0x98
	private IItemViewModelPlugin <extPlugin>k__BackingField; // 0xa0
	public Int64 maxItemCount; // 0xa8
	public Int64 selectedCount; // 0xb0
	public Int64 requireCount; // 0xb8
	public Int64 itemCount; // 0xc0
	public Int64 validTs; // 0xc8
	public Int32 instId; // 0xd0
	private String m_loadedId; // 0xd8
	private String m_loadedIconId; // 0xe0
	private ItemRarity m_loadedRarity; // 0xe8
	private Sprite m_iconSprite; // 0xf0

	public IItemViewModelPlugin extPlugin { get; set; }
	public Sprite iconSprite { get; }

	// RVA: 0x2186654 VA: 0x759479e654
	public IItemViewModelPlugin get_extPlugin() { }
	// RVA: 0x218665c VA: 0x759479e65c
	private Void set_extPlugin(IItemViewModelPlugin value) { }
	// RVA: 0x2186664 VA: 0x759479e664
	public Sprite get_iconSprite() { }
	// RVA: 0x2186774 VA: 0x759479e774
	public ItemType GetItemType() { }
	// RVA: 0x218677c VA: 0x759479e77c
	public String GetItemId() { }
	// RVA: 0x2186784 VA: 0x759479e784
	public Int32 GetItemCount() { }
	// RVA: 0x218678c VA: 0x759479e78c
	public Void SetItemCount(Int32 count_) { }
	// RVA: 0x2186798 VA: 0x759479e798
	public Boolean HasValidTs() { }
	// RVA: 0x21867a8 VA: 0x759479e7a8
	public Int32 GetExp() { }
	// RVA: 0x2185fe0 VA: 0x759479dfe0
	public Int32 GetAp() { }
	// RVA: 0x2186864 VA: 0x759479e864
	public Void LoadGameData(String itemId, ItemType itemType) { }
	// RVA: 0x218667c VA: 0x759479e67c
	public Void LoadSpritesIfNeeded() { }
	// RVA: 0x VA: 0x0
	public Boolean CheckPlugin() { }
	// RVA: 0x2188124 VA: 0x75947a0124
	public Void SetPlugin(IItemViewModelPlugin plugin) { }
	// RVA: 0x VA: 0x0
	public T GetPlugin() { }
	// RVA: 0x VA: 0x0
	public T GetPluginNotNull() { }
	// RVA: 0x2187d0c VA: 0x759479fd0c
	private Void _LoadDataItem(String itemId, ItemType itemType) { }
	// RVA: 0x2186cfc VA: 0x759479ecfc
	private Void _LoadFurnitureAsItem(String itemId) { }
	// RVA: 0x2186b48 VA: 0x759479eb48
	private Void _LoadCharAsItem(String charId) { }
	// RVA: 0x2186ee4 VA: 0x759479eee4
	private Void _LoadSkinAsItem(String skinId) { }
	// RVA: 0x2187118 VA: 0x759479f118
	private Void _LoadPlayerAvatarItem(String itemId) { }
	// RVA: 0x21872d8 VA: 0x759479f2d8
	private Void _LoadCharmItem(String itemId) { }
	// RVA: 0x21879d0 VA: 0x759479f9d0
	private Void _LoadSandboxV2Item(String sandboxPermItemId) { }
	// RVA: 0x21877cc VA: 0x759479f7cc
	private Void _LoadCarItem(String itemId) { }
	// RVA: 0x218748c VA: 0x759479f48c
	private Void _LoadHomeBackgroundItem(String itemId) { }
	// RVA: 0x2187630 VA: 0x759479f630
	private Void _LoadHomeThemeItem(String itemId) { }
	// RVA: 0x2187b70 VA: 0x759479fb70
	private Void _LoadNameCardSkinItem(String itemId) { }
	// RVA: 0x218812c VA: 0x75947a012c
	private Void _AddMetaValue(String key, Int32 val) { }
	// RVA: 0x21867f0 VA: 0x759479e7f0
	private Int32 _GetMetaValue(String key) { }
	// RVA: 0x21881ec VA: 0x75947a01ec
	public static UIItemViewModel FromSharedItemGetModel(ISharedItemModel from) { }
	// RVA: 0x21883c8 VA: 0x75947a03c8
	public static Void LoadPotentialDetail(UIItemViewModel cardModel, CharacterData data) { }
	// RVA: 0x21883ac VA: 0x75947a03ac
	public Void .ctor() { }
}
```