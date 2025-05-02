# PauseGame

**Namespace:** `Torappu.Battle.Opera`


## Fields

- `BattlePauseKey _pauseKey`

- `Boolean _isPause`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Opera
public class PauseGame : OperaNode
{
	private BattlePauseKey _pauseKey; // 0x14
	private Boolean _isPause; // 0x18
	private static DelegateBridge __Hotfix0_get_postProcessType; // 0x0
	private static DelegateBridge __Hotfix0_DoExecute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override PostprocessMask postProcessType { get; }

	// RVA: 0x1c6201c VA: 0x759427a01c
	public override PostprocessMask get_postProcessType() { }
	// RVA: 0x1c62080 VA: 0x759427a080
	protected override Void DoExecute() { }
	// RVA: 0x1c62114 VA: 0x759427a114
	public Void .ctor() { }
}
```