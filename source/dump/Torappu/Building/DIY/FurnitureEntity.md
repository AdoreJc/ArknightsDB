# FurnitureEntity

**Namespace:** `Torappu.Building.DIY`


## Fields

- `Direction m_direction`

- `Vector3 m_oldDim`

- `IFurnitureController m_controller`

- `Tween m_DragedTween`

- `Boolean m_validOnRotate`

- `Boolean m_isOnCeil`

- `Boolean m_isOnWall`


## Properties

- `IFurnitureController controller`

- `Direction direction`

- `Boolean isDefaultDir`

- `Boolean enableInteract`

- `Boolean enableRotate`


## Methods

- `IFurnitureController get_controller()`

- `Void RegisterControllerHolder(IFurnitureController)`

- `Void _Reset()`

- `Void PlayDragedAnim()`

- `Void PlayDragedAnim(Transform)`

- `Void StopDragedAnim()`

- `Void OnDestroy()`

- `Direction get_direction()`

- `Void set_direction(Direction)`

- `Boolean get_isDefaultDir()`

- `Boolean get_enableInteract()`

- `Boolean get_enableRotate()`

- `Void RotateToNext(out, Int32)`

- `FourDirLocalOffset _GetRotateInitInfo(Transform)`

- `Void UpdateRotateState()`

- `Void _UpdateRotateState(Transform)`

- `Vector2 <GatherAttachPoints>b__24_0(Int32, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY
public class FurnitureEntity : MonoBehaviour, IHotfixable
{
	private const String FURNITURE_MODEL_PREFIX; // 0x0
	public AttachPoint[] attachPoints; // 0x18
	private Direction m_direction; // 0x20
	private Vector3 m_oldDim; // 0x24
	private IFurnitureController m_controller; // 0x30
	private Dictionary`2 m_InitFourDirInfo; // 0x38
	private Tween m_DragedTween; // 0x40
	private Boolean m_validOnRotate; // 0x48
	private Boolean m_isOnCeil; // 0x49
	private Boolean m_isOnWall; // 0x4a
	public List`1 _fourDirLocalOffset; // 0x50
	private static DelegateBridge __Hotfix0_get_controller; // 0x0
	private static DelegateBridge __Hotfix0_get_fourDirLocalOffsetDict; // 0x8
	private static DelegateBridge __Hotfix0_RegisterControllerHolder; // 0x10
	private static DelegateBridge __Hotfix0__Reset; // 0x18
	private static DelegateBridge __Hotfix0_PlayDragedAnim; // 0x20
	private static DelegateBridge __Hotfix1_PlayDragedAnim; // 0x28
	private static DelegateBridge __Hotfix0_StopDragedAnim; // 0x30
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x38
	private static DelegateBridge __Hotfix0_GatherAttachPoints; // 0x40
	private static DelegateBridge __Hotfix0_get_direction; // 0x48
	private static DelegateBridge __Hotfix0_set_direction; // 0x50
	private static DelegateBridge __Hotfix0_get_isDefaultDir; // 0x58
	private static DelegateBridge __Hotfix0_get_enableInteract; // 0x60
	private static DelegateBridge __Hotfix0_get_enableRotate; // 0x68
	private static DelegateBridge __Hotfix0_RotateToNext; // 0x70
	private static DelegateBridge __Hotfix0__GetRotateInitInfo; // 0x78
	private static DelegateBridge __Hotfix0_UpdateRotateState; // 0x80
	private static DelegateBridge __Hotfix0__UpdateRotateState; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90

	public IFurnitureController controller { get; }
	public Dictionary`2 fourDirLocalOffsetDict { get; }
	public Direction direction { get; set; }
	public Boolean isDefaultDir { get; }
	public Boolean enableInteract { get; }
	public Boolean enableRotate { get; }

	// RVA: 0x37cce4c VA: 0x7595de4e4c
	public IFurnitureController get_controller() { }
	// RVA: 0x37cceb4 VA: 0x7595de4eb4
	public Dictionary`2 get_fourDirLocalOffsetDict() { }
	// RVA: 0x37cd08c VA: 0x7595de508c
	public Void RegisterControllerHolder(IFurnitureController controller) { }
	// RVA: 0x37cd458 VA: 0x7595de5458
	private Void _Reset() { }
	// RVA: 0x37cd4c4 VA: 0x7595de54c4
	public Void PlayDragedAnim() { }
	// RVA: 0x37cd838 VA: 0x7595de5838
	public Void PlayDragedAnim(Transform trans) { }
	// RVA: 0x37cdb38 VA: 0x7595de5b38
	public Void StopDragedAnim() { }
	// RVA: 0x37ce1b4 VA: 0x7595de61b4
	private Void OnDestroy() { }
	// RVA: 0x37ce234 VA: 0x7595de6234
	public AttachPoint[] GatherAttachPoints() { }
	// RVA: 0x37ce5d8 VA: 0x7595de65d8
	public Direction get_direction() { }
	// RVA: 0x37ce640 VA: 0x7595de6640
	public Void set_direction(Direction value) { }
	// RVA: 0x37ce460 VA: 0x7595de6460
	public Boolean get_isDefaultDir() { }
	// RVA: 0x37ce3cc VA: 0x7595de63cc
	public Boolean get_enableInteract() { }
	// RVA: 0x37ce6bc VA: 0x7595de66bc
	public Boolean get_enableRotate() { }
	// RVA: 0x37ce7a4 VA: 0x7595de67a4
	public Void RotateToNext(out Vector2 posOffset, Int32 maxLRWidth) { }
	// RVA: 0x37ce928 VA: 0x7595de6928
	private FourDirLocalOffset _GetRotateInitInfo(Transform trans) { }
	// RVA: 0x37cdbb0 VA: 0x7595de5bb0
	public Void UpdateRotateState() { }
	// RVA: 0x37ceb44 VA: 0x7595de6b44
	private Void _UpdateRotateState(Transform trans) { }
	// RVA: 0x37ceecc VA: 0x7595de6ecc
	public Void .ctor() { }
	// RVA: 0x37cf020 VA: 0x7595de7020
	private Vector2 <GatherAttachPoints>b__24_0(Int32 x, Int32 y) { }
}
```