# VUISystem

**Namespace:** `Torappu.Building.Vault.UI`


## Fields

- `Canvas _perspectiveUI`

- `RectTransform _orthoUI`

- `Camera m_perspectiveCam`

- `VOUIOrthoPrefabConfig m_orthoPrefabConfig`


## Properties

- `Camera perspectiveCamera`

- `Transform orthoRoot`

- `VOUIOrthoPrefabConfig orthoPrefabConfig`


## Methods

- `Camera get_perspectiveCamera()`

- `Transform get_orthoRoot()`

- `VOUIOrthoPrefabConfig get_orthoPrefabConfig()`

- `Void Update()`

- `Vector2 CalcPosOnPerspectiveCanvas(Vector3)`

- `Vector2 CalcPosOnOrthoCanvas(Vector3)`

- `Void RegisterListeners()`

- `Void _OnBuildingModelLoaded(Object)`

- `Void _OnVaultLayoutUpdate(Object)`

- `Void _OnVaultRoomCharCreated(Object)`

- `Void _OnVaultRoomFurnitureCreated(Object)`

- `Void _OnVaultRoomCharChanged(Object)`

- `Void _OnFuncFurniDataUpdated(Object)`

- `Void _OnVaultRoomObjectDestroyed(Object)`

- `Void _UpdateVPUI()`

- `Void _LoadUIFromModel(BuildingModel)`

- `Void _UpdateVOUI()`

- `VPUIPanel _CreateVPUI(RoomSlotModel)`

- `Void _RecycleVPUI(VPUIPanel)`

- `VPUIPanel _GetVPUIPrefab(RoomSlotModel)`

- `Void _AddVOUIPanel(VOUIPanel, Object)`

- `Void _RecycleVOUI(VOUIPanel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.Vault.UI
public class VUISystem : SingletonMonoBehaviour`1, ISingletonNotAutoCreate
{
	private Canvas _perspectiveUI; // 0x18
	private VPUIPanel[] _perspectiveUIPrefs; // 0x20
	private RectTransform _orthoUI; // 0x28
	private Camera m_perspectiveCam; // 0x30
	private VOUIOrthoPrefabConfig m_orthoPrefabConfig; // 0x38
	private List`1 m_VPUIs; // 0x40
	private List`1 m_VOUIs; // 0x48
	private List`1 m_sharedList; // 0x50
	private static DelegateBridge __Hotfix0_get_perspectiveCamera; // 0x0
	private static DelegateBridge __Hotfix0_get_orthoRoot; // 0x8
	private static DelegateBridge __Hotfix0_get_orthoPrefabConfig; // 0x10
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x18
	private static DelegateBridge __Hotfix0_Update; // 0x20
	private static DelegateBridge __Hotfix0_CalcPosOnPerspectiveCanvas; // 0x28
	private static DelegateBridge __Hotfix0_CalcPosOnOrthoCanvas; // 0x30
	private static DelegateBridge __Hotfix0_RegisterListeners; // 0x38
	private static DelegateBridge __Hotfix0__OnBuildingModelLoaded; // 0x40
	private static DelegateBridge __Hotfix0__OnVaultLayoutUpdate; // 0x48
	private static DelegateBridge __Hotfix0__OnVaultRoomCharCreated; // 0x50
	private static DelegateBridge __Hotfix0__OnVaultRoomFurnitureCreated; // 0x58
	private static DelegateBridge __Hotfix0__OnVaultRoomCharChanged; // 0x60
	private static DelegateBridge __Hotfix0__OnFuncFurniDataUpdated; // 0x68
	private static DelegateBridge __Hotfix0__OnVaultRoomObjectDestroyed; // 0x70
	private static DelegateBridge __Hotfix0__UpdateVPUI; // 0x78
	private static DelegateBridge __Hotfix0__LoadUIFromModel; // 0x80
	private static DelegateBridge __Hotfix0__UpdateVOUI; // 0x88
	private static DelegateBridge __Hotfix0__CreateVPUI; // 0x90
	private static DelegateBridge __Hotfix0__RecycleVPUI; // 0x98
	private static DelegateBridge __Hotfix0__GetVPUIPrefab; // 0xa0
	private static DelegateBridge __Hotfix0__AddVOUIPanel; // 0xa8
	private static DelegateBridge __Hotfix0__RecycleVOUI; // 0xb0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb8

	public Camera perspectiveCamera { get; }
	public Transform orthoRoot { get; }
	private VOUIOrthoPrefabConfig orthoPrefabConfig { get; }

	// RVA: 0x3d0aa84 VA: 0x7596322a84
	public Camera get_perspectiveCamera() { }
	// RVA: 0x3d0ab50 VA: 0x7596322b50
	public Transform get_orthoRoot() { }
	// RVA: 0x3d0abc4 VA: 0x7596322bc4
	private VOUIOrthoPrefabConfig get_orthoPrefabConfig() { }
	// RVA: 0x3d0accc VA: 0x7596322ccc
	protected override Void OnDestroy() { }
	// RVA: 0x3d0afd0 VA: 0x7596322fd0
	private Void Update() { }
	// RVA: 0x3d0a838 VA: 0x7596322838
	public Vector2 CalcPosOnPerspectiveCanvas(Vector3 target) { }
	// RVA: 0x3d092a4 VA: 0x75963212a4
	public Vector2 CalcPosOnOrthoCanvas(Vector3 target) { }
	// RVA: 0x3d0b150 VA: 0x7596323150
	public Void RegisterListeners() { }
	// RVA: 0x3d0b414 VA: 0x7596323414
	private Void _OnBuildingModelLoaded(Object param) { }
	// RVA: 0x3d0b754 VA: 0x7596323754
	private Void _OnVaultLayoutUpdate(Object param) { }
	// RVA: 0x3d0b8b0 VA: 0x75963238b0
	private Void _OnVaultRoomCharCreated(Object param) { }
	// RVA: 0x3d0bd18 VA: 0x7596323d18
	private Void _OnVaultRoomFurnitureCreated(Object param) { }
	// RVA: 0x3d0bfc8 VA: 0x7596323fc8
	private Void _OnVaultRoomCharChanged(Object param) { }
	// RVA: 0x3d0c45c VA: 0x759632445c
	private Void _OnFuncFurniDataUpdated(Object param) { }
	// RVA: 0x3d0c588 VA: 0x7596324588
	private Void _OnVaultRoomObjectDestroyed(Object param) { }
	// RVA: 0x3d0b7d0 VA: 0x75963237d0
	private Void _UpdateVPUI() { }
	// RVA: 0x3d0b4dc VA: 0x75963234dc
	private Void _LoadUIFromModel(BuildingModel model) { }
	// RVA: 0x3d0b038 VA: 0x7596323038
	private Void _UpdateVOUI() { }
	// RVA: 0x3d0caac VA: 0x7596324aac
	private VPUIPanel _CreateVPUI(RoomSlotModel slotModel) { }
	// RVA: 0x3d0cd10 VA: 0x7596324d10
	private Void _RecycleVPUI(VPUIPanel panel) { }
	// RVA: 0x3d0cbd0 VA: 0x7596324bd0
	private VPUIPanel _GetVPUIPrefab(RoomSlotModel slotModel) { }
	// RVA: 0x3d0bb60 VA: 0x7596323b60
	private Void _AddVOUIPanel(VOUIPanel prefab, Object roomObject) { }
	// RVA: 0x3d0ce7c VA: 0x7596324e7c
	private Void _RecycleVOUI(VOUIPanel panel) { }
	// RVA: 0x3d0cf14 VA: 0x7596324f14
	public Void .ctor() { }
}
```