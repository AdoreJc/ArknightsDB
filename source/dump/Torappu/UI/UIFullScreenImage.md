# UIFullScreenImage

**Namespace:** `Torappu.UI`


## Fields

- `UICanvasScalerHelper _targetScaler`

- `Image m_image`

- `UICanvasScalerHelper m_scaler`

- `Sprite m_rtSprite`


## Properties

- `Image image`

- `UICanvasScalerHelper scaler`


## Methods

- `Void SetRTSpriteToImage(Sprite)`

- `Image get_image()`

- `UICanvasScalerHelper get_scaler()`

- `Void OnSafeRectUpdated(SafeRect)`

- `Void Start()`

- `Void OnDestroy()`

- `Void UpdateSize()`

- `Void _OnScalerChanged(CanvasScaler)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIFullScreenImage : MonoBehaviour, IHotfixable
{
	private UICanvasScalerHelper _targetScaler; // 0x18
	private Image m_image; // 0x20
	private UICanvasScalerHelper m_scaler; // 0x28
	private Sprite m_rtSprite; // 0x30
	private static DelegateBridge __Hotfix0_SetRTSpriteToImage; // 0x0
	private static DelegateBridge __Hotfix0_get_image; // 0x8
	private static DelegateBridge __Hotfix0_get_scaler; // 0x10
	private static DelegateBridge __Hotfix0_OnSafeRectUpdated; // 0x18
	private static DelegateBridge __Hotfix0_Start; // 0x20
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x28
	private static DelegateBridge __Hotfix0_UpdateSize; // 0x30
	private static DelegateBridge __Hotfix0__OnScalerChanged; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public Image image { get; }
	private UICanvasScalerHelper scaler { get; }

	// RVA: 0x21d5748 VA: 0x75947ed748
	public Void SetRTSpriteToImage(Sprite rtSprite) { }
	// RVA: 0x21d58ec VA: 0x75947ed8ec
	public Image get_image() { }
	// RVA: 0x21d5b54 VA: 0x75947edb54
	private UICanvasScalerHelper get_scaler() { }
	// RVA: 0x21d5d1c VA: 0x75947edd1c
	public Void OnSafeRectUpdated(SafeRect safeRect) { }
	// RVA: 0x21d5ea0 VA: 0x75947edea0
	private Void Start() { }
	// RVA: 0x21d5fc4 VA: 0x75947edfc4
	private Void OnDestroy() { }
	// RVA: 0x21d5da0 VA: 0x75947edda0
	public Void UpdateSize() { }
	// RVA: 0x21d6164 VA: 0x75947ee164
	private Void _OnScalerChanged(CanvasScaler canvasScaler) { }
	// RVA: 0x21d62a0 VA: 0x75947ee2a0
	public Void .ctor() { }
}
```