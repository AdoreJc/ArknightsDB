# ColorGrading

**Namespace:** `Torappu.Battle.Opera`


## Fields

- `Single _fadeInTime`

- `Single _keepTime`

- `Single _fadeOutTime`


## Methods

- `Void <>xLuaBaseProxy_OnCompleted()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Opera
public class ColorGrading : OperaNode
{
	private Single _fadeInTime; // 0x14
	private Single _keepTime; // 0x18
	private Single _fadeOutTime; // 0x1c
	private static DelegateBridge __Hotfix0_get_postProcessType; // 0x0
	private static DelegateBridge __Hotfix0_DoExecute; // 0x8
	private static DelegateBridge __Hotfix0_OnCompleted; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override PostprocessMask postProcessType { get; }

	// RVA: 0x1c5f53c VA: 0x759427753c
	public override PostprocessMask get_postProcessType() { }
	// RVA: 0x1c5f5a4 VA: 0x75942775a4
	protected override Void DoExecute() { }
	// RVA: 0x1c5fab0 VA: 0x7594277ab0
	public override Void OnCompleted() { }
	// RVA: 0x1c5fb4c VA: 0x7594277b4c
	public Void .ctor() { }
	// RVA: 0x1c5fbb8 VA: 0x7594277bb8
	private Void <>xLuaBaseProxy_OnCompleted() { }
}
```