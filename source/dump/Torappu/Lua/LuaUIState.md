# LuaUIState

**Namespace:** `Torappu.Lua`


## Fields

- `String _mainDialog`

- `LuaUIContext m_context`


## Properties

- `Transform root`

- `String mainDialog`


## Methods

- `Transform get_root()`

- `String get_mainDialog()`

- `Void OnLeaveContext()`

- `T LoadAsset(String)`

- `Void UnloadAsset(Object)`

- `Void HandleOpenState(String)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Lua
public class LuaUIState : PopupFloatState, IContextHost
{
	private String _mainDialog; // 0x70
	private LuaUIContext m_context; // 0x78
	private static DelegateBridge __Hotfix0_get_root; // 0x0
	private static DelegateBridge __Hotfix0_get_mainDialog; // 0x8
	private static DelegateBridge __Hotfix0_OnLeaveContext; // 0x10
	private static DelegateBridge __Hotfix0_LoadAsset; // 0x18
	private static DelegateBridge __Hotfix0_UnloadAsset; // 0x20
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x28
	private static DelegateBridge __Hotfix0_OnEnter; // 0x30
	private static DelegateBridge __Hotfix0_OnResume; // 0x38
	private static DelegateBridge __Hotfix0_HandleOpenState; // 0x40
	private static DelegateBridge __Hotfix0_CompDeclaration; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public Transform root { get; }
	public String mainDialog { get; }

	// RVA: 0x35b4bd0 VA: 0x7595bccbd0
	public Transform get_root() { }
	// RVA: 0x35b4c3c VA: 0x7595bccc3c
	public String get_mainDialog() { }
	// RVA: 0x35b4ca4 VA: 0x7595bccca4
	public Void OnLeaveContext() { }
	// RVA: 0x VA: 0x0
	public T LoadAsset(String path) { }
	// RVA: 0x35b4d18 VA: 0x7595bccd18
	public Void UnloadAsset(Object asset) { }
	// RVA: 0x35b4dac VA: 0x7595bccdac
	public override IStateBean GetCacheBean() { }
	// RVA: 0x35b4e10 VA: 0x7595bcce10
	protected override Void OnEnter() { }
	// RVA: 0x35b4ed4 VA: 0x7595bcced4
	protected override Void OnResume() { }
	// RVA: 0x35b4fb8 VA: 0x7595bccfb8
	public Void HandleOpenState(String stateType) { }
	// RVA: 0x35b51e4 VA: 0x7595bcd1e4
	public IDictionary`2 CompDeclaration() { }
	// RVA: 0x35b5248 VA: 0x7595bcd248
	public Void .ctor() { }
	// RVA: 0x35b52b8 VA: 0x7595bcd2b8
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x35b52c0 VA: 0x7595bcd2c0
	private Void <>xLuaBaseProxy_OnResume() { }
}
```