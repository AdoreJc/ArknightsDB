# HotUpdatePreMainTicker

**Namespace:** `Torappu.UI.HotUpdate`


## Fields

- `TickFunction m_tickPreMainFunction`

- `Single m_preMainLastTimeStamp`

- `Single m_preMainTimeStamp`

- `Action m_onChangePic`

- `Single delta`


## Methods

- `Void _OnTickWork(Single)`

- `Void StartTick()`

- `Void StopTick()`

- `Void OnClear()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HotUpdate
public class HotUpdatePreMainTicker : IHotfixable
{
	private TickFunction m_tickPreMainFunction; // 0x10
	private Single m_preMainLastTimeStamp; // 0x18
	private Single m_preMainTimeStamp; // 0x1c
	private Action m_onChangePic; // 0x20
	private Single delta; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0__OnTickWork; // 0x8
	private static DelegateBridge __Hotfix0_StartTick; // 0x10
	private static DelegateBridge __Hotfix0_StopTick; // 0x18
	private static DelegateBridge __Hotfix0_OnClear; // 0x20


	// RVA: 0x27bcfc4 VA: 0x7594dd4fc4
	public Void .ctor(Action onChangePic) { }
	// RVA: 0x27cb6d4 VA: 0x7594de36d4
	public Void _OnTickWork(Single deltaTime) { }
	// RVA: 0x27cb790 VA: 0x7594de3790
	public Void StartTick() { }
	// RVA: 0x27cb808 VA: 0x7594de3808
	public Void StopTick() { }
	// RVA: 0x27bd280 VA: 0x7594dd5280
	public Void OnClear() { }
}
```