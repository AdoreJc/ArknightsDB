# ActMultiV3SquadClassColVirtualView

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `GameObject m_viewPrefab`

- `Single m_viewWidth`

- `ActMultiV3IdentityType m_identityType`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3SquadClassColVirtualView : VirtualView`1
{
	private GameObject m_viewPrefab; // 0x20
	private Single m_viewWidth; // 0x28
	private List`1 m_charList; // 0x30
	private ActMultiV3IdentityType m_identityType; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GetPrefab; // 0x8
	private static DelegateBridge __Hotfix0_GetPreferSize; // 0x10
	private static DelegateBridge __Hotfix0_OnViewAttached; // 0x18
	private static DelegateBridge __Hotfix0_OnViewDetached; // 0x20


	// RVA: 0x3136df0 VA: 0x759574edf0
	public Void .ctor(Param param) { }
	// RVA: 0x3136ec4 VA: 0x759574eec4
	public override GameObject GetPrefab() { }
	// RVA: 0x3136f2c VA: 0x759574ef2c
	public override Single GetPreferSize() { }
	// RVA: 0x3136f94 VA: 0x759574ef94
	protected override Void OnViewAttached() { }
	// RVA: 0x3137190 VA: 0x759574f190
	protected override Void OnViewDetached() { }
}
```