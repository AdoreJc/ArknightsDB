# UIAssetLoader

**Namespace:** `Torappu.UI`


## Fields

- `StaticOutlinks _staticOutlinks`

- `UIShopCashIconText _cashIconText`

- `Boolean m_shouldUnloadUnusedAssets`

- `Boolean m_isInited`

- `BaseAssetLoader m_baseAssetLoader`

- `UICharIllustInfoCache m_illustInfo`

- `Boolean m_startBindTimeTicker`

- `BuildingStaticOutlinks m_buildingOutlinks`


## Properties

- `Sprite missingSprite`

- `UIItemCard itemCardPrefab`

- `UICharacterCardPanel uiCharacterCard`

- `CommonTopMenu commonTopMenuPrefab`

- `UIShopCashIconText cashIconText`

- `CommonResourceBar commonResourceBarPrefab`

- `GameObject trackPointPrefab`

- `Shader blurShader`

- `StaticOutlinks staticOutlinks`

- `UICharIllustInfoCache illustInfo`

- `BuildingStaticOutlinks buildingOutlinks`

- `BuildingGlobalNotificationHolder notifyHolder`

- `BaseAssetLoader EditorOnly_BaseAssetLoader`


## Methods

- `T LoadAsset(String)`

- `T LoadAsset(String, Int32)`

- `Void UnloadAsset(Object, Int32)`

- `Void _LegacyDirectLoader_RemoveAsset(String)`

- `Void UnloadAssetGroup(Int32)`

- `Void Start()`

- `Sprite get_missingSprite()`

- `UIItemCard get_itemCardPrefab()`

- `UICharacterCardPanel get_uiCharacterCard()`

- `CommonTopMenu get_commonTopMenuPrefab()`

- `UIShopCashIconText get_cashIconText()`

- `CommonResourceBar get_commonResourceBarPrefab()`

- `GameObject get_trackPointPrefab()`

- `Shader get_blurShader()`

- `StaticOutlinks get_staticOutlinks()`

- `UICharIllustInfoCache get_illustInfo()`

- `IEnumerator _BindTimeTicker()`

- `Void _OnTickTime()`

- `BuildingStaticOutlinks get_buildingOutlinks()`

- `BuildingGlobalNotificationHolder get_notifyHolder()`

- `BuildingStaticOutlinks _LoadBuildingOutlinks()`

- `Void _OnLowMemory()`

- `BaseAssetLoader get_EditorOnly_BaseAssetLoader()`

- `Void OpenInspectWindow()`

- `EditorInterface CreateEditorInterface()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIAssetLoader : SingletonMonoBehaviour`1, ISingletonNotAutoCreate, ILuaCallCSharp, IHotfixable
{
	public const Int32 DEFAULT_GROUP; // 0x0
	private const Int32 TIME_TICK_INTERVAL; // 0x0
	private StaticOutlinks _staticOutlinks; // 0x18
	private UIShopCashIconText _cashIconText; // 0x20
	private Boolean m_shouldUnloadUnusedAssets; // 0x28
	private Boolean m_isInited; // 0x29
	private BaseAssetLoader m_baseAssetLoader; // 0x30
	private UICharIllustInfoCache m_illustInfo; // 0x38
	private Boolean m_startBindTimeTicker; // 0x40
	private BuildingStaticOutlinks m_buildingOutlinks; // 0x48
	private static DelegateBridge __Hotfix0_LoadAsset; // 0x0
	private static DelegateBridge __Hotfix1_LoadAsset; // 0x8
	private static DelegateBridge __Hotfix0_UnloadAsset; // 0x10
	private static DelegateBridge __Hotfix0__LegacyDirectLoader_RemoveAsset; // 0x18
	private static DelegateBridge __Hotfix0_UnloadAssetGroup; // 0x20
	private static DelegateBridge __Hotfix0_OnInit; // 0x28
	private static DelegateBridge __Hotfix0_Start; // 0x30
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x38
	private static DelegateBridge __Hotfix0_get_missingSprite; // 0x40
	private static DelegateBridge __Hotfix0_get_itemCardPrefab; // 0x48
	private static DelegateBridge __Hotfix0_get_uiCharacterCard; // 0x50
	private static DelegateBridge __Hotfix0_get_commonTopMenuPrefab; // 0x58
	private static DelegateBridge __Hotfix0_get_cashIconText; // 0x60
	private static DelegateBridge __Hotfix0_get_commonResourceBarPrefab; // 0x68
	private static DelegateBridge __Hotfix0_get_trackPointPrefab; // 0x70
	private static DelegateBridge __Hotfix0_get_blurShader; // 0x78
	private static DelegateBridge __Hotfix0_get_staticOutlinks; // 0x80
	private static DelegateBridge __Hotfix0_get_illustInfo; // 0x88
	private static DelegateBridge __Hotfix0__BindTimeTicker; // 0x90
	private static DelegateBridge __Hotfix0__OnTickTime; // 0x98
	private static DelegateBridge __Hotfix0_get_buildingOutlinks; // 0xa0
	private static DelegateBridge __Hotfix0_get_notifyHolder; // 0xa8
	private static DelegateBridge __Hotfix0__LoadBuildingOutlinks; // 0xb0
	private static DelegateBridge __Hotfix0_LoadPrefab; // 0xb8
	private static DelegateBridge __Hotfix0_UnloadUnusedAssets; // 0xc0
	private static DelegateBridge __Hotfix0__OnLowMemory; // 0xc8
	private static DelegateBridge __Hotfix0__EnableFrequentUIUUA; // 0xd0
	private static DelegateBridge __Hotfix0__EnableDelayedUnload; // 0xd8
	private static DelegateBridge __Hotfix0_IsLargeMemoryDevice; // 0xe0
	private static DelegateBridge __Hotfix0_get_EditorOnly_BaseAssetLoader; // 0xe8
	private static DelegateBridge __Hotfix0_OpenInspectWindow; // 0xf0
	private static DelegateBridge __Hotfix0_CreateEditorInterface; // 0xf8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x100

	public Sprite missingSprite { get; }
	public UIItemCard itemCardPrefab { get; }
	public UICharacterCardPanel uiCharacterCard { get; }
	public CommonTopMenu commonTopMenuPrefab { get; }
	public UIShopCashIconText cashIconText { get; }
	public CommonResourceBar commonResourceBarPrefab { get; }
	public GameObject trackPointPrefab { get; }
	public Shader blurShader { get; }
	public StaticOutlinks staticOutlinks { get; }
	public UICharIllustInfoCache illustInfo { get; }
	public BuildingStaticOutlinks buildingOutlinks { get; }
	public BuildingGlobalNotificationHolder notifyHolder { get; }
	public BaseAssetLoader EditorOnly_BaseAssetLoader { get; }

	// RVA: 0x VA: 0x0
	public T LoadAsset(String path) { }
	// RVA: 0x VA: 0x0
	public T LoadAsset(String path, Int32 group) { }
	// RVA: 0x21c5ca8 VA: 0x75947ddca8
	public Void UnloadAsset(Object asset, Int32 group) { }
	// RVA: 0x21c5d40 VA: 0x75947ddd40
	private Void _LegacyDirectLoader_RemoveAsset(String assetPath) { }
	// RVA: 0x21c5dcc VA: 0x75947dddcc
	public Void UnloadAssetGroup(Int32 group) { }
	// RVA: 0x21c5e58 VA: 0x75947dde58
	protected override Void OnInit() { }
	// RVA: 0x21c5f2c VA: 0x75947ddf2c
	private Void Start() { }
	// RVA: 0x21c60e0 VA: 0x75947de0e0
	protected override Void OnDestroy() { }
	// RVA: 0x21c6208 VA: 0x75947de208
	public Sprite get_missingSprite() { }
	// RVA: 0x21c627c VA: 0x75947de27c
	public UIItemCard get_itemCardPrefab() { }
	// RVA: 0x21c62f0 VA: 0x75947de2f0
	public UICharacterCardPanel get_uiCharacterCard() { }
	// RVA: 0x21c6364 VA: 0x75947de364
	public CommonTopMenu get_commonTopMenuPrefab() { }
	// RVA: 0x21c63d8 VA: 0x75947de3d8
	public UIShopCashIconText get_cashIconText() { }
	// RVA: 0x21c6440 VA: 0x75947de440
	public CommonResourceBar get_commonResourceBarPrefab() { }
	// RVA: 0x21c64b4 VA: 0x75947de4b4
	public GameObject get_trackPointPrefab() { }
	// RVA: 0x21c6528 VA: 0x75947de528
	public Shader get_blurShader() { }
	// RVA: 0x21c659c VA: 0x75947de59c
	public StaticOutlinks get_staticOutlinks() { }
	// RVA: 0x21c6604 VA: 0x75947de604
	public UICharIllustInfoCache get_illustInfo() { }
	// RVA: 0x21c6034 VA: 0x75947de034
	private IEnumerator _BindTimeTicker() { }
	// RVA: 0x21c66dc VA: 0x75947de6dc
	private Void _OnTickTime() { }
	// RVA: 0x21c67dc VA: 0x75947de7dc
	public BuildingStaticOutlinks get_buildingOutlinks() { }
	// RVA: 0x21c68f0 VA: 0x75947de8f0
	public BuildingGlobalNotificationHolder get_notifyHolder() { }
	// RVA: 0x21c6844 VA: 0x75947de844
	private BuildingStaticOutlinks _LoadBuildingOutlinks() { }
	// RVA: 0x21c6964 VA: 0x75947de964
	public static GameObject LoadPrefab(String path, Int32 group) { }
	// RVA: 0x21c6a20 VA: 0x75947dea20
	public static Void UnloadUnusedAssets() { }
	// RVA: 0x21c6bc0 VA: 0x75947debc0
	private Void _OnLowMemory() { }
	// RVA: 0x21c6b24 VA: 0x75947deb24
	private static Boolean _EnableFrequentUIUUA() { }
	// RVA: 0x21c6cd8 VA: 0x75947decd8
	private static Boolean _EnableDelayedUnload() { }
	// RVA: 0x21c6c48 VA: 0x75947dec48
	public static Boolean IsLargeMemoryDevice() { }
	// RVA: 0x21c6d74 VA: 0x75947ded74
	public BaseAssetLoader get_EditorOnly_BaseAssetLoader() { }
	// RVA: 0x21c6dd8 VA: 0x75947dedd8
	public Void OpenInspectWindow() { }
	// RVA: 0x21c6e3c VA: 0x75947dee3c
	public EditorInterface CreateEditorInterface() { }
	// RVA: 0x21c6ea0 VA: 0x75947deea0
	public Void .ctor() { }
}
```