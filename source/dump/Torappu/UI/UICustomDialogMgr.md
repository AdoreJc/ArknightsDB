# UICustomDialogMgr

**Namespace:** `Torappu.UI`


## Fields

- `RectTransform _dialogContainer`

- `Camera m_uiCamera`


## Methods

- `Boolean Show(DynDialogParam, OptionType)`

- `Boolean Show(StaticDialogParam, OptionType)`

- `Void DialogMessage(Int32, ValueBundle)`

- `Void DialogMessage(Int32)`

- `Boolean _ShowDialogImpl(DialogType, OptionType)`

- `Void DialogCore_DestroyDialog(Int32)`

- `CameraWrapper DialogCore_GetCameraWrapper()`

- `Void DialogCore_HookFindViewableCameras(IList`1)`

- `Void _LoadUiCameraIfNecessary()`

- `Void _UnloadUnusedPrefabs()`

- `Int32 _GetAssetGroup()`

- `DialogType _CreateDialogInst(DynDialogParam)`

- `DialogType _CreateDialogInst(StaticDialogParam)`

- `Void OnDisable()`

- `Void _DisposeSelf()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICustomDialogMgr : SingletonMonoBehaviour`1, IHotfixable
{
	private RectTransform _dialogContainer; // 0x18
	private List`1 m_dialogInsts; // 0x20
	private List`1 m_loadedPrefabs; // 0x28
	private Camera m_uiCamera; // 0x30
	private static DelegateBridge __Hotfix0_Show; // 0x0
	private static DelegateBridge __Hotfix1_Show; // 0x8
	private static DelegateBridge __Hotfix0_DialogMessage; // 0x10
	private static DelegateBridge __Hotfix1_DialogMessage; // 0x18
	private static DelegateBridge __Hotfix0__ShowDialogImpl; // 0x20
	private static DelegateBridge __Hotfix0_DialogCore_DestroyDialog; // 0x28
	private static DelegateBridge __Hotfix0_DialogCore_GetCameraWrapper; // 0x30
	private static DelegateBridge __Hotfix0_DialogCore_HookFindViewableCameras; // 0x38
	private static DelegateBridge __Hotfix0__LoadUiCameraIfNecessary; // 0x40
	private static DelegateBridge __Hotfix0__UnloadUnusedPrefabs; // 0x48
	private static DelegateBridge __Hotfix0__GetAssetGroup; // 0x50
	private static DelegateBridge __Hotfix0__UnloadDialog; // 0x58
	private static DelegateBridge __Hotfix0__CreateDialogInst; // 0x60
	private static DelegateBridge __Hotfix1__CreateDialogInst; // 0x68
	private static DelegateBridge __Hotfix0__LoadDialog; // 0x70
	private static DelegateBridge __Hotfix0_OnDisable; // 0x78
	private static DelegateBridge __Hotfix0__DisposeSelf; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88


	// RVA: 0x VA: 0x0
	public Boolean Show(DynDialogParam dialogParam, OptionType options) { }
	// RVA: 0x VA: 0x0
	public Boolean Show(StaticDialogParam dialogParam, OptionType options) { }
	// RVA: 0x VA: 0x0
	public Void DialogMessage(Int32 msg, ValueBundle param) { }
	// RVA: 0x VA: 0x0
	public Void DialogMessage(Int32 msg) { }
	// RVA: 0x VA: 0x0
	private Boolean _ShowDialogImpl(DialogType dialog, OptionType options) { }
	// RVA: 0x2267884 VA: 0x759487f884
	public Void DialogCore_DestroyDialog(Int32 instCode) { }
	// RVA: 0x2267bb0 VA: 0x759487fbb0
	public CameraWrapper DialogCore_GetCameraWrapper() { }
	// RVA: 0x2267d74 VA: 0x759487fd74
	public Void DialogCore_HookFindViewableCameras(IList`1 cameraList) { }
	// RVA: 0x2267c38 VA: 0x759487fc38
	private Void _LoadUiCameraIfNecessary() { }
	// RVA: 0x22679b8 VA: 0x759487f9b8
	private Void _UnloadUnusedPrefabs() { }
	// RVA: 0x2267ebc VA: 0x759487febc
	private Int32 _GetAssetGroup() { }
	// RVA: 0x2267f28 VA: 0x759487ff28
	private static Void _UnloadDialog(GameObject prefab, Int32 assetGroup) { }
	// RVA: 0x VA: 0x0
	private DialogType _CreateDialogInst(DynDialogParam dialogParam) { }
	// RVA: 0x VA: 0x0
	private DialogType _CreateDialogInst(StaticDialogParam dialogParam) { }
	// RVA: 0x2268048 VA: 0x7594880048
	private static GameObject _LoadDialog(String resPath, Int32 assetGroup) { }
	// RVA: 0x226815c VA: 0x759488015c
	private Void OnDisable() { }
	// RVA: 0x22681c4 VA: 0x75948801c4
	private Void _DisposeSelf() { }
	// RVA: 0x22683c4 VA: 0x75948803c4
	public Void .ctor() { }
}
```