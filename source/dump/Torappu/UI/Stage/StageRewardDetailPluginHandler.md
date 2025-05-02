# StageRewardDetailPluginHandler

**Namespace:** `Torappu.UI.Stage`


## Fields

- `RectTransform m_pluginContainer`

- `String m_cacheActId`

- `StageData m_stageData`

- `StagePreviewActPlugin m_plugin`

- `StageRewardDetailPluginView m_pluginView`


## Properties

- `Boolean hasValidPlugin`


## Methods

- `Boolean get_hasValidPlugin()`

- `Boolean TryGetBgTint(out)`

- `Void Init(StageData, ILoadAsset, RectTransform)`

- `Void _ReleasePluginView()`

- `Void RenderRewardPlugin(Boolean, Boolean)`

- `Void ForceRebuildLayout()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageRewardDetailPluginHandler : MonoBehaviour, IHotfixable
{
	private RectTransform m_pluginContainer; // 0x18
	private String m_cacheActId; // 0x20
	private StageData m_stageData; // 0x28
	private StagePreviewActPlugin m_plugin; // 0x30
	private StageRewardDetailPluginView m_pluginView; // 0x38
	private static DelegateBridge __Hotfix0_get_hasValidPlugin; // 0x0
	private static DelegateBridge __Hotfix0_TryGetBgTint; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge __Hotfix0__ReleasePluginView; // 0x18
	private static DelegateBridge __Hotfix0_RenderRewardPlugin; // 0x20
	private static DelegateBridge __Hotfix0_ForceRebuildLayout; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Boolean hasValidPlugin { get; }

	// RVA: 0x2f9b258 VA: 0x75955b3258
	public Boolean get_hasValidPlugin() { }
	// RVA: 0x2f9b310 VA: 0x75955b3310
	public Boolean TryGetBgTint(out Color bgTint) { }
	// RVA: 0x2f9b3d8 VA: 0x75955b33d8
	public Void Init(StageData stageData, ILoadAsset assetLoader, RectTransform pluginContainer) { }
	// RVA: 0x2f9b6fc VA: 0x75955b36fc
	private Void _ReleasePluginView() { }
	// RVA: 0x2f9b824 VA: 0x75955b3824
	public Void RenderRewardPlugin(Boolean getFlag, Boolean completeFlag) { }
	// RVA: 0x2f9b9f8 VA: 0x75955b39f8
	public Void ForceRebuildLayout() { }
	// RVA: 0x2f9bae4 VA: 0x75955b3ae4
	public Void .ctor() { }
}
```