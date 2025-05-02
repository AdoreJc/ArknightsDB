# ReadyToLoginNode

**Namespace:** ` `


## Fields

- `Boolean m_isVoicePrefReady`

- `Boolean m_isBtnEnterClicked`

- `Controller m_voicePrefController`


## Methods

- `Void _InitVoicePrefIfNecessary()`

- `Boolean _ShowVoicePrefSelectPanelIfNecessary()`

- `Boolean <Work>b__5_0()`

- `Boolean <>xLuaBaseProxy_OnEvent(ViewEvent, ValueBundle)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ReadyToLoginNode : Node
{
	private Boolean m_isVoicePrefReady; // 0x20
	private Boolean m_isBtnEnterClicked; // 0x21
	private Controller m_voicePrefController; // 0x28
	private static DelegateBridge __Hotfix0_get_type; // 0x0
	private static DelegateBridge __Hotfix0_Work; // 0x8
	private static DelegateBridge __Hotfix0_OnEvent; // 0x10
	private static DelegateBridge __Hotfix0__InitVoicePrefIfNecessary; // 0x18
	private static DelegateBridge __Hotfix0__ShowVoicePrefSelectPanelIfNecessary; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public override ENode type { get; }

	// RVA: 0x27c82ac VA: 0x7594de02ac
	public override ENode get_type() { }
	// RVA: 0x27c8314 VA: 0x7594de0314
	public override CustomYieldInstruction Work() { }
	// RVA: 0x27c85e8 VA: 0x7594de05e8
	public override Boolean OnEvent(ViewEvent evt, ValueBundle param) { }
	// RVA: 0x27c86c8 VA: 0x7594de06c8
	private Void _InitVoicePrefIfNecessary() { }
	// RVA: 0x27c8530 VA: 0x7594de0530
	private Boolean _ShowVoicePrefSelectPanelIfNecessary() { }
	// RVA: 0x27bfb94 VA: 0x7594dd7b94
	public Void .ctor() { }
	// RVA: 0x27c8848 VA: 0x7594de0848
	private Boolean <Work>b__5_0() { }
	// RVA: 0x27c8868 VA: 0x7594de0868
	private Boolean <>xLuaBaseProxy_OnEvent(ViewEvent P0, ValueBundle P1) { }
}
```