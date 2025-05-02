# RallyPointRebornTalent

**Namespace:** `Torappu.Battle`


## Fields

- `Buff m_rebornBuff`


## Properties

- `FP rebornProgress`


## Methods

- `Void _FetchFirstPassiveBuffUids()`

- `FP get_rebornProgress()`

- `Void <>xLuaBaseProxy_DoAttach()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class RallyPointRebornTalent : Talent
{
	private Buff m_rebornBuff; // 0x88
	private static DelegateBridge __Hotfix0_DoAttach; // 0x0
	private static DelegateBridge __Hotfix0__FetchFirstPassiveBuffUids; // 0x8
	private static DelegateBridge __Hotfix0_get_rebornProgress; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public FP rebornProgress { get; }

	// RVA: 0x1b7e0f0 VA: 0x75941960f0
	protected override Void DoAttach() { }
	// RVA: 0x1b7e170 VA: 0x7594196170
	private Void _FetchFirstPassiveBuffUids() { }
	// RVA: 0x1b7e2ec VA: 0x75941962ec
	public FP get_rebornProgress() { }
	// RVA: 0x1b7e3bc VA: 0x75941963bc
	public Void .ctor() { }
	// RVA: 0x1b7e428 VA: 0x7594196428
	private Void <>xLuaBaseProxy_DoAttach() { }
}
```