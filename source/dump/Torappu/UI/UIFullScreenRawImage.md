# UIFullScreenRawImage

**Namespace:** `Torappu.UI`


## Fields

- `UICanvasScalerHelper _targetScaler`

- `RawImage m_image`

- `UICanvasScalerHelper m_scaler`


## Properties

- `RawImage image`

- `UICanvasScalerHelper scaler`


## Methods

- `RawImage get_image()`

- `UICanvasScalerHelper get_scaler()`

- `Void Start()`

- `Void OnDestroy()`

- `Void _OnScalerChanged(CanvasScaler)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIFullScreenRawImage : MonoBehaviour
{
	private UICanvasScalerHelper _targetScaler; // 0x18
	private RawImage m_image; // 0x20
	private UICanvasScalerHelper m_scaler; // 0x28

	private RawImage image { get; }
	private UICanvasScalerHelper scaler { get; }

	// RVA: 0x21d6310 VA: 0x75947ee310
	private RawImage get_image() { }
	// RVA: 0x21d6474 VA: 0x75947ee474
	private UICanvasScalerHelper get_scaler() { }
	// RVA: 0x21d6600 VA: 0x75947ee600
	private Void Start() { }
	// RVA: 0x21d66ec VA: 0x75947ee6ec
	private Void OnDestroy() { }
	// RVA: 0x21d67d8 VA: 0x75947ee7d8
	private Void _OnScalerChanged(CanvasScaler canvasScaler) { }
	// RVA: 0x21d68d0 VA: 0x75947ee8d0
	public Void .ctor() { }
}
```