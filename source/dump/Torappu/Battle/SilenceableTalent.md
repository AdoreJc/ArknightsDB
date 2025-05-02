# SilenceableTalent

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _isSilenceable`

- `Boolean m_isManuallyAttached`


## Methods

- `Void _UpdateInternalAbilityAttachStatus(Boolean)`

- `Void _OnAbnormalFlagPossiblyChanged(AbnormalFlag)`

- `Void <>xLuaBaseProxy_DoAttach()`

- `Void <>xLuaBaseProxy_DoDetach()`

- `Void <>xLuaBaseProxy_OnRecycle()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class SilenceableTalent : Talent
{
	private Boolean _isSilenceable; // 0x88
	private Boolean m_isManuallyAttached; // 0x89
	private static DelegateBridge __Hotfix0_DoAttach; // 0x0
	private static DelegateBridge __Hotfix0_DoDetach; // 0x8
	private static DelegateBridge __Hotfix0__UpdateInternalAbilityAttachStatus; // 0x10
	private static DelegateBridge __Hotfix0__OnAbnormalFlagPossiblyChanged; // 0x18
	private static DelegateBridge __Hotfix0_OnRecycle; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x1b7f704 VA: 0x7594197704
	protected override Void DoAttach() { }
	// RVA: 0x1b7fb20 VA: 0x7594197b20
	protected override Void DoDetach() { }
	// RVA: 0x1b7f950 VA: 0x7594197950
	private Void _UpdateInternalAbilityAttachStatus(Boolean isManuallyAttached) { }
	// RVA: 0x1b7fcac VA: 0x7594197cac
	private Void _OnAbnormalFlagPossiblyChanged(AbnormalFlag abnormalFlag) { }
	// RVA: 0x1b7fd2c VA: 0x7594197d2c
	public override Void OnRecycle() { }
	// RVA: 0x1b7febc VA: 0x7594197ebc
	public Void .ctor() { }
	// RVA: 0x1b7ff30 VA: 0x7594197f30
	private Void <>xLuaBaseProxy_DoAttach() { }
	// RVA: 0x1b7ff34 VA: 0x7594197f34
	private Void <>xLuaBaseProxy_DoDetach() { }
	// RVA: 0x1b7ff38 VA: 0x7594197f38
	private Void <>xLuaBaseProxy_OnRecycle() { }
}
```