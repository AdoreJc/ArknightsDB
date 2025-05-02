# SandboxV2CookDeckView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2ItemCard _itemCardPrefab`

- `Single _matItemScale`

- `Single _foodItemScale`

- `Transform _foodItemHolder`

- `CanvasGroup _deckFoodGroup`

- `CanvasGroup _deckFrameGroup`

- `GameObject _knownFoodPanel`

- `GameObject _unknownFoodPanel`

- `GameObject _addMainMatPanel`

- `GameObject _addSubMatPanel`

- `GameObject _fullPanel`

- `Text _durationText`

- `SimpleLayoutContent _attributeContent`

- `Text _usageText`

- `Boolean m_hasInited`

- `SandboxV2ItemCard m_foodItemCard`

- `UISwitchTween m_foodTween`

- `UISwitchTween m_frameTween`

- `Adapter m_adapter`

- `String m_topicId`

- `SandboxV2Data m_gameData`

- `UIItemViewModel m_cachedFoodItem`

- `DeckFoodState m_cachedFoodState`

- `Boolean <initialRender>k__BackingField`

- `ILoadAsset <assetLoader>k__BackingField`


## Properties

- `Boolean initialRender`

- `String topicId`

- `ILoadAsset assetLoader`


## Methods

- `Boolean get_initialRender()`

- `Void set_initialRender(Boolean)`

- `Void set_topicId(String)`

- `ILoadAsset get_assetLoader()`

- `Void set_assetLoader(ILoadAsset)`

- `Void Render(List`1, List`1, SandboxV2FoodData)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2CookDeckView : MonoBehaviour, IHotfixable
{
	private SandboxV2ItemCard _itemCardPrefab; // 0x18
	private Single _matItemScale; // 0x20
	private Single _foodItemScale; // 0x24
	private List`1 _mainBranches; // 0x28
	private List`1 _subBranches; // 0x30
	private Transform _foodItemHolder; // 0x38
	private CanvasGroup _deckFoodGroup; // 0x40
	private CanvasGroup _deckFrameGroup; // 0x48
	private GameObject _knownFoodPanel; // 0x50
	private GameObject _unknownFoodPanel; // 0x58
	private GameObject _addMainMatPanel; // 0x60
	private GameObject _addSubMatPanel; // 0x68
	private GameObject _fullPanel; // 0x70
	private Text _durationText; // 0x78
	private SimpleLayoutContent _attributeContent; // 0x80
	private Text _usageText; // 0x88
	private Boolean m_hasInited; // 0x90
	private List`1 m_mainControllers; // 0x98
	private List`1 m_subControllers; // 0xa0
	private SandboxV2ItemCard m_foodItemCard; // 0xa8
	private UISwitchTween m_foodTween; // 0xb0
	private UISwitchTween m_frameTween; // 0xb8
	private Adapter m_adapter; // 0xc0
	private readonly List`1 m_subMats; // 0xc8
	private readonly List`1 m_attributes; // 0xd0
	private readonly HashSet`1 m_subAttributeSet; // 0xd8
	private readonly List`1 m_subMatIdList; // 0xe0
	private readonly StringBuilder m_builder; // 0xe8
	private String m_topicId; // 0xf0
	private SandboxV2Data m_gameData; // 0xf8
	private UIItemViewModel m_cachedFoodItem; // 0x100
	private DeckFoodState m_cachedFoodState; // 0x108
	private Boolean <initialRender>k__BackingField; // 0x10c
	private ILoadAsset <assetLoader>k__BackingField; // 0x110
	private static DelegateBridge __Hotfix0_get_initialRender; // 0x0
	private static DelegateBridge __Hotfix0_set_initialRender; // 0x8
	private static DelegateBridge __Hotfix0_set_topicId; // 0x10
	private static DelegateBridge __Hotfix0_get_assetLoader; // 0x18
	private static DelegateBridge __Hotfix0_set_assetLoader; // 0x20
	private static DelegateBridge __Hotfix0_Render; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0__SubMatComparison; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	private Boolean initialRender { get; set; }
	public String topicId { set; }
	private ILoadAsset assetLoader { get; set; }

	// RVA: 0x24c1f80 VA: 0x7594ad9f80
	private Boolean get_initialRender() { }
	// RVA: 0x24c1fe8 VA: 0x7594ad9fe8
	public Void set_initialRender(Boolean value) { }
	// RVA: 0x24c2068 VA: 0x7594ada068
	public Void set_topicId(String value) { }
	// RVA: 0x24c217c VA: 0x7594ada17c
	private ILoadAsset get_assetLoader() { }
	// RVA: 0x24c21e4 VA: 0x7594ada1e4
	public Void set_assetLoader(ILoadAsset value) { }
	// RVA: 0x24c2268 VA: 0x7594ada268
	public Void Render(List`1 mainMats, List`1 subMats, SandboxV2FoodData food) { }
	// RVA: 0x24c2dc0 VA: 0x7594adadc0
	private Void _InitIfNot() { }
	// RVA: 0x24c39bc VA: 0x7594adb9bc
	private static Int32 _SubMatComparison(SandboxV2FoodMatData x, SandboxV2FoodMatData y) { }
	// RVA: 0x24c3a70 VA: 0x7594adba70
	public Void .ctor() { }
}
```