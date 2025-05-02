# LuaActivityEntry

**Namespace:** `Torappu.Lua`


## Fields

- `String _mainDialog`

- `String _activityId`

- `String _dlgPath`

- `String _overrideBaseCls`

- `LuaUIContext m_context`

- `String m_mainDialogCls`

- `IDismissControl m_luaBridge`


## Properties

- `LuaLayout _dragLuaLayoutHere`

- `Transform root`

- `String mainDialog`


## Methods

- `LuaLayout get__dragLuaLayoutHere()`

- `Void set__dragLuaLayoutHere(LuaLayout)`

- `Transform get_root()`

- `String get_mainDialog()`

- `Void OnLeaveContext()`

- `T LoadAsset(String)`

- `Void UnloadAsset(Object)`

- `String _GetMainDialogClass()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnExit()`

- `Boolean <>xLuaBaseProxy_TryDismissBackPress()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Lua
public class LuaActivityEntry : ActivityCommonEntry, IContextHost
{
	public const String KEY_DISMISS_CONTROL; // 0x0
	private String _mainDialog; // 0x38
	private String _activityId; // 0x40
	private String _dlgPath; // 0x48
	private String _overrideBaseCls; // 0x50
	private LuaUIContext m_context; // 0x58
	private String m_mainDialogCls; // 0x60
	private IDismissControl m_luaBridge; // 0x68
	private static DelegateBridge __Hotfix0_get__dragLuaLayoutHere; // 0x0
	private static DelegateBridge __Hotfix0_set__dragLuaLayoutHere; // 0x8
	private static DelegateBridge __Hotfix0_get_root; // 0x10
	private static DelegateBridge __Hotfix0_get_mainDialog; // 0x18
	private static DelegateBridge __Hotfix0_OnEnter; // 0x20
	private static DelegateBridge __Hotfix0_OnResume; // 0x28
	private static DelegateBridge __Hotfix0_OnExit; // 0x30
	private static DelegateBridge __Hotfix0_TryDismissBackPress; // 0x38
	private static DelegateBridge __Hotfix0_OnLeaveContext; // 0x40
	private static DelegateBridge __Hotfix0_LoadAsset; // 0x48
	private static DelegateBridge __Hotfix0_UnloadAsset; // 0x50
	private static DelegateBridge __Hotfix0__GetMainDialogClass; // 0x58
	private static DelegateBridge __Hotfix0_StartStoryWithSyncMusic; // 0x60
	private static DelegateBridge __Hotfix0_CompDeclaration; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	private LuaLayout _dragLuaLayoutHere { get; set; }
	public Transform root { get; }
	public String mainDialog { get; }

	// RVA: 0x35b3108 VA: 0x7595bcb108
	private LuaLayout get__dragLuaLayoutHere() { }
	// RVA: 0x35b316c VA: 0x7595bcb16c
	private Void set__dragLuaLayoutHere(LuaLayout value) { }
	// RVA: 0x35b31e4 VA: 0x7595bcb1e4
	public Transform get_root() { }
	// RVA: 0x35b3250 VA: 0x7595bcb250
	public String get_mainDialog() { }
	// RVA: 0x35b35e0 VA: 0x7595bcb5e0
	public override Void OnEnter(String activityId) { }
	// RVA: 0x35b3714 VA: 0x7595bcb714
	public override Void OnResume() { }
	// RVA: 0x35b38a4 VA: 0x7595bcb8a4
	public override Void OnExit() { }
	// RVA: 0x35b393c VA: 0x7595bcb93c
	public override Boolean TryDismissBackPress() { }
	// RVA: 0x35b3a78 VA: 0x7595bcba78
	public Void OnLeaveContext() { }
	// RVA: 0x VA: 0x0
	public T LoadAsset(String path) { }
	// RVA: 0x35b3ae4 VA: 0x7595bcbae4
	public Void UnloadAsset(Object asset) { }
	// RVA: 0x35b32fc VA: 0x7595bcb2fc
	private String _GetMainDialogClass() { }
	// RVA: 0x35b3b78 VA: 0x7595bcbb78
	public static Void StartStoryWithSyncMusic(String storyId) { }
	// RVA: 0x35b3cd0 VA: 0x7595bcbcd0
	public IDictionary`2 CompDeclaration() { }
	// RVA: 0x35b3e0c VA: 0x7595bcbe0c
	public Void .ctor() { }
	// RVA: 0x35b3e7c VA: 0x7595bcbe7c
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x35b3e84 VA: 0x7595bcbe84
	private Void <>xLuaBaseProxy_OnExit() { }
	// RVA: 0x35b3e8c VA: 0x7595bcbe8c
	private Boolean <>xLuaBaseProxy_TryDismissBackPress() { }
}
```