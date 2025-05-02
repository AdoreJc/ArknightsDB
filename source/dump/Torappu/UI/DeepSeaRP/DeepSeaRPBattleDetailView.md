# DeepSeaRPBattleDetailView

**Namespace:** `Torappu.UI.DeepSeaRP`


## Fields

- `Image _imgMapPreview`

- `CanvasGroup _selfCanvas`

- `Text _mapDesc`

- `Sprite m_stagePreviewMap`

- `DirectAssetLoader m_stagePreviewMapLoader`

- `DetailViewSwitchTween m_switchTween`

- `Boolean m_isInited`


## Methods

- `Void OnEnter()`

- `Void _LoadMapPreview(String)`

- `Void _UnloadStagePreviewMap()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.DeepSeaRP
public class DeepSeaRPBattleDetailView : DataBinder`1, IHotfixable
{
	private Image _imgMapPreview; // 0x20
	private CanvasGroup _selfCanvas; // 0x28
	private Text _mapDesc; // 0x30
	private Sprite m_stagePreviewMap; // 0x38
	private DirectAssetLoader m_stagePreviewMapLoader; // 0x40
	private DetailViewSwitchTween m_switchTween; // 0x48
	private Boolean m_isInited; // 0x50
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__LoadMapPreview; // 0x10
	private static DelegateBridge __Hotfix0__UnloadStagePreviewMap; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x29bbbf4 VA: 0x7594fd3bf4
	public Void OnEnter() { }
	// RVA: 0x29bbd44 VA: 0x7594fd3d44
	public override Void OnValueChanged(DeepSeaRPBattleNodeDetailProperty property) { }
	// RVA: 0x29bbe60 VA: 0x7594fd3e60
	private Void _LoadMapPreview(String stageId) { }
	// RVA: 0x29bbf34 VA: 0x7594fd3f34
	private Void _UnloadStagePreviewMap() { }
	// RVA: 0x29bbc74 VA: 0x7594fd3c74
	private Void _InitIfNot() { }
	// RVA: 0x29bc0b0 VA: 0x7594fd40b0
	public Void .ctor() { }
}
```