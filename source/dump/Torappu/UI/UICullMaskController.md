# UICullMaskController

**Namespace:** `Torappu.UI`


## Fields

- `RectTransform _panelLeft`

- `RectTransform _panelRight`

- `RectTransform _panelTop`

- `RectTransform _panelBottom`

- `RectTransform _panelCenter`

- `CanvasScaler _canvasScaler`

- `Boolean m_inited`


## Methods

- `Void Start()`

- `Void OnDestroy()`

- `Void OnSafeRectUpdated(SafeRect)`

- `Void OnEnable()`

- `Void _InitIfNot()`

- `Vector2 _CalcUniformScreenSize()`

- `Void _UpdateLayout()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICullMaskController : MonoBehaviour, ISafeAreaListener, IHotfixable
{
	private RectTransform _panelLeft; // 0x18
	private RectTransform _panelRight; // 0x20
	private RectTransform _panelTop; // 0x28
	private RectTransform _panelBottom; // 0x30
	private RectTransform _panelCenter; // 0x38
	private CanvasScaler _canvasScaler; // 0x40
	private Boolean m_inited; // 0x48
	private static DelegateBridge __Hotfix0_Start; // 0x0
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x8
	private static DelegateBridge __Hotfix0_OnSafeRectUpdated; // 0x10
	private static DelegateBridge __Hotfix0_OnEnable; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0__CalcUniformScreenSize; // 0x28
	private static DelegateBridge __Hotfix0__UpdateLayout; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x21ccb38 VA: 0x75947e4b38
	private Void Start() { }
	// RVA: 0x21ccc44 VA: 0x75947e4c44
	private Void OnDestroy() { }
	// RVA: 0x21cccd4 VA: 0x75947e4cd4
	public Void OnSafeRectUpdated(SafeRect rect) { }
	// RVA: 0x21ccf3c VA: 0x75947e4f3c
	private Void OnEnable() { }
	// RVA: 0x21ccba0 VA: 0x75947e4ba0
	private Void _InitIfNot() { }
	// RVA: 0x21ccfa4 VA: 0x75947e4fa4
	private Vector2 _CalcUniformScreenSize() { }
	// RVA: 0x21ccd58 VA: 0x75947e4d58
	private Void _UpdateLayout() { }
	// RVA: 0x21cd08c VA: 0x75947e508c
	public Void .ctor() { }
}
```