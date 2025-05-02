# SandboxV2DungeonNodeStagePreviewView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Image _stageImage`

- `RectTransform _stageRect`

- `Vector2 _maxSize`

- `Single _frameWidth`

- `String m_cachedTopicId`

- `String m_cachedStageId`

- `ILoadAsset <assetLoader>k__BackingField`

- `Action <backEvent>k__BackingField`


## Properties

- `ILoadAsset assetLoader`

- `Action backEvent`


## Methods

- `ILoadAsset get_assetLoader()`

- `Void set_assetLoader(ILoadAsset)`

- `Action get_backEvent()`

- `Void set_backEvent(Action)`

- `Void OnBackEvent()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonNodeStagePreviewView : DataBinder`1
{
	private Image _stageImage; // 0x20
	private RectTransform _stageRect; // 0x28
	private Vector2 _maxSize; // 0x30
	private Single _frameWidth; // 0x38
	private String m_cachedTopicId; // 0x40
	private String m_cachedStageId; // 0x48
	private ILoadAsset <assetLoader>k__BackingField; // 0x50
	private Action <backEvent>k__BackingField; // 0x58
	private static DelegateBridge __Hotfix0_get_assetLoader; // 0x0
	private static DelegateBridge __Hotfix0_set_assetLoader; // 0x8
	private static DelegateBridge __Hotfix0_get_backEvent; // 0x10
	private static DelegateBridge __Hotfix0_set_backEvent; // 0x18
	private static DelegateBridge __Hotfix0_OnBackEvent; // 0x20
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x28
	private static DelegateBridge __Hotfix0__FitSizeRetainRatio; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	private ILoadAsset assetLoader { get; set; }
	private Action backEvent { get; set; }

	// RVA: 0x256ad5c VA: 0x7594b82d5c
	private ILoadAsset get_assetLoader() { }
	// RVA: 0x256adc4 VA: 0x7594b82dc4
	public Void set_assetLoader(ILoadAsset value) { }
	// RVA: 0x256ae48 VA: 0x7594b82e48
	private Action get_backEvent() { }
	// RVA: 0x256aeb0 VA: 0x7594b82eb0
	public Void set_backEvent(Action value) { }
	// RVA: 0x256af34 VA: 0x7594b82f34
	public Void OnBackEvent() { }
	// RVA: 0x256afd0 VA: 0x7594b82fd0
	public override Void OnValueChanged(SandboxV2DungeonNodeStagePreviewProperty property) { }
	// RVA: 0x256b1d4 VA: 0x7594b831d4
	private static Vector2 _FitSizeRetainRatio(Vector2 raw, Vector2 max) { }
	// RVA: 0x256b2ac VA: 0x7594b832ac
	public Void .ctor() { }
}
```