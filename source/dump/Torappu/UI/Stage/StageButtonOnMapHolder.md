# StageButtonOnMapHolder

**Namespace:** `Torappu.UI.Stage`


## Fields

- `String _stageId`

- `StageButtonOnMap _prefab`

- `RectTransform _container`

- `StageButtonOnMap m_button`

- `Int32 m_appliedPrefabSign`


## Properties

- `String stageId`

- `RectTransform buttonContainer`

- `StageButtonOnMap button`


## Methods

- `String get_stageId()`

- `RectTransform get_buttonContainer()`

- `Void SetButtonContainerActive(Boolean)`

- `Void ApplyPatch(StageButtonPatch)`

- `Void SetupIfNeeded(StageButtonOnMap)`

- `Void Clear()`

- `StageButtonOnMap get_button()`

- `TComp SingleComponent()`

- `Void ZoneMapOnlyOnRenderStage(StageViewModel)`

- `Void _CollectPlugins()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageButtonOnMapHolder : MonoBehaviour, IHotfixable
{
	private String _stageId; // 0x18
	private StageButtonOnMap _prefab; // 0x20
	private RectTransform _container; // 0x28
	private ListSet`1 m_msgReceivers; // 0x30
	private Dictionary`2 m_singleComps; // 0x38
	private StageButtonOnMap m_button; // 0x40
	private Int32 m_appliedPrefabSign; // 0x48
	private static DelegateBridge __Hotfix0_get_stageId; // 0x0
	private static DelegateBridge __Hotfix0_get_buttonContainer; // 0x8
	private static DelegateBridge __Hotfix0_SetButtonContainerActive; // 0x10
	private static DelegateBridge __Hotfix0_ApplyPatch; // 0x18
	private static DelegateBridge __Hotfix0_SetupIfNeeded; // 0x20
	private static DelegateBridge __Hotfix0_Clear; // 0x28
	private static DelegateBridge __Hotfix0_get_button; // 0x30
	private static DelegateBridge __Hotfix0_SingleComponent; // 0x38
	private static DelegateBridge __Hotfix0_ZoneMapOnlyOnRenderStage; // 0x40
	private static DelegateBridge __Hotfix0__CollectPlugins; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public String stageId { get; }
	protected RectTransform buttonContainer { get; }
	public StageButtonOnMap button { get; }

	// RVA: 0x2fa2cf8 VA: 0x75955bacf8
	public String get_stageId() { }
	// RVA: 0x2fa2d60 VA: 0x75955bad60
	protected RectTransform get_buttonContainer() { }
	// RVA: 0x2fa2e18 VA: 0x75955bae18
	public Void SetButtonContainerActive(Boolean isActive) { }
	// RVA: 0x2fa2ef8 VA: 0x75955baef8
	public Void ApplyPatch(StageButtonPatch patch) { }
	// RVA: 0x2fa2fb4 VA: 0x75955bafb4
	public Void SetupIfNeeded(StageButtonOnMap defaultPrefab) { }
	// RVA: 0x2fa33e4 VA: 0x75955bb3e4
	public Void Clear() { }
	// RVA: 0x2fa10b8 VA: 0x75955b90b8
	public StageButtonOnMap get_button() { }
	// RVA: 0x VA: 0x0
	public TComp SingleComponent() { }
	// RVA: 0x2fa3494 VA: 0x75955bb494
	public Void ZoneMapOnlyOnRenderStage(StageViewModel model) { }
	// RVA: 0x2fa3240 VA: 0x75955bb240
	private Void _CollectPlugins() { }
	// RVA: 0x2fa36a4 VA: 0x75955bb6a4
	public Void .ctor() { }
}
```