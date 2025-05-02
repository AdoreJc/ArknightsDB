# UICanvasScalerHelper

**Namespace:** `Torappu.UI`


## Fields

- `CanvasScaler m_scaler`

- `RectTransform m_rectTrans`

- `Boolean <isInited>k__BackingField`


## Properties

- `Boolean isInited`

- `CanvasScaler scaler`

- `RectTransform rectTrans`

- `Vector2 size`


## Methods

- `Boolean get_isInited()`

- `Void set_isInited(Boolean)`

- `Void add_onScalerChanged(Action`1)`

- `Void remove_onScalerChanged(Action`1)`

- `CanvasScaler get_scaler()`

- `RectTransform get_rectTrans()`

- `Vector2 get_size()`

- `Void OnSafeRectUpdated(SafeRect)`

- `Void Start()`

- `Void OnDestroy()`

- `Void _UpdateMatchMethod()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICanvasScalerHelper : MonoBehaviour, ISafeAreaListener, IHotfixable
{
	private CanvasScaler m_scaler; // 0x18
	private RectTransform m_rectTrans; // 0x20
	private Action`1 m_onScalerChanged; // 0x28
	private Boolean <isInited>k__BackingField; // 0x30
	private static DelegateBridge __Hotfix0_get_isInited; // 0x0
	private static DelegateBridge __Hotfix0_set_isInited; // 0x8
	private static DelegateBridge __Hotfix0_add_onScalerChanged; // 0x10
	private static DelegateBridge __Hotfix0_remove_onScalerChanged; // 0x18
	private static DelegateBridge __Hotfix0_get_scaler; // 0x20
	private static DelegateBridge __Hotfix0_get_rectTrans; // 0x28
	private static DelegateBridge __Hotfix0_get_size; // 0x30
	private static DelegateBridge __Hotfix0_OnSafeRectUpdated; // 0x38
	private static DelegateBridge __Hotfix0_Start; // 0x40
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x48
	private static DelegateBridge __Hotfix0__UpdateMatchMethod; // 0x50
	private static DelegateBridge __Hotfix0_UpdateScalerFitMode; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public Boolean isInited { get; set; }
	public CanvasScaler scaler { get; }
	public RectTransform rectTrans { get; }
	public Vector2 size { get; }

	// RVA: 0x21cbfbc VA: 0x75947e3fbc
	public Boolean get_isInited() { }
	// RVA: 0x21cc024 VA: 0x75947e4024
	private Void set_isInited(Boolean value) { }
	// RVA: 0x21cc0a4 VA: 0x75947e40a4
	public Void add_onScalerChanged(Action`1 value) { }
	// RVA: 0x21cc358 VA: 0x75947e4358
	public Void remove_onScalerChanged(Action`1 value) { }
	// RVA: 0x21cc280 VA: 0x75947e4280
	public CanvasScaler get_scaler() { }
	// RVA: 0x21cc440 VA: 0x75947e4440
	public RectTransform get_rectTrans() { }
	// RVA: 0x21cc504 VA: 0x75947e4504
	public Vector2 get_size() { }
	// RVA: 0x21cc59c VA: 0x75947e459c
	public Void OnSafeRectUpdated(SafeRect rect) { }
	// RVA: 0x21cc8b8 VA: 0x75947e48b8
	private Void Start() { }
	// RVA: 0x21cc954 VA: 0x75947e4954
	private Void OnDestroy() { }
	// RVA: 0x21cc620 VA: 0x75947e4620
	private Void _UpdateMatchMethod() { }
	// RVA: 0x21cc9e4 VA: 0x75947e49e4
	public static Void UpdateScalerFitMode(CanvasScaler scaler) { }
	// RVA: 0x21ccac8 VA: 0x75947e4ac8
	public Void .ctor() { }
}
```