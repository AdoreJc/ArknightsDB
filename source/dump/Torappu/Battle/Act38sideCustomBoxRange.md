# Act38sideCustomBoxRange

**Namespace:** `Torappu.Battle`


## Fields

- `String _envSystemKey`

- `String m_rangeId`

- `RangeData m_rangeData`


## Methods

- `Void <>xLuaBaseProxy_OnInit(Options)`

- `Void <>xLuaBaseProxy_InitCollidersIfNot(Options)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class Act38sideCustomBoxRange : AutoLoadBoxRange
{
	private String _envSystemKey; // 0x40
	private String m_rangeId; // 0x48
	private RangeData m_rangeData; // 0x50
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_InitCollidersIfNot; // 0x8
	private static DelegateBridge __Hotfix0_FetchColliders; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x1b8a458 VA: 0x75941a2458
	protected override Void OnInit(Options options) { }
	// RVA: 0x1b8a674 VA: 0x75941a2674
	protected override Void InitCollidersIfNot(Options options) { }
	// RVA: 0x1b8a894 VA: 0x75941a2894
	protected override Collider2D[] FetchColliders(Options options) { }
	// RVA: 0x1b8b06c VA: 0x75941a306c
	public Void .ctor() { }
	// RVA: 0x1b8b174 VA: 0x75941a3174
	private Void <>xLuaBaseProxy_OnInit(Options P0) { }
	// RVA: 0x1b8b1a0 VA: 0x75941a31a0
	private Void <>xLuaBaseProxy_InitCollidersIfNot(Options P0) { }
	// RVA: 0x1b8b274 VA: 0x75941a3274
	private Collider2D[] <>xLuaBaseProxy_FetchColliders(Options P0) { }
}
```