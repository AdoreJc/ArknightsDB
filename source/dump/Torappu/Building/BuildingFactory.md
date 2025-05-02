# BuildingFactory

**Namespace:** `Torappu.Building`


## Fields

- `BRoom _defaultBRoom`

- `VRoom _defaultVRoom`

- `GameObjectSplitFrameLoadBalancer m_loadBalancer`


## Properties

- `AbstractAssetLoader directAssetLoader`


## Methods

- `AbstractAssetLoader get_directAssetLoader()`

- `Void OnStart()`

- `BRoomSlot CreateBRoomSlot(Transform)`

- `BRoom CreateBRoom(String, Transform)`

- `BRoomHilightContainer CreateBRoomSlotHilight()`

- `VRoom CreateVRoom(String, Transform)`

- `VDoor CreateVDoor(String, Transform)`

- `Void CreateVCharacterAsync(CharUISkinStruct, Transform, Action`1)`

- `Void _OnBuildingModeChanged(Object)`

- `Void _CheckIsPauseForSplitFrameLoader()`

- `Void OnDestroy()`

- `Void Update()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building
public class BuildingFactory : MonoBehaviour, IHotfixable
{
	private BRoom _defaultBRoom; // 0x18
	private VRoom _defaultVRoom; // 0x20
	private GameObjectSplitFrameLoadBalancer m_loadBalancer; // 0x28
	private static DelegateBridge __Hotfix0_get_directAssetLoader; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8
	private static DelegateBridge __Hotfix0_OnStart; // 0x10
	private static DelegateBridge __Hotfix0_CreateBRoomSlot; // 0x18
	private static DelegateBridge __Hotfix0_CreateBRoom; // 0x20
	private static DelegateBridge __Hotfix0_CreateBRoomSlotHilight; // 0x28
	private static DelegateBridge __Hotfix0_CreateVRoom; // 0x30
	private static DelegateBridge __Hotfix0_CreateVDoor; // 0x38
	private static DelegateBridge __Hotfix0_CreateVCharacterAsync; // 0x40
	private static DelegateBridge __Hotfix0__OnBuildingModeChanged; // 0x48
	private static DelegateBridge __Hotfix0__CheckIsPauseForSplitFrameLoader; // 0x50
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x58
	private static DelegateBridge __Hotfix0_Update; // 0x60

	private AbstractAssetLoader directAssetLoader { get; }

	// RVA: 0x377bd30 VA: 0x7595d93d30
	private AbstractAssetLoader get_directAssetLoader() { }
	// RVA: 0x377bda4 VA: 0x7595d93da4
	public Void .ctor() { }
	// RVA: 0x377a15c VA: 0x7595d9215c
	public Void OnStart() { }
	// RVA: 0x377bf84 VA: 0x7595d93f84
	public BRoomSlot CreateBRoomSlot(Transform parent) { }
	// RVA: 0x377c12c VA: 0x7595d9412c
	public BRoom CreateBRoom(String roomId, Transform parent) { }
	// RVA: 0x377c284 VA: 0x7595d94284
	public BRoomHilightContainer CreateBRoomSlotHilight() { }
	// RVA: 0x377c424 VA: 0x7595d94424
	public VRoom CreateVRoom(String roomId, Transform parent) { }
	// RVA: 0x377c57c VA: 0x7595d9457c
	public VDoor CreateVDoor(String doorId, Transform parent) { }
	// RVA: 0x377c6d8 VA: 0x7595d946d8
	public Void CreateVCharacterAsync(CharUISkinStruct skinStruct, Transform parent, Action`1 cb) { }
	// RVA: 0x377c89c VA: 0x7595d9489c
	private Void _OnBuildingModeChanged(Object arg) { }
	// RVA: 0x377be9c VA: 0x7595d93e9c
	private Void _CheckIsPauseForSplitFrameLoader() { }
	// RVA: 0x377c918 VA: 0x7595d94918
	private Void OnDestroy() { }
	// RVA: 0x377ca4c VA: 0x7595d94a4c
	private Void Update() { }
}
```