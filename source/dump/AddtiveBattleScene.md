# AddtiveBattleScene

**Namespace:** ` `


## Fields

- `ConstructBattleSceneParam <param>k__BackingField`

- `String <sceneAssetPath>k__BackingField`


## Properties

- `ConstructBattleSceneParam param`

- `String sceneAssetPath`


## Methods

- `ConstructBattleSceneParam get_param()`

- `Void set_param(ConstructBattleSceneParam)`

- `String get_sceneAssetPath()`

- `Void set_sceneAssetPath(String)`

- `Void OnSceneLoaded()`

- `Void OnSceneUnloaded(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class AddtiveBattleScene : IAddtiveBattleScene, IHotfixable
{
	private ConstructBattleSceneParam <param>k__BackingField; // 0x10
	private String <sceneAssetPath>k__BackingField; // 0x18
	private static DelegateBridge __Hotfix0_Construct; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8
	private static DelegateBridge __Hotfix0_get_param; // 0x10
	private static DelegateBridge __Hotfix0_set_param; // 0x18
	private static DelegateBridge __Hotfix0_get_sceneAssetPath; // 0x20
	private static DelegateBridge __Hotfix0_set_sceneAssetPath; // 0x28
	private static DelegateBridge __Hotfix0_OnSceneLoaded; // 0x30
	private static DelegateBridge __Hotfix0_OnSceneUnloaded; // 0x38

	public ConstructBattleSceneParam param { get; set; }
	public String sceneAssetPath { get; set; }

	// RVA: 0x3f6b320 VA: 0x7596583320
	public static AddtiveBattleScene Construct(ConstructBattleSceneParam param) { }
	// RVA: 0x3f6b484 VA: 0x7596583484
	private Void .ctor() { }
	// RVA: 0x3f6b280 VA: 0x7596583280
	public ConstructBattleSceneParam get_param() { }
	// RVA: 0x3f6b4f4 VA: 0x75965834f4
	private Void set_param(ConstructBattleSceneParam value) { }
	// RVA: 0x3f6b5fc VA: 0x75965835fc
	public String get_sceneAssetPath() { }
	// RVA: 0x3f6b578 VA: 0x7596583578
	private Void set_sceneAssetPath(String value) { }
	// RVA: 0x3f6b664 VA: 0x7596583664
	public Void OnSceneLoaded() { }
	// RVA: 0x3f6b704 VA: 0x7596583704
	public Void OnSceneUnloaded(Boolean bySceneTrans) { }
}
```