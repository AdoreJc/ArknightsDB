# CountStyleAnimController

**Namespace:** ` `


## Fields

- `MedalShowBarListView m_closure`

- `Boolean m_showProgressDetails`

- `Boolean m_isSwitchingProgress`


## Methods

- `Void ResetAnim()`

- `Void SwitchAnim()`

- `Void StopAnim()`

- `Void _StopAnimImpl()`

- `Void <SwitchAnim>b__5_0(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class CountStyleAnimController : IHotfixable
{
	private MedalShowBarListView m_closure; // 0x10
	private Boolean m_showProgressDetails; // 0x18
	private Boolean m_isSwitchingProgress; // 0x19
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_ResetAnim; // 0x8
	private static DelegateBridge __Hotfix0_SwitchAnim; // 0x10
	private static DelegateBridge __Hotfix0_StopAnim; // 0x18
	private static DelegateBridge __Hotfix0__StopAnimImpl; // 0x20


	// RVA: 0x27a4118 VA: 0x7594dbc118
	public Void .ctor(MedalShowBarListView closure) { }
	// RVA: 0x27a4be4 VA: 0x7594dbcbe4
	public Void ResetAnim() { }
	// RVA: 0x27a48d0 VA: 0x7594dbc8d0
	public Void SwitchAnim() { }
	// RVA: 0x27a4b08 VA: 0x7594dbcb08
	public Void StopAnim() { }
	// RVA: 0x27a6de0 VA: 0x7594dbede0
	private Void _StopAnimImpl() { }
	// RVA: 0x27a70d0 VA: 0x7594dbf0d0
	private Void <SwitchAnim>b__5_0(String _) { }
}
```