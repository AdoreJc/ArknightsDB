# VPlayerOwnedVisitor

**Namespace:** `Torappu.Building.Vault`


## Fields

- `BuildingController m_controller`

- `InvokeWhenUnlock m_invokeWhenVCharCreated`

- `TickFunction m_tickFunction`

- `VCharacter m_targetChar`

- `Boolean m_isActived`


## Methods

- `Void Dispose()`

- `Void _BindEvents()`

- `Void _UnbindEvents()`

- `Void _OnRoomObjectCreated(Object)`

- `Void _TryToStartCharYieldInst(VCharacter)`

- `Void _OnMeetingRoomFocusedBySceneParam(Object)`

- `Void _Release()`

- `Boolean IsActive()`

- `Void BindController(BuildingController)`

- `Void Tick(Single)`

- `Boolean CheckNeedActiveWithoutController()`

- `Void Clear()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.Vault
public class VPlayerOwnedVisitor : IBuildingBindTools, IHotfixable, IDisposable
{
	private BuildingController m_controller; // 0x10
	private InvokeWhenUnlock m_invokeWhenVCharCreated; // 0x18
	private TickFunction m_tickFunction; // 0x20
	private VCharacter m_targetChar; // 0x28
	private Boolean m_isActived; // 0x30
	private static DelegateBridge __Hotfix0_Dispose; // 0x0
	private static DelegateBridge __Hotfix0__BindEvents; // 0x8
	private static DelegateBridge __Hotfix0__UnbindEvents; // 0x10
	private static DelegateBridge __Hotfix0__OnRoomObjectCreated; // 0x18
	private static DelegateBridge __Hotfix0__TryToStartCharYieldInst; // 0x20
	private static DelegateBridge __Hotfix0__CreateYieldWaitForValid; // 0x28
	private static DelegateBridge __Hotfix0__OnMeetingRoomFocusedBySceneParam; // 0x30
	private static DelegateBridge __Hotfix0__Release; // 0x38
	private static DelegateBridge __Hotfix0_IsActive; // 0x40
	private static DelegateBridge __Hotfix0_BindController; // 0x48
	private static DelegateBridge __Hotfix0_Tick; // 0x50
	private static DelegateBridge __Hotfix0_CheckNeedActiveWithoutController; // 0x58
	private static DelegateBridge __Hotfix0_Clear; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68


	// RVA: 0x384799c VA: 0x7595e5f99c
	public Void Dispose() { }
	// RVA: 0x3847c5c VA: 0x7595e5fc5c
	private Void _BindEvents() { }
	// RVA: 0x3847a0c VA: 0x7595e5fa0c
	private Void _UnbindEvents() { }
	// RVA: 0x3847e08 VA: 0x7595e5fe08
	private Void _OnRoomObjectCreated(Object arg) { }
	// RVA: 0x38480e4 VA: 0x7595e600e4
	private Void _TryToStartCharYieldInst(VCharacter vChar) { }
	// RVA: 0x3848230 VA: 0x7595e60230
	private Func`2 _CreateYieldWaitForValid(VCharacter vCharacter) { }
	// RVA: 0x384833c VA: 0x7595e6033c
	private Void _OnMeetingRoomFocusedBySceneParam(Object _) { }
	// RVA: 0x3847bb8 VA: 0x7595e5fbb8
	private Void _Release() { }
	// RVA: 0x38483d0 VA: 0x7595e603d0
	public Boolean IsActive() { }
	// RVA: 0x3848438 VA: 0x7595e60438
	public Void BindController(BuildingController controller) { }
	// RVA: 0x3848504 VA: 0x7595e60504
	public Void Tick(Single ts) { }
	// RVA: 0x38485fc VA: 0x7595e605fc
	public Boolean CheckNeedActiveWithoutController() { }
	// RVA: 0x38486a8 VA: 0x7595e606a8
	public Void Clear() { }
	// RVA: 0x3848718 VA: 0x7595e60718
	public Void .ctor() { }
}
```