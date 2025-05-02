# ActMultiV3TrainingRoomView

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `RectTransform _bottomBarHolder`

- `SimpleLayoutContent _layoutMode`

- `PageCameraRenderTextureHolder _renderTextureHolder`

- `RectTransform _billboardPrefabHolder`

- `Boolean m_inited`

- `ActMultiV3CommonBottomBar m_bottomBar`

- `UIStateFinder m_stateFinder`

- `ActMultiV3TrainingRoomViewModel m_cachedViewModel`

- `Adapter m_adapter`

- `Tween m_modeShowTween`

- `ActMultiV3MapModeType m_cachedSelectedModeType`


## Methods

- `Void _InitIfNot()`

- `Void _EnsureBillboardView(String, ILoadAsset)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3TrainingRoomView : DataBinder`1
{
	private RectTransform _bottomBarHolder; // 0x20
	private SimpleLayoutContent _layoutMode; // 0x28
	private PageCameraRenderTextureHolder _renderTextureHolder; // 0x30
	private UIMeshImage[] _billboardMeshImageList; // 0x38
	private RectTransform _billboardPrefabHolder; // 0x40
	private Boolean m_inited; // 0x48
	private ActMultiV3CommonBottomBar m_bottomBar; // 0x50
	private UIStateFinder m_stateFinder; // 0x58
	private ActMultiV3TrainingRoomViewModel m_cachedViewModel; // 0x68
	private Adapter m_adapter; // 0x70
	private ListDict`2 m_billboardViews; // 0x78
	private Tween m_modeShowTween; // 0x80
	private ActMultiV3MapModeType m_cachedSelectedModeType; // 0x88
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0__EnsureBillboardView; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3154404 VA: 0x759576c404
	private Void _InitIfNot() { }
	// RVA: 0x31546bc VA: 0x759576c6bc
	private Void _EnsureBillboardView(String actId, ILoadAsset assetLoader) { }
	// RVA: 0x3154904 VA: 0x759576c904
	public override Void OnValueChanged(ActMultiV3TrainingRoomProperty property) { }
	// RVA: 0x3154bf4 VA: 0x759576cbf4
	public Void .ctor() { }
}
```