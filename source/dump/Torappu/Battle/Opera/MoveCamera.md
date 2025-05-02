# MoveCamera

**Namespace:** `Torappu.Battle.Opera`


## Fields

- `Vector3 _offset`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Opera
public class MoveCamera : OperaNode
{
	private Vector3 _offset; // 0x14
	private static DelegateBridge __Hotfix0_get_postProcessType; // 0x0
	private static DelegateBridge __Hotfix0_DoExecute; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override PostprocessMask postProcessType { get; }

	// RVA: 0x1c5f3d4 VA: 0x75942773d4
	public override PostprocessMask get_postProcessType() { }
	// RVA: 0x1c5f438 VA: 0x7594277438
	protected override Void DoExecute() { }
	// RVA: 0x1c5f4d0 VA: 0x75942774d0
	public Void .ctor() { }
}
```