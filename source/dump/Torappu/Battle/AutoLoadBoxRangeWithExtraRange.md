# AutoLoadBoxRangeWithExtraRange

**Namespace:** `Torappu.Battle`


## Fields

- `String _extraRangeId`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class AutoLoadBoxRangeWithExtraRange : AutoLoadBoxRange
{
	private String _extraRangeId; // 0x40
	private String[] m_rangeIds; // 0x48
	private static DelegateBridge __Hotfix0_FetchColliders; // 0x0
	private static DelegateBridge __Hotfix0_FetchCollidersByRangeIds; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x1b8cafc VA: 0x75941a4afc
	protected override Collider2D[] FetchColliders(Options options) { }
	// RVA: 0x1b8cc7c VA: 0x75941a4c7c
	private Collider2D[] FetchCollidersByRangeIds(String[] rangeIds, Options options) { }
	// RVA: 0x1b8cfc0 VA: 0x75941a4fc0
	public Void .ctor() { }
	// RVA: 0x1b8d068 VA: 0x75941a5068
	private Collider2D[] <>xLuaBaseProxy_FetchColliders(Options P0) { }
}
```