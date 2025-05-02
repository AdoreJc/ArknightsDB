# SandboxV2StateBindingPanelManager

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `StateEngine _stateEngine`

- `OnStateChangeListener m_stateEngineListener`

- `Type m_currTopState`


## Methods

- `Void Init()`

- `Void Watch(SandboxV2StateBindingPanel)`

- `Void Unwatch(SandboxV2StateBindingPanel)`

- `Void _OnBeforeTransition(Type, Type, Additions)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2StateBindingPanelManager : MonoBehaviour, IHotfixable
{
	private StateEngine _stateEngine; // 0x18
	private OnStateChangeListener m_stateEngineListener; // 0x20
	private List`1 m_panels; // 0x28
	private Type m_currTopState; // 0x30
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_Watch; // 0x8
	private static DelegateBridge __Hotfix0_Unwatch; // 0x10
	private static DelegateBridge __Hotfix0__OnBeforeTransition; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2503008 VA: 0x7594b1b008
	public Void Init() { }
	// RVA: 0x2502bf8 VA: 0x7594b1abf8
	public Void Watch(SandboxV2StateBindingPanel element) { }
	// RVA: 0x2502df8 VA: 0x7594b1adf8
	public Void Unwatch(SandboxV2StateBindingPanel element) { }
	// RVA: 0x25030e0 VA: 0x7594b1b0e0
	private Void _OnBeforeTransition(Type stateType, Type toType, Additions additions) { }
	// RVA: 0x250320c VA: 0x7594b1b20c
	public Void .ctor() { }
}
```