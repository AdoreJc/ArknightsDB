# StagePreviewActPluginHander

**Namespace:** `Torappu.UI.Stage`


## Fields

- `RectTransform _rewardPreviewPluginContainer`

- `RectTransform m_mapPreviewPluginContainer`

- `String m_cacheActId`

- `StagePreviewActPlugin m_plugin`

- `StageRewardPreviewPluginView m_rewardPreviewPlugin`

- `StageMapPreviewPluginView m_mapPreviewPlugin`


## Properties

- `Boolean overrideMapPreview`

- `Boolean overrideRewardPreview`

- `Boolean hasValidPlugin`


## Methods

- `Boolean get_overrideMapPreview()`

- `Boolean get_overrideRewardPreview()`

- `Boolean get_hasValidPlugin()`

- `Void Init(StageViewModel, ILoadAsset, RectTransform)`

- `Void UpdateRewardPreview(StageViewModel, Action)`

- `Void SetRewardPreviewVisible(Boolean)`

- `Void ShowMapPreview(StageData, ILoadAsset)`

- `Sprite LoadMapPreview(String, ILoadAsset)`

- `Void _ReleasePluginView()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StagePreviewActPluginHander : MonoBehaviour, IHotfixable
{
	private RectTransform _rewardPreviewPluginContainer; // 0x18
	private RectTransform m_mapPreviewPluginContainer; // 0x20
	private String m_cacheActId; // 0x28
	private StagePreviewActPlugin m_plugin; // 0x30
	private StageRewardPreviewPluginView m_rewardPreviewPlugin; // 0x38
	private StageMapPreviewPluginView m_mapPreviewPlugin; // 0x40
	private static DelegateBridge __Hotfix0_get_overrideMapPreview; // 0x0
	private static DelegateBridge __Hotfix0_get_overrideRewardPreview; // 0x8
	private static DelegateBridge __Hotfix0_get_hasValidPlugin; // 0x10
	private static DelegateBridge __Hotfix0_Init; // 0x18
	private static DelegateBridge __Hotfix0_UpdateRewardPreview; // 0x20
	private static DelegateBridge __Hotfix0_SetRewardPreviewVisible; // 0x28
	private static DelegateBridge __Hotfix0_ShowMapPreview; // 0x30
	private static DelegateBridge __Hotfix0_LoadMapPreview; // 0x38
	private static DelegateBridge __Hotfix0__ReleasePluginView; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public Boolean overrideMapPreview { get; }
	public Boolean overrideRewardPreview { get; }
	public Boolean hasValidPlugin { get; }

	// RVA: 0x2f98f60 VA: 0x75955b0f60
	public Boolean get_overrideMapPreview() { }
	// RVA: 0x2f990a4 VA: 0x75955b10a4
	public Boolean get_overrideRewardPreview() { }
	// RVA: 0x2f98fec VA: 0x75955b0fec
	public Boolean get_hasValidPlugin() { }
	// RVA: 0x2f99130 VA: 0x75955b1130
	public Void Init(StageViewModel stageModel, ILoadAsset assetLoader, RectTransform mapPreviewPluginContainer) { }
	// RVA: 0x2f995f0 VA: 0x75955b15f0
	public Void UpdateRewardPreview(StageViewModel selectedStage, Action onRewardClick) { }
	// RVA: 0x2f99838 VA: 0x75955b1838
	public Void SetRewardPreviewVisible(Boolean isCustom) { }
	// RVA: 0x2f99918 VA: 0x75955b1918
	public Void ShowMapPreview(StageData previewStageData, ILoadAsset assetLoader) { }
	// RVA: 0x2f99ae4 VA: 0x75955b1ae4
	public Sprite LoadMapPreview(String stageId, ILoadAsset assetLoader) { }
	// RVA: 0x2f99444 VA: 0x75955b1444
	private Void _ReleasePluginView() { }
	// RVA: 0x2f99be4 VA: 0x75955b1be4
	public Void .ctor() { }
}
```