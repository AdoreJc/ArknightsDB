# BuildingAVGAdapter

**Namespace:** `Torappu.Building`


## Fields

- `Button m_bRoomTutorialBtn`


## Methods

- `Void _OnStoryBegin(Object)`

- `Void _OnStoryEnd(Object)`

- `Void _BlockBuildingModeRaycast(Boolean)`

- `Boolean _ExecutePrivateReturn(Command)`

- `Boolean _ExecuteFocusPrivateChar(Command)`

- `Boolean _ExecuteFocusBRoom(Command)`

- `Boolean _ExecuteBlockRaycaster(Command)`

- `Boolean _ExecuteEnsureOperationMode(Command)`

- `Void Start()`

- `Void OnDestroy()`

- `Void <_ExecuteFocusBRoom>b__8_0(Boolean)`

- `Void <_ExecuteFocusBRoom>b__8_1(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building
public class BuildingAVGAdapter : ExecutorComponent
{
	private Button m_bRoomTutorialBtn; // 0x50
	private static DelegateBridge __Hotfix0_GetExecutors; // 0x0
	private static DelegateBridge __Hotfix0_ForceCommandEnd; // 0x8
	private static DelegateBridge __Hotfix0__OnStoryBegin; // 0x10
	private static DelegateBridge __Hotfix0__OnStoryEnd; // 0x18
	private static DelegateBridge __Hotfix0__BlockBuildingModeRaycast; // 0x20
	private static DelegateBridge __Hotfix0__ExecutePrivateReturn; // 0x28
	private static DelegateBridge __Hotfix0__ExecuteFocusPrivateChar; // 0x30
	private static DelegateBridge __Hotfix0__ExecuteFocusBRoom; // 0x38
	private static DelegateBridge __Hotfix0__ExecuteBlockRaycaster; // 0x40
	private static DelegateBridge __Hotfix0__ExecuteEnsureOperationMode; // 0x48
	private static DelegateBridge __Hotfix0_Start; // 0x50
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x37956b4 VA: 0x7595dad6b4
	public override Dictionary`2 GetExecutors() { }
	// RVA: 0x3795a18 VA: 0x7595dada18
	protected override Void ForceCommandEnd() { }
	// RVA: 0x3795a7c VA: 0x7595dada7c
	private Void _OnStoryBegin(Object arg) { }
	// RVA: 0x3795c0c VA: 0x7595dadc0c
	private Void _OnStoryEnd(Object arg) { }
	// RVA: 0x3795b64 VA: 0x7595dadb64
	private Void _BlockBuildingModeRaycast(Boolean isBlock) { }
	// RVA: 0x3795c8c VA: 0x7595dadc8c
	private Boolean _ExecutePrivateReturn(Command command) { }
	// RVA: 0x3795fe0 VA: 0x7595dadfe0
	private Boolean _ExecuteFocusPrivateChar(Command command) { }
	// RVA: 0x37963c4 VA: 0x7595dae3c4
	private Boolean _ExecuteFocusBRoom(Command command) { }
	// RVA: 0x3796828 VA: 0x7595dae828
	private Boolean _ExecuteBlockRaycaster(Command command) { }
	// RVA: 0x37968e0 VA: 0x7595dae8e0
	private Boolean _ExecuteEnsureOperationMode(Command command) { }
	// RVA: 0x37969d8 VA: 0x7595dae9d8
	private Void Start() { }
	// RVA: 0x3796bd8 VA: 0x7595daebd8
	private Void OnDestroy() { }
	// RVA: 0x3796da0 VA: 0x7595daeda0
	public Void .ctor() { }
	// RVA: 0x3796e10 VA: 0x7595daee10
	private Void <_ExecuteFocusBRoom>b__8_0(Boolean succeed) { }
	// RVA: 0x3796e18 VA: 0x7595daee18
	private Void <_ExecuteFocusBRoom>b__8_1(Boolean succeed) { }
}
```