# DIYCameraSwitchToggle

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `Graphic _ceilingSwitchIcon`

- `Graphic _wallSwitchIcon`

- `Graphic _floorSwitchIcon`

- `Graphic _generalSwitchIcon`

- `RectTransform _ceilingButton`

- `RectTransform _wallButton`

- `RectTransform _floorButton`

- `RectTransform _cameraPointer`

- `TwoStateToggle _toggle`

- `Button _toggleButton`

- `CanvasGroup _buttonsGroup`

- `Single _radiusMax`

- `Single _radiusMin`

- `CameraSwitchState m_cameraState`

- `Graphic m_currentFoldSwitchIcon`

- `DIYCameraSwitchTween m_cameraSwitchTween`

- `Boolean m_isInit`


## Methods

- `Void OnSwitchToggle(CameraSwitchState)`

- `Void _InitIfNot()`

- `Void _SetSwitchIconState(CameraSwitchState)`

- `Void _OnToggle(State)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYCameraSwitchToggle : MonoBehaviour, IHotfixable
{
	private Graphic _ceilingSwitchIcon; // 0x18
	private Graphic _wallSwitchIcon; // 0x20
	private Graphic _floorSwitchIcon; // 0x28
	private Graphic _generalSwitchIcon; // 0x30
	private RectTransform _ceilingButton; // 0x38
	private RectTransform _wallButton; // 0x40
	private RectTransform _floorButton; // 0x48
	private RectTransform _cameraPointer; // 0x50
	private TwoStateToggle _toggle; // 0x58
	private Button _toggleButton; // 0x60
	private CanvasGroup _buttonsGroup; // 0x68
	private Single _radiusMax; // 0x70
	private Single _radiusMin; // 0x74
	private CameraSwitchState m_cameraState; // 0x78
	private Graphic m_currentFoldSwitchIcon; // 0x80
	private DIYCameraSwitchTween m_cameraSwitchTween; // 0x88
	private Boolean m_isInit; // 0x90
	private const Single SQRT_2_DIV_2; // 0x0
	private const Single DURATION; // 0x0
	private const Single CEILING_ICON_ANGLE; // 0x0
	private const Single WALL_ICON_ANGLE; // 0x0
	private const Single FLOOR_ICON_ANGLE; // 0x0
	private static DelegateBridge __Hotfix0_OnSwitchToggle; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__SetSwitchIconState; // 0x10
	private static DelegateBridge __Hotfix0__OnToggle; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x3812d28 VA: 0x7595e2ad28
	public Void OnSwitchToggle(CameraSwitchState state) { }
	// RVA: 0x3812e90 VA: 0x7595e2ae90
	private Void _InitIfNot() { }
	// RVA: 0x3812f9c VA: 0x7595e2af9c
	private Void _SetSwitchIconState(CameraSwitchState state) { }
	// RVA: 0x381312c VA: 0x7595e2b12c
	private Void _OnToggle(State state) { }
	// RVA: 0x38131c8 VA: 0x7595e2b1c8
	public Void .ctor() { }
}
```