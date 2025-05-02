# GachaController

**Namespace:** `Torappu.Gacha`


## Fields

- `Single _fadeTime`

- `Camera _uiCamera`

- `Transform _bodyTransform`

- `Transform _uiPhaseContainer`

- `Transform _generalPhaseContainer`

- `Image _mask`

- `String _phase0Path`

- `String _phase1Path`

- `Int32 m_newCnt`

- `Input m_input`

- `AbstractAssetLoader m_assetLoader`

- `CharacterData m_character`

- `ProfessionSpriteHub m_professionHub`

- `GachaPhase m_phase0`

- `GachaPhase m_phase1`

- `RectTransform m_interactivePanel`

- `Coroutine m_playCorout`

- `Boolean m_isSkipped`

- `Boolean m_isSkipping`

- `RarityRank m_totalRarity`

- `StateEnum <state>k__BackingField`

- `PlayMode <playMode>k__BackingField`


## Properties

- `StateEnum state`

- `CharacterConfig charConfig`

- `Boolean isNew`

- `ProfessionSpriteHub professionHub`

- `CharacterData characterData`

- `AbstractAssetLoader assetLoader`

- `Boolean isRunning`

- `Boolean showDynEntrance`

- `RarityRank totalRarity`

- `Boolean isMultipleGacha`

- `Boolean isSkipped`

- `Boolean isSkipping`

- `PlayMode playMode`


## Methods

- `StateEnum get_state()`

- `Void set_state(StateEnum)`

- `CharacterConfig get_charConfig()`

- `Boolean get_isNew()`

- `ProfessionSpriteHub get_professionHub()`

- `CharacterData get_characterData()`

- `AbstractAssetLoader get_assetLoader()`

- `Boolean get_isRunning()`

- `Boolean get_showDynEntrance()`

- `RarityRank get_totalRarity()`

- `Boolean get_isMultipleGacha()`

- `Boolean get_isSkipped()`

- `Boolean get_isSkipping()`

- `PlayMode get_playMode()`

- `Void set_playMode(PlayMode)`

- `Void OnMaskClicked()`

- `Void PlayInternal(PlayMode, Input[], Action`1)`

- `Void PlayInternal(PlayMode, Input, Action`1)`

- `Void InitData(Input)`

- `Void FinishIfNot(String)`

- `Void SkipToEndIfNot(Boolean)`

- `Void _DoEndCb()`

- `IEnumerator _DoPlay(Input)`

- `IEnumerator _DoPhase1(Input)`

- `IEnumerator _DoSkipFromPhase1ToEnd(Input)`

- `Void _ClearResource(Boolean)`

- `Void _ClearCoroutines()`

- `Void _LoadResourceIfNot()`

- `GachaPhase _CreatePhase0()`

- `GachaPhase _CreatePhase1()`

- `GachaPhase _CreatePhaseUncached(String)`

- `GameObject _InstGachaPhase(GameObject)`

- `Void _DisposePhase0()`

- `Void _DisposePhase1()`

- `Void _DisposePhase(ref)`

- `Void _OnSceneUnloaded(Scene)`

- `RarityRank _GetTotalRarity(Input, List`1)`

- `RarityRank _GetTotalRarity(Input[], List`1)`

- `Void _PopulateItems(Input[], List`1)`

- `Void _PreloadGachaSounds(PlayMode, RarityRank, Boolean)`

- `Void OnEnable()`

- `Void OnDisable()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Gacha
public class GachaController : PersistentSingleton`1, ISingletonNotAutoCreate
{
	private const Single AUTO_EXIT_DELAY_NORMAL; // 0x0
	private const Single AUTO_EXIT_DELAY_SKIP; // 0x0
	private Single _fadeTime; // 0x18
	private Camera _uiCamera; // 0x20
	private Transform _bodyTransform; // 0x28
	private Transform _uiPhaseContainer; // 0x30
	private Transform _generalPhaseContainer; // 0x38
	private Image _mask; // 0x40
	private String _phase0Path; // 0x48
	private String _phase1Path; // 0x50
	private Int32 m_newCnt; // 0x58
	private Input m_input; // 0x60
	private AbstractAssetLoader m_assetLoader; // 0xc0
	private CharacterData m_character; // 0xc8
	private ProfessionSpriteHub m_professionHub; // 0xd0
	private GachaPhase m_phase0; // 0xd8
	private GachaPhase m_phase1; // 0xe0
	private Action`1 m_endCb; // 0xe8
	private RectTransform m_interactivePanel; // 0xf0
	private Coroutine m_playCorout; // 0xf8
	private Queue`1 m_pendingInputQueue; // 0x100
	private List`1 m_rarityList; // 0x108
	private Boolean m_isSkipped; // 0x110
	private Boolean m_isSkipping; // 0x111
	private RarityRank m_totalRarity; // 0x114
	private List`1 m_allItems; // 0x118
	private StateEnum <state>k__BackingField; // 0x120
	private PlayMode <playMode>k__BackingField; // 0x124
	private static DelegateBridge __Hotfix0_get_state; // 0x0
	private static DelegateBridge __Hotfix0_set_state; // 0x8
	private static DelegateBridge __Hotfix0_get_charConfig; // 0x10
	private static DelegateBridge __Hotfix0_get_isNew; // 0x18
	private static DelegateBridge __Hotfix0_get_professionHub; // 0x20
	private static DelegateBridge __Hotfix0_get_characterData; // 0x28
	private static DelegateBridge __Hotfix0_get_assetLoader; // 0x30
	private static DelegateBridge __Hotfix0_get_isRunning; // 0x38
	private static DelegateBridge __Hotfix0_get_itemList; // 0x40
	private static DelegateBridge __Hotfix0_get_showDynEntrance; // 0x48
	private static DelegateBridge __Hotfix0_get_totalRarity; // 0x50
	private static DelegateBridge __Hotfix0_get_rarityList; // 0x58
	private static DelegateBridge __Hotfix0_get_isMultipleGacha; // 0x60
	private static DelegateBridge __Hotfix0_get_isSkipped; // 0x68
	private static DelegateBridge __Hotfix0_get_isSkipping; // 0x70
	private static DelegateBridge __Hotfix0_get_playMode; // 0x78
	private static DelegateBridge __Hotfix0_set_playMode; // 0x80
	private static DelegateBridge __Hotfix0_Play; // 0x88
	private static DelegateBridge __Hotfix1_Play; // 0x90
	private static DelegateBridge __Hotfix0_PlayInStandaloneScene; // 0x98
	private static DelegateBridge __Hotfix1_PlayInStandaloneScene; // 0xa0
	private static DelegateBridge __Hotfix0_GetOutput; // 0xa8
	private static DelegateBridge __Hotfix0_Prewarm; // 0xb0
	private static DelegateBridge __Hotfix0_StopAll; // 0xb8
	private static DelegateBridge __Hotfix0_TryFetchAndAddCameras; // 0xc0
	private static DelegateBridge __Hotfix0_OnMaskClicked; // 0xc8
	private static DelegateBridge __Hotfix0_PlayInternal; // 0xd0
	private static DelegateBridge __Hotfix1_PlayInternal; // 0xd8
	private static DelegateBridge __Hotfix0_InitData; // 0xe0
	private static DelegateBridge __Hotfix0_FinishIfNot; // 0xe8
	private static DelegateBridge __Hotfix0_SkipToEndIfNot; // 0xf0
	private static DelegateBridge __Hotfix0__DoEndCb; // 0xf8
	private static DelegateBridge __Hotfix0__DoPlay; // 0x100
	private static DelegateBridge __Hotfix0__DoPhase1; // 0x108
	private static DelegateBridge __Hotfix0__DoSkipFromPhase1ToEnd; // 0x110
	private static DelegateBridge __Hotfix0__ClearResource; // 0x118
	private static DelegateBridge __Hotfix0__ClearCoroutines; // 0x120
	private static DelegateBridge __Hotfix0__LoadResourceIfNot; // 0x128
	private static DelegateBridge __Hotfix0__CreatePhase0; // 0x130
	private static DelegateBridge __Hotfix0__CreatePhase1; // 0x138
	private static DelegateBridge __Hotfix0__CreatePhaseUncached; // 0x140
	private static DelegateBridge __Hotfix0__InstGachaPhase; // 0x148
	private static DelegateBridge __Hotfix0__DisposePhase0; // 0x150
	private static DelegateBridge __Hotfix0__DisposePhase1; // 0x158
	private static DelegateBridge __Hotfix0__DisposePhase; // 0x160
	private static DelegateBridge __Hotfix0__OnSceneUnloaded; // 0x168
	private static DelegateBridge __Hotfix0__GetTotalRarity; // 0x170
	private static DelegateBridge __Hotfix1__GetTotalRarity; // 0x178
	private static DelegateBridge __Hotfix0__PopulateItems; // 0x180
	private static DelegateBridge __Hotfix0__PreloadGachaSounds; // 0x188
	private static DelegateBridge __Hotfix0_OnEnable; // 0x190
	private static DelegateBridge __Hotfix0_OnDisable; // 0x198
	private static DelegateBridge _c__Hotfix0_ctor; // 0x1a0

	public StateEnum state { get; set; }
	public CharacterConfig charConfig { get; }
	public Boolean isNew { get; }
	public ProfessionSpriteHub professionHub { get; }
	public CharacterData characterData { get; }
	public AbstractAssetLoader assetLoader { get; }
	public Boolean isRunning { get; }
	public ItemBundle[] itemList { get; }
	public Boolean showDynEntrance { get; }
	public RarityRank totalRarity { get; }
	public List`1 rarityList { get; }
	public Boolean isMultipleGacha { get; }
	public Boolean isSkipped { get; }
	public Boolean isSkipping { get; }
	protected PlayMode playMode { get; set; }

	// RVA: 0x35c5b94 VA: 0x7595bddb94
	public StateEnum get_state() { }
	// RVA: 0x35c5bfc VA: 0x7595bddbfc
	private Void set_state(StateEnum value) { }
	// RVA: 0x35c5c78 VA: 0x7595bddc78
	public CharacterConfig get_charConfig() { }
	// RVA: 0x35c5d1c VA: 0x7595bddd1c
	public Boolean get_isNew() { }
	// RVA: 0x35c5d84 VA: 0x7595bddd84
	public ProfessionSpriteHub get_professionHub() { }
	// RVA: 0x35c5dec VA: 0x7595bdddec
	public CharacterData get_characterData() { }
	// RVA: 0x35c5e54 VA: 0x7595bdde54
	public AbstractAssetLoader get_assetLoader() { }
	// RVA: 0x35c5ebc VA: 0x7595bddebc
	public Boolean get_isRunning() { }
	// RVA: 0x35c5f30 VA: 0x7595bddf30
	public ItemBundle[] get_itemList() { }
	// RVA: 0x35c5f98 VA: 0x7595bddf98
	public Boolean get_showDynEntrance() { }
	// RVA: 0x35c6000 VA: 0x7595bde000
	public RarityRank get_totalRarity() { }
	// RVA: 0x35c6068 VA: 0x7595bde068
	public List`1 get_rarityList() { }
	// RVA: 0x35c60d0 VA: 0x7595bde0d0
	public Boolean get_isMultipleGacha() { }
	// RVA: 0x35c6158 VA: 0x7595bde158
	public Boolean get_isSkipped() { }
	// RVA: 0x35c61c0 VA: 0x7595bde1c0
	public Boolean get_isSkipping() { }
	// RVA: 0x35c6228 VA: 0x7595bde228
	protected PlayMode get_playMode() { }
	// RVA: 0x35c6290 VA: 0x7595bde290
	private Void set_playMode(PlayMode value) { }
	// RVA: 0x35c5594 VA: 0x7595bdd594
	public static Void Play(PlayMode playMode, Input input, Action`1 endCb) { }
	// RVA: 0x35c585c VA: 0x7595bdd85c
	public static Void Play(PlayMode playMode, Input[] input, Action`1 endCb) { }
	// RVA: 0x35c6748 VA: 0x7595bde748
	public static Boolean PlayInStandaloneScene(PlayMode playMode, Input input, String backScene, Action`1 endCb) { }
	// RVA: 0x35c6824 VA: 0x7595bde824
	public static Boolean PlayInStandaloneScene(PlayMode playMode, Input input, String backScene, Options backOptions, Action`1 endCb) { }
	// RVA: 0x35c69d0 VA: 0x7595bde9d0
	public static Output GetOutput() { }
	// RVA: 0x35c6b14 VA: 0x7595bdeb14
	public static Void Prewarm(PlayMode playMode) { }
	// RVA: 0x35c6dc4 VA: 0x7595bdedc4
	public static Void StopAll() { }
	// RVA: 0x35c731c VA: 0x7595bdf31c
	public static Boolean TryFetchAndAddCameras(List`1 cameras) { }
	// RVA: 0x35c7540 VA: 0x7595bdf540
	public Void OnMaskClicked() { }
	// RVA: 0x35c64dc VA: 0x7595bde4dc
	protected Void PlayInternal(PlayMode playMode, Input[] inputList, Action`1 endCb) { }
	// RVA: 0x35c630c VA: 0x7595bde30c
	protected Void PlayInternal(PlayMode playMode, Input input, Action`1 endCb) { }
	// RVA: 0x35c7e18 VA: 0x7595bdfe18
	protected Void InitData(Input input) { }
	// RVA: 0x35c6ea4 VA: 0x7595bdeea4
	protected Void FinishIfNot(String errorMsg) { }
	// RVA: 0x35c710c VA: 0x7595bdf10c
	protected Void SkipToEndIfNot(Boolean setSkippedFlag) { }
	// RVA: 0x35c80e8 VA: 0x7595be00e8
	private Void _DoEndCb() { }
	// RVA: 0x35c7b58 VA: 0x7595bdfb58
	private IEnumerator _DoPlay(Input input) { }
	// RVA: 0x35c8260 VA: 0x7595be0260
	private IEnumerator _DoPhase1(Input input) { }
	// RVA: 0x35c8338 VA: 0x7595be0338
	private IEnumerator _DoSkipFromPhase1ToEnd(Input input) { }
	// RVA: 0x35c7fb4 VA: 0x7595bdffb4
	private Void _ClearResource(Boolean unloadUnusedResources) { }
	// RVA: 0x35c75e4 VA: 0x7595bdf5e4
	private Void _ClearCoroutines() { }
	// RVA: 0x35c6bb0 VA: 0x7595bdebb0
	private Void _LoadResourceIfNot() { }
	// RVA: 0x35c85d8 VA: 0x7595be05d8
	private GachaPhase _CreatePhase0() { }
	// RVA: 0x35c8644 VA: 0x7595be0644
	private GachaPhase _CreatePhase1() { }
	// RVA: 0x35c86b0 VA: 0x7595be06b0
	private GachaPhase _CreatePhaseUncached(String path) { }
	// RVA: 0x35c8970 VA: 0x7595be0970
	private GameObject _InstGachaPhase(GameObject prefab) { }
	// RVA: 0x35c8488 VA: 0x7595be0488
	private Void _DisposePhase0() { }
	// RVA: 0x35c84f4 VA: 0x7595be04f4
	private Void _DisposePhase1() { }
	// RVA: 0x35c8b20 VA: 0x7595be0b20
	private Void _DisposePhase(ref GachaPhase phaseField) { }
	// RVA: 0x35c8c28 VA: 0x7595be0c28
	private Void _OnSceneUnloaded(Scene scene) { }
	// RVA: 0x35c7c50 VA: 0x7595bdfc50
	private RarityRank _GetTotalRarity(Input input, List`1 rarityList) { }
	// RVA: 0x35c7678 VA: 0x7595bdf678
	private RarityRank _GetTotalRarity(Input[] inputList, List`1 rarityList) { }
	// RVA: 0x35c7968 VA: 0x7595bdf968
	private Void _PopulateItems(Input[] inputList, List`1 items) { }
	// RVA: 0x35c8cc8 VA: 0x7595be0cc8
	private Void _PreloadGachaSounds(PlayMode playMode, RarityRank rarity, Boolean isMultipleGacha) { }
	// RVA: 0x35c8e40 VA: 0x7595be0e40
	private Void OnEnable() { }
	// RVA: 0x35c8ef8 VA: 0x7595be0ef8
	private Void OnDisable() { }
	// RVA: 0x35c8fbc VA: 0x7595be0fbc
	public Void .ctor() { }
}
```