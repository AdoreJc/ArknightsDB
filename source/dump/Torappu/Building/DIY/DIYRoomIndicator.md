# DIYRoomIndicator

**Namespace:** `Torappu.Building.DIY`


## Fields

- `Text _coordinatorText`

- `String _coordinatorFormat`

- `Transform _opButtonRoot`

- `Transform _dragButtonRoot`

- `Single _positiveOffset`

- `Single _negativeOffset`

- `Single _horizontalOffset`

- `Single _edgeLengthWeight`

- `Single _edgeLengthBias`

- `Single _animInterval`

- `Color _toneColor`

- `Renderer _innerCubeRenderer`

- `Color _innerCubeColor`

- `Single _opButtonHorizontalThreshold`

- `Single _opButtonVerticalThreshold`

- `ISpaceOccupation m_currentOccupation`

- `FurnitureLocationType m_locationType`

- `Int32 m_prePosition0`

- `Int32 m_prePosition1`

- `Camera m_camera`

- `CameraState m_cameraState`

- `Boolean m_enableRotate`

- `Single m_buttonDisableAlpha`


## Properties

- `ISpaceOccupation currentOccupation`

- `FurnitureLocationType locationType`

- `Vector3 centerPosition`

- `Vector3 opButtonPosition`

- `Vector3 dragButtonPosition`

- `CameraStateType m_cameraType`


## Methods

- `ISpaceOccupation get_currentOccupation()`

- `FurnitureLocationType get_locationType()`

- `Vector3 get_centerPosition()`

- `Vector3 get_opButtonPosition()`

- `Vector3 get_dragButtonPosition()`

- `CameraStateType get_m_cameraType()`

- `Void Setup(ISpaceOccupation, FurnitureLocationType, Camera, CameraState, Boolean)`

- `Void UpdatePosition()`

- `Void _UpdatePosition(Boolean, Boolean)`

- `Void _UpdateButtonTransform()`

- `Void PlayDragedAnim()`

- `Void OnDestroy()`

- `Void StopDragedAnim()`

- `Void _UpdateMaterialColor(Color)`

- `Void _UpdateInnerCubeColor(Single)`

- `Void _ParseAllMaterial()`

- `Void _ClearMaterials()`

- `Void Update()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY
public class DIYRoomIndicator : MonoBehaviour, IHotfixable
{
	private Text _coordinatorText; // 0x18
	private String _coordinatorFormat; // 0x20
	private Transform _opButtonRoot; // 0x28
	private Renderer[] _opButtonRenderers; // 0x30
	private List`1 _rotateButtonRenderers; // 0x38
	private Transform _dragButtonRoot; // 0x40
	private Renderer[] _dragButtonRenderers; // 0x48
	private Single _positiveOffset; // 0x50
	private Single _negativeOffset; // 0x54
	private Single _horizontalOffset; // 0x58
	private Transform[] _frameObjects; // 0x60
	private Transform[] _frameEdgeObjects; // 0x68
	private Single _edgeLengthWeight; // 0x70
	private Single _edgeLengthBias; // 0x74
	private Single _animInterval; // 0x78
	private Color _toneColor; // 0x7c
	private Renderer _innerCubeRenderer; // 0x90
	private Color _innerCubeColor; // 0x98
	private Single _opButtonHorizontalThreshold; // 0xa8
	private Single _opButtonVerticalThreshold; // 0xac
	private ISpaceOccupation m_currentOccupation; // 0xb0
	private FurnitureLocationType m_locationType; // 0xb8
	private Int32 m_prePosition0; // 0xbc
	private Int32 m_prePosition1; // 0xc0
	private Camera m_camera; // 0xc8
	private CameraState m_cameraState; // 0xd0
	private List`1 m_colorMaterials; // 0xd8
	private List`1 m_DragedTween; // 0xe0
	private Boolean m_enableRotate; // 0xe8
	private Single m_buttonDisableAlpha; // 0xec
	private static DelegateBridge __Hotfix0_get_currentOccupation; // 0x0
	private static DelegateBridge __Hotfix0_get_locationType; // 0x8
	private static DelegateBridge __Hotfix0_get_centerPosition; // 0x10
	private static DelegateBridge __Hotfix0_get_opButtonPosition; // 0x18
	private static DelegateBridge __Hotfix0_get_dragButtonPosition; // 0x20
	private static DelegateBridge __Hotfix0_get_m_cameraType; // 0x28
	private static DelegateBridge __Hotfix0_Setup; // 0x30
	private static DelegateBridge __Hotfix0_UpdatePosition; // 0x38
	private static DelegateBridge __Hotfix0__UpdatePosition; // 0x40
	private static DelegateBridge __Hotfix0__UpdateButtonTransform; // 0x48
	private static DelegateBridge __Hotfix0_PlayDragedAnim; // 0x50
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x58
	private static DelegateBridge __Hotfix0_StopDragedAnim; // 0x60
	private static DelegateBridge __Hotfix0__UpdateMaterialColor; // 0x68
	private static DelegateBridge __Hotfix0__UpdateInnerCubeColor; // 0x70
	private static DelegateBridge __Hotfix0__ParseAllMaterial; // 0x78
	private static DelegateBridge __Hotfix0__ClearMaterials; // 0x80
	private static DelegateBridge __Hotfix0_Update; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90

	public ISpaceOccupation currentOccupation { get; }
	public FurnitureLocationType locationType { get; }
	private Vector3 centerPosition { get; }
	private Vector3 opButtonPosition { get; }
	private Vector3 dragButtonPosition { get; }
	private CameraStateType m_cameraType { get; }

	// RVA: 0x37e07b0 VA: 0x7595df87b0
	public ISpaceOccupation get_currentOccupation() { }
	// RVA: 0x37e0818 VA: 0x7595df8818
	public FurnitureLocationType get_locationType() { }
	// RVA: 0x37e0880 VA: 0x7595df8880
	private Vector3 get_centerPosition() { }
	// RVA: 0x37e14ac VA: 0x7595df94ac
	private Vector3 get_opButtonPosition() { }
	// RVA: 0x37e1534 VA: 0x7595df9534
	private Vector3 get_dragButtonPosition() { }
	// RVA: 0x37e1438 VA: 0x7595df9438
	private CameraStateType get_m_cameraType() { }
	// RVA: 0x37e15bc VA: 0x7595df95bc
	public Void Setup(ISpaceOccupation occupation, FurnitureLocationType locationType, Camera mainCamera, CameraState cameraState, Boolean enableRotate) { }
	// RVA: 0x37e2a20 VA: 0x7595dfaa20
	public Void UpdatePosition() { }
	// RVA: 0x37e172c VA: 0x7595df972c
	private Void _UpdatePosition(Boolean force, Boolean updateTextPos) { }
	// RVA: 0x37e2a90 VA: 0x7595dfaa90
	private Void _UpdateButtonTransform() { }
	// RVA: 0x37e2bfc VA: 0x7595dfabfc
	public Void PlayDragedAnim() { }
	// RVA: 0x37e333c VA: 0x7595dfb33c
	private Void OnDestroy() { }
	// RVA: 0x37e3614 VA: 0x7595dfb614
	public Void StopDragedAnim() { }
	// RVA: 0x37e3788 VA: 0x7595dfb788
	private Void _UpdateMaterialColor(Color color) { }
	// RVA: 0x37e3908 VA: 0x7595dfb908
	private Void _UpdateInnerCubeColor(Single density) { }
	// RVA: 0x37e259c VA: 0x7595dfa59c
	private Void _ParseAllMaterial() { }
	// RVA: 0x37e34c0 VA: 0x7595dfb4c0
	private Void _ClearMaterials() { }
	// RVA: 0x37e39f4 VA: 0x7595dfb9f4
	private Void Update() { }
	// RVA: 0x37e3b04 VA: 0x7595dfbb04
	public Void .ctor() { }
}
```