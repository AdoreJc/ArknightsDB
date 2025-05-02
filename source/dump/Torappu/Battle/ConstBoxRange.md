# ConstBoxRange

**Namespace:** `Torappu.Battle`


## Fields

- `String _rangeId`


## Methods

- `Void <>xLuaBaseProxy_InitCollidersIfNot(Options)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class ConstBoxRange : AutoLoadBoxRange
{
	private String _rangeId; // 0x40
	private static DelegateBridge __Hotfix0_FetchColliders; // 0x0
	private static DelegateBridge __Hotfix0_InitCollidersIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x1b8ebb4 VA: 0x75941a6bb4
	protected override Collider2D[] FetchColliders(Options options) { }
	// RVA: 0x1b8ec5c VA: 0x75941a6c5c
	protected override Void InitCollidersIfNot(Options options) { }
	// RVA: 0x1b8ed04 VA: 0x75941a6d04
	public Void .ctor() { }
	// RVA: 0x1b8ed70 VA: 0x75941a6d70
	private Collider2D[] <>xLuaBaseProxy_FetchColliders(Options P0) { }
	// RVA: 0x1b8ed9c VA: 0x75941a6d9c
	private Void <>xLuaBaseProxy_InitCollidersIfNot(Options P0) { }
}
```