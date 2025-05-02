# UITouchZoom

**Namespace:** `Torappu.UI`


## Fields

- `Int32 _pixelsPerScale`

- `Single _minScale`

- `Single _maxScale`

- `Single _deltaScale`

- `Single m_scale`

- `Boolean m_dirtyLock`

- `Boolean m_isStarted`

- `Single m_minScale`

- `Single m_maxScale`

- `Boolean m_isInited`

- `Boolean m_zoomingLastFrame`

- `Single m_distanceLastFrame`

- `Single m_scaleLastFrame`


## Properties

- `Single scale`

- `Boolean dirtyLock`


## Methods

- `Void _InitIfNot()`

- `Single get_scale()`

- `Void set_scale(Single)`

- `Void set_dirtyLock(Boolean)`

- `Void set_onScaleChanged(Action`1)`

- `Void set_onScaleStart(Action`1)`

- `Void set_onScaleEnd(Action`1)`

- `Void Start()`

- `Void OnEnable()`

- `Void OnDisable()`

- `Void UpdateTime(Single)`

- `Void SetScaleRange(Single, Single)`

- `Single ClampScale(Single)`

- `Void _Resume()`

- `Boolean _UpdateZoomDistance()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UITouchZoom : MonoBehaviour, ITimeWatcher, IHotfixable
{
	private Int32 _pixelsPerScale; // 0x18
	private Single _minScale; // 0x1c
	private Single _maxScale; // 0x20
	private Single _deltaScale; // 0x24
	private Action`1 m_onScaleChanged; // 0x28
	private Action`1 m_onScaleStart; // 0x30
	private Action`1 m_onScaleEnd; // 0x38
	private Single m_scale; // 0x40
	private Boolean m_dirtyLock; // 0x44
	private Boolean m_isStarted; // 0x45
	private Single m_minScale; // 0x48
	private Single m_maxScale; // 0x4c
	private Boolean m_isInited; // 0x50
	private Boolean m_zoomingLastFrame; // 0x51
	private Single m_distanceLastFrame; // 0x54
	private Single m_scaleLastFrame; // 0x58
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_get_scale; // 0x8
	private static DelegateBridge __Hotfix0_set_scale; // 0x10
	private static DelegateBridge __Hotfix0_set_dirtyLock; // 0x18
	private static DelegateBridge __Hotfix0_set_onScaleChanged; // 0x20
	private static DelegateBridge __Hotfix0_set_onScaleStart; // 0x28
	private static DelegateBridge __Hotfix0_set_onScaleEnd; // 0x30
	private static DelegateBridge __Hotfix0_Start; // 0x38
	private static DelegateBridge __Hotfix0_OnEnable; // 0x40
	private static DelegateBridge __Hotfix0_OnDisable; // 0x48
	private static DelegateBridge __Hotfix0_UpdateTime; // 0x50
	private static DelegateBridge __Hotfix0_SetScaleRange; // 0x58
	private static DelegateBridge __Hotfix0_ClampScale; // 0x60
	private static DelegateBridge __Hotfix0__Resume; // 0x68
	private static DelegateBridge __Hotfix0__UpdateZoomDistance; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	public Single scale { get; set; }
	public Boolean dirtyLock { set; }
	public Action`1 onScaleChanged { set; }
	public Action`1 onScaleStart { set; }
	public Action`1 onScaleEnd { set; }

	// RVA: 0x2258610 VA: 0x7594870610
	private Void _InitIfNot() { }
	// RVA: 0x225868c VA: 0x759487068c
	public Single get_scale() { }
	// RVA: 0x22586f4 VA: 0x75948706f4
	public Void set_scale(Single value) { }
	// RVA: 0x2258774 VA: 0x7594870774
	public Void set_dirtyLock(Boolean value) { }
	// RVA: 0x22587f4 VA: 0x75948707f4
	public Void set_onScaleChanged(Action`1 value) { }
	// RVA: 0x2258878 VA: 0x7594870878
	public Void set_onScaleStart(Action`1 value) { }
	// RVA: 0x22588fc VA: 0x75948708fc
	public Void set_onScaleEnd(Action`1 value) { }
	// RVA: 0x2258980 VA: 0x7594870980
	private Void Start() { }
	// RVA: 0x2258a70 VA: 0x7594870a70
	protected Void OnEnable() { }
	// RVA: 0x2258af4 VA: 0x7594870af4
	protected Void OnDisable() { }
	// RVA: 0x2258b64 VA: 0x7594870b64
	public Void UpdateTime(Single deltaTime) { }
	// RVA: 0x2258e34 VA: 0x7594870e34
	public Void SetScaleRange(Single minScale, Single maxScale) { }
	// RVA: 0x2258ec0 VA: 0x7594870ec0
	public Single ClampScale(Single scale) { }
	// RVA: 0x22589fc VA: 0x75948709fc
	private Void _Resume() { }
	// RVA: 0x2258cbc VA: 0x7594870cbc
	private Boolean _UpdateZoomDistance() { }
	// RVA: 0x2258f58 VA: 0x7594870f58
	public Void .ctor() { }
}
```