# MapScaleController

**Namespace:** ` `


## Fields

- `RL02OuterBuffController m_closure`

- `Tween m_initTween`

- `Single m_lastMinScale`

- `Boolean m_hasPendingInitTween`


## Methods

- `Void StartInitLayoutTween()`

- `Void Dispose()`

- `Void EnableTouchZoom(Boolean)`

- `Void _DisposeInitTween()`

- `Void _TryStartInitLayoutTween()`

- `Void BindTouchZoom(Action`1, Action`2, Action`1)`

- `Void BindScroll(Action`1)`

- `Void OnMapLayoutChanged(Vector2, Vector2)`

- `Void OnMapScaleChanged(Single)`

- `Void OnMapTouchZoomStateChanged(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class MapScaleController : IBindings, IHotfixable, IDisposable
{
	public const Single MAX_SCALE; // 0x0
	private const Single INIT_SCALE_BIAS; // 0x0
	private const Single INIT_SCALE_DUR; // 0x0
	private Action`1 m_scaleMethod; // 0x10
	private Action`2 m_scaleRangeMethod; // 0x18
	private Action`1 m_enableTouchMethod; // 0x20
	private Action`1 m_normalizedPosMethod; // 0x28
	private RL02OuterBuffController m_closure; // 0x30
	private Tween m_initTween; // 0x38
	private Single m_lastMinScale; // 0x40
	private Boolean m_hasPendingInitTween; // 0x44
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_StartInitLayoutTween; // 0x8
	private static DelegateBridge __Hotfix0_Dispose; // 0x10
	private static DelegateBridge __Hotfix0_EnableTouchZoom; // 0x18
	private static DelegateBridge __Hotfix0__DisposeInitTween; // 0x20
	private static DelegateBridge __Hotfix0__TryStartInitLayoutTween; // 0x28
	private static DelegateBridge __Hotfix0_BindTouchZoom; // 0x30
	private static DelegateBridge __Hotfix0_BindScroll; // 0x38
	private static DelegateBridge __Hotfix0_OnMapLayoutChanged; // 0x40
	private static DelegateBridge __Hotfix0_OnMapScaleChanged; // 0x48
	private static DelegateBridge __Hotfix0_OnMapTouchZoomStateChanged; // 0x50


	// RVA: 0x26bac48 VA: 0x7594cd2c48
	public Void .ctor(RL02OuterBuffController closure) { }
	// RVA: 0x26bcaa4 VA: 0x7594cd4aa4
	public Void StartInitLayoutTween() { }
	// RVA: 0x26bcd50 VA: 0x7594cd4d50
	public Void Dispose() { }
	// RVA: 0x26bd698 VA: 0x7594cd5698
	public Void EnableTouchZoom(Boolean enabled) { }
	// RVA: 0x26bdb34 VA: 0x7594cd5b34
	private Void _DisposeInitTween() { }
	// RVA: 0x26bd920 VA: 0x7594cd5920
	private Void _TryStartInitLayoutTween() { }
	// RVA: 0x26bdbdc VA: 0x7594cd5bdc
	public Void BindTouchZoom(Action`1 scaleMethod, Action`2 scaleRangeMethod, Action`1 enableTouchMethod) { }
	// RVA: 0x26bdc9c VA: 0x7594cd5c9c
	public Void BindScroll(Action`1 normalizedPosMethod) { }
	// RVA: 0x26bdd20 VA: 0x7594cd5d20
	public Void OnMapLayoutChanged(Vector2 viewportSize, Vector2 contentSize) { }
	// RVA: 0x26bde6c VA: 0x7594cd5e6c
	public Void OnMapScaleChanged(Single scale) { }
	// RVA: 0x26bdf0c VA: 0x7594cd5f0c
	public Void OnMapTouchZoomStateChanged(Boolean isZooming) { }
}
```