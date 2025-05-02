# LiteCircleRange

**Namespace:** `Torappu.Battle`


## Methods

- `Boolean <>xLuaBaseProxy_CheckTargetIn(ILocatable)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class LiteCircleRange : CircleRange
{
	private static DelegateBridge __Hotfix0_FetchColliders; // 0x0
	private static DelegateBridge __Hotfix0_DoFindTargets_DISPOSE; // 0x8
	private static DelegateBridge __Hotfix0_CheckTargetIn; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1b9193c VA: 0x75941a993c
	protected override Collider2D[] FetchColliders(Options options) { }
	// RVA: 0x1b91a08 VA: 0x75941a9a08
	protected override ReusableList`1 DoFindTargets_DISPOSE(Vector2 mapPos, TargetOptions options, Func`2 validator) { }
	// RVA: 0x1b91ff0 VA: 0x75941a9ff0
	public override Boolean CheckTargetIn(ILocatable target) { }
	// RVA: 0x1b921bc VA: 0x75941aa1bc
	public Void .ctor() { }
	// RVA: 0x1b92228 VA: 0x75941aa228
	private Collider2D[] <>xLuaBaseProxy_FetchColliders(Options P0) { }
	// RVA: 0x1b92254 VA: 0x75941aa254
	private ReusableList`1 <>xLuaBaseProxy_DoFindTargets_DISPOSE(Vector2 P0, TargetOptions P1, Func`2 P2) { }
	// RVA: 0x1b922ac VA: 0x75941aa2ac
	private Boolean <>xLuaBaseProxy_CheckTargetIn(ILocatable P0) { }
}
```