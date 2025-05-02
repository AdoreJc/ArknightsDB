# BuildingWorkshopBonusView

**Namespace:** `Torappu.Building.UI.Workshop`


## Fields

- `SimpleLayoutContent _listView`

- `Adapter m_adapter`


## Methods

- `Void UpdateStatus(IWorkshopSession)`

- `Void _UpdateBonusFromPlayerData(IWorkshopSession)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Workshop
public class BuildingWorkshopBonusView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _listView; // 0x18
	private Adapter m_adapter; // 0x20
	private List`1 m_bonusList; // 0x28
	private static DelegateBridge __Hotfix0_UpdateStatus; // 0x0
	private static DelegateBridge __Hotfix0__UpdateBonusFromPlayerData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3d6bd20 VA: 0x7596383d20
	public Void UpdateStatus(IWorkshopSession curSession) { }
	// RVA: 0x3d6be28 VA: 0x7596383e28
	private Void _UpdateBonusFromPlayerData(IWorkshopSession curSession) { }
	// RVA: 0x3d6c2b0 VA: 0x75963842b0
	public Void .ctor() { }
}
```