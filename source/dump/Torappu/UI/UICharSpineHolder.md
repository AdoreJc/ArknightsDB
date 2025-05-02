# UICharSpineHolder

**Namespace:** `Torappu.UI`


## Fields

- `SpineType _spineType`

- `Boolean _loadOnStart`

- `String _charSkinIdToLoad`

- `Material m_material`

- `Object m_dataSource`

- `LoadSpineParam m_loadParam`


## Properties

- `Boolean loadOnStart`

- `Boolean isLoaded`

- `String CharSkinId`


## Methods

- `Boolean get_loadOnStart()`

- `Boolean get_isLoaded()`

- `String get_CharSkinId()`

- `Void set_CharSkinId(String)`

- `Boolean LoadSpine(String, LoadSpineParam)`

- `Void ReleaseIfNot()`

- `Boolean _LoadBuildingSpine(String)`

- `Boolean _LoadBattleSpine(String)`

- `IEnumerator _LoadSpineGraphic(SkeletonAnimation)`

- `Void Awake()`

- `Void Start()`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICharSpineHolder : MonoBehaviour, IHotfixable
{
	private SpineType _spineType; // 0x18
	private Boolean _loadOnStart; // 0x1c
	private String _charSkinIdToLoad; // 0x20
	private Material m_material; // 0x28
	private Object m_dataSource; // 0x30
	private LoadSpineParam m_loadParam; // 0x38
	private static DelegateBridge __Hotfix0_get_loadOnStart; // 0x0
	private static DelegateBridge __Hotfix0_get_isLoaded; // 0x8
	private static DelegateBridge __Hotfix0_get_CharSkinId; // 0x10
	private static DelegateBridge __Hotfix0_set_CharSkinId; // 0x18
	private static DelegateBridge __Hotfix0_LoadSpine; // 0x20
	private static DelegateBridge __Hotfix0_ReleaseIfNot; // 0x28
	private static DelegateBridge __Hotfix0__LoadBuildingSpine; // 0x30
	private static DelegateBridge __Hotfix0__LoadBattleSpine; // 0x38
	private static DelegateBridge __Hotfix0__LoadSpineGraphic; // 0x40
	private static DelegateBridge __Hotfix0_Awake; // 0x48
	private static DelegateBridge __Hotfix0_Start; // 0x50
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public Boolean loadOnStart { get; }
	public Boolean isLoaded { get; }
	public String CharSkinId { get; set; }

	// RVA: 0x21cfd88 VA: 0x75947e7d88
	public Boolean get_loadOnStart() { }
	// RVA: 0x21cfdf0 VA: 0x75947e7df0
	public Boolean get_isLoaded() { }
	// RVA: 0x21cfe88 VA: 0x75947e7e88
	public String get_CharSkinId() { }
	// RVA: 0x21cfef0 VA: 0x75947e7ef0
	public Void set_CharSkinId(String value) { }
	// RVA: 0x21cff74 VA: 0x75947e7f74
	public Boolean LoadSpine(String skinId, LoadSpineParam overrideParam) { }
	// RVA: 0x21d0a34 VA: 0x75947e8a34
	public Void ReleaseIfNot() { }
	// RVA: 0x21d00f0 VA: 0x75947e80f0
	private Boolean _LoadBuildingSpine(String skinId) { }
	// RVA: 0x21d0484 VA: 0x75947e8484
	private Boolean _LoadBattleSpine(String skinId) { }
	// RVA: 0x21d0ba8 VA: 0x75947e8ba8
	private IEnumerator _LoadSpineGraphic(SkeletonAnimation skeletonAnimation) { }
	// RVA: 0x21d0ca0 VA: 0x75947e8ca0
	private Void Awake() { }
	// RVA: 0x21d0f10 VA: 0x75947e8f10
	private Void Start() { }
	// RVA: 0x21d0fa4 VA: 0x75947e8fa4
	private Void OnDestroy() { }
	// RVA: 0x21d100c VA: 0x75947e900c
	public Void .ctor() { }
}
```