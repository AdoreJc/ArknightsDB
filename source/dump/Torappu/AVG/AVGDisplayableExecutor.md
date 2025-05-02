# AVGDisplayableExecutor

**Namespace:** `Torappu.AVG`


## Fields

- `Transform _container`

- `Transform _bgOverlayTrans`

- `Transform _charOverlayTrans`

- `AVGDisplayableManager m_manager`


## Methods

- `CmdParam _GenParamWithCmd(Command)`

- `Boolean _ExecuteAVGDisplayable(Command)`

- `Void _EnsureManager()`

- `Boolean _ExecuteAnimatedText(Command)`

- `Boolean _ExecuteAnimatedTextClean(Command)`

- `Void _CleanAllTextStamps()`

- `GameObject _LoadDisplayable(String, AVGDisplayableType)`

- `Void <>xLuaBaseProxy_OnReset()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AVGDisplayableExecutor : ExecutorComponent
{
	private Transform _container; // 0x50
	private Transform _bgOverlayTrans; // 0x58
	private Transform _charOverlayTrans; // 0x60
	private List`1 m_cachedTextStamps; // 0x68
	private AVGDisplayableManager m_manager; // 0x70
	private static DelegateBridge __Hotfix0__GenParamWithCmd; // 0x0
	private static DelegateBridge __Hotfix0_GetExecutors; // 0x8
	private static DelegateBridge __Hotfix0_OnReset; // 0x10
	private static DelegateBridge __Hotfix0_ForceCommandEnd; // 0x18
	private static DelegateBridge __Hotfix0__ExecuteAVGDisplayable; // 0x20
	private static DelegateBridge __Hotfix0__EnsureManager; // 0x28
	private static DelegateBridge __Hotfix0__ExecuteAnimatedText; // 0x30
	private static DelegateBridge __Hotfix0__ExecuteAnimatedTextClean; // 0x38
	private static DelegateBridge __Hotfix0__CleanAllTextStamps; // 0x40
	private static DelegateBridge __Hotfix0__LoadDisplayable; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x3e53854 VA: 0x759646b854
	private CmdParam _GenParamWithCmd(Command cmd) { }
	// RVA: 0x3e53ef0 VA: 0x759646bef0
	public override Dictionary`2 GetExecutors() { }
	// RVA: 0x3e541c8 VA: 0x759646c1c8
	public override Void OnReset() { }
	// RVA: 0x3e544a8 VA: 0x759646c4a8
	protected override Void ForceCommandEnd() { }
	// RVA: 0x3e5450c VA: 0x759646c50c
	private Boolean _ExecuteAVGDisplayable(Command cmd) { }
	// RVA: 0x3e545c4 VA: 0x759646c5c4
	private Void _EnsureManager() { }
	// RVA: 0x3e5490c VA: 0x759646c90c
	private Boolean _ExecuteAnimatedText(Command cmd) { }
	// RVA: 0x3e54c00 VA: 0x759646cc00
	private Boolean _ExecuteAnimatedTextClean(Command cmd) { }
	// RVA: 0x3e542c8 VA: 0x759646c2c8
	private Void _CleanAllTextStamps() { }
	// RVA: 0x3e54e70 VA: 0x759646ce70
	private GameObject _LoadDisplayable(String name, AVGDisplayableType type) { }
	// RVA: 0x3e551e4 VA: 0x759646d1e4
	public Void .ctor() { }
	// RVA: 0x3e553b8 VA: 0x759646d3b8
	private Void <>xLuaBaseProxy_OnReset() { }
}
```