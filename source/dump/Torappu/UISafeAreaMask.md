# UISafeAreaMask

**Namespace:** `Torappu`


## Fields

- `RectTransform _panelLeft`

- `RectTransform _panelRight`

- `CanvasScaler _scaler`

- `Canvas _canvas`

- `Camera _camera`

- `Boolean m_isShown`


## Methods

- `Void Start()`

- `Void Update()`

- `Void OnSafeRectUpdated(SafeRect)`

- `Void _ShowIfNeeded()`

- `Void _UpdateLayout()`

- `Void _UpdateDisplayStatus()`

- `Void _EnableCoreComponents(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class UISafeAreaMask : SingletonMonoBehaviour`1, ISingletonNotAutoCreate, ISafeAreaListener
{
	private RectTransform _panelLeft; // 0x18
	private RectTransform _panelRight; // 0x20
	private CanvasScaler _scaler; // 0x28
	private Canvas _canvas; // 0x30
	private Camera _camera; // 0x38
	private Boolean m_isShown; // 0x40
	private ListSet`1 m_hideCondSet; // 0x48
	private static DelegateBridge __Hotfix0_Start; // 0x0
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x8
	private static DelegateBridge __Hotfix0_Update; // 0x10
	private static DelegateBridge __Hotfix0_OnSafeRectUpdated; // 0x18
	private static DelegateBridge __Hotfix0_Display; // 0x20
	private static DelegateBridge __Hotfix0_ShowIfNeeded; // 0x28
	private static DelegateBridge __Hotfix0__ShowIfNeeded; // 0x30
	private static DelegateBridge __Hotfix0__UpdateLayout; // 0x38
	private static DelegateBridge __Hotfix0__UpdateDisplayStatus; // 0x40
	private static DelegateBridge __Hotfix0__EnableCoreComponents; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x2f4100c VA: 0x759555900c
	private Void Start() { }
	// RVA: 0x2f410a4 VA: 0x75955590a4
	protected override Void OnDestroy() { }
	// RVA: 0x2f41150 VA: 0x7595559150
	private Void Update() { }
	// RVA: 0x2f41204 VA: 0x7595559204
	public Void OnSafeRectUpdated(SafeRect rect) { }
	// RVA: 0x2f413ec VA: 0x75955593ec
	public static Void Display(SafeAreaMaskCond condition, Boolean isShow) { }
	// RVA: 0x2f415f8 VA: 0x75955595f8
	public static Void ShowIfNeeded() { }
	// RVA: 0x2f416c8 VA: 0x75955596c8
	private Void _ShowIfNeeded() { }
	// RVA: 0x2f41288 VA: 0x7595559288
	private Void _UpdateLayout() { }
	// RVA: 0x2f4152c VA: 0x759555952c
	private Void _UpdateDisplayStatus() { }
	// RVA: 0x2f4174c VA: 0x759555974c
	private Void _EnableCoreComponents(Boolean isEnable) { }
	// RVA: 0x2f417f0 VA: 0x75955597f0
	public Void .ctor() { }
}
```