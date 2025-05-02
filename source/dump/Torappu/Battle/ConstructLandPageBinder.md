# ConstructLandPageBinder

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean m_isReady`

- `ConstructPageMsg m_pageMsg`

- `ConstructLandPage m_page`

- `ConstructLandPageProp m_prop`

- `ConstructLandPageModel m_fallbackModel`


## Properties

- `PlayerSandboxV2 playerSandboxV2`

- `ConstructLandPageModel model`


## Methods

- `PlayerSandboxV2 get_playerSandboxV2()`

- `ConstructLandPageModel get_model()`

- `Void Awake()`

- `Void OnDestroy()`

- `Void OnGameReady(Object)`

- `Void Update()`

- `Void AttachSceneBinder(ConstructLandPage, ConstructLandPageProp, ConstructPageMsg)`

- `Void AttachSceneView(IConstructSceneView)`

- `Void DetachSceneView(IConstructSceneView)`

- `Void UpdateConstructDetail()`

- `Void Trigger(EventFromScene)`

- `Void NotifyPage()`

- `Void ShowSandboxTextToast(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class ConstructLandPageBinder : DataBinder`1
{
	private static ConstructLandPageBinder <instance>k__BackingField; // 0x0
	private Boolean m_isReady; // 0x20
	private EventPool`1 m_eventPool; // 0x28
	private ConstructPageMsg m_pageMsg; // 0x30
	private ConstructLandPage m_page; // 0x38
	private ConstructLandPageProp m_prop; // 0x40
	private ConstructLandPageModel m_fallbackModel; // 0x48
	private List`1 m_views; // 0x50
	private static DelegateBridge __Hotfix0_get_instance; // 0x8
	private static DelegateBridge __Hotfix0_set_instance; // 0x10
	private static DelegateBridge __Hotfix0_get_playerSandboxV2; // 0x18
	private static DelegateBridge __Hotfix0_get_isReady; // 0x20
	private static DelegateBridge __Hotfix0_get_eventPool; // 0x28
	private static DelegateBridge __Hotfix0_get_model; // 0x30
	private static DelegateBridge __Hotfix0_Awake; // 0x38
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x40
	private static DelegateBridge __Hotfix0_OnGameReady; // 0x48
	private static DelegateBridge __Hotfix0_Update; // 0x50
	private static DelegateBridge __Hotfix0_AttachSceneBinder; // 0x58
	private static DelegateBridge __Hotfix0_AttachSceneView; // 0x60
	private static DelegateBridge __Hotfix0_DetachSceneView; // 0x68
	private static DelegateBridge __Hotfix0_UpdateConstructDetail; // 0x70
	private static DelegateBridge __Hotfix0_Trigger; // 0x78
	private static DelegateBridge __Hotfix0_NotifyPage; // 0x80
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x88
	private static DelegateBridge __Hotfix0_ShowSandboxTextToast; // 0x90
	private static DelegateBridge _c__Hotfix0_ctor; // 0x98

	public static ConstructLandPageBinder instance { get; set; }
	public PlayerSandboxV2 playerSandboxV2 { get; }
	public static Boolean isReady { get; }
	public EventPool`1 eventPool { get; }
	public ConstructLandPageModel model { get; }

	// RVA: 0x3fa5704 VA: 0x75965bd704
	public static ConstructLandPageBinder get_instance() { }
	// RVA: 0x3fa5764 VA: 0x75965bd764
	private static Void set_instance(ConstructLandPageBinder value) { }
	// RVA: 0x3fa57d8 VA: 0x75965bd7d8
	public PlayerSandboxV2 get_playerSandboxV2() { }
	// RVA: 0x3fa58fc VA: 0x75965bd8fc
	public static Boolean get_isReady() { }
	// RVA: 0x3fa59bc VA: 0x75965bd9bc
	public EventPool`1 get_eventPool() { }
	// RVA: 0x3fa5a24 VA: 0x75965bda24
	public ConstructLandPageModel get_model() { }
	// RVA: 0x3fa5ac4 VA: 0x75965bdac4
	private Void Awake() { }
	// RVA: 0x3fa5bbc VA: 0x75965bdbbc
	private Void OnDestroy() { }
	// RVA: 0x3fa561c VA: 0x75965bd61c
	public Void OnGameReady(Object arg) { }
	// RVA: 0x3fa5c20 VA: 0x75965bdc20
	private Void Update() { }
	// RVA: 0x3fa5e4c VA: 0x75965bde4c
	public Void AttachSceneBinder(ConstructLandPage page, ConstructLandPageProp prop, ConstructPageMsg pageMsg) { }
	// RVA: 0x3fa5f60 VA: 0x75965bdf60
	public Void AttachSceneView(IConstructSceneView view) { }
	// RVA: 0x3fa6098 VA: 0x75965be098
	public Void DetachSceneView(IConstructSceneView view) { }
	// RVA: 0x3fa6138 VA: 0x75965be138
	public Void UpdateConstructDetail() { }
	// RVA: 0x3fa6260 VA: 0x75965be260
	public Void Trigger(EventFromScene signal) { }
	// RVA: 0x3fa5b34 VA: 0x75965bdb34
	public Void NotifyPage() { }
	// RVA: 0x3fa63c0 VA: 0x75965be3c0
	public override Void OnValueChanged(ConstructLandPageProp property) { }
	// RVA: 0x3fa65a0 VA: 0x75965be5a0
	public Void ShowSandboxTextToast(String msg) { }
	// RVA: 0x3fa6654 VA: 0x75965be654
	public Void .ctor() { }
}
```