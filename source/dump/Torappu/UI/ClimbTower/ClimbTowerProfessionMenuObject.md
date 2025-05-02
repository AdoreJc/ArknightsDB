# ClimbTowerProfessionMenuObject

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `Boolean m_hasInited`

- `GetProfessionCharCount m_overrideGetProfessionCharCount`

- `ClimbTowerMenuViewModel m_cachedModel`


## Properties

- `GetProfessionCharCount getProfessionCharCount`


## Methods

- `GetProfessionCharCount get_getProfessionCharCount()`

- `Void _InitIfNot()`

- `Int32 _DefaultGetProfessionCharCount(ProfessionCategory)`

- `Void _RenderCount()`

- `Void UpdateButton(GetProfessionCharCount, Action`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerProfessionMenuObject : ClimbTowerMenuObject
{
	private List`1 _professionItems; // 0x20
	private Boolean m_hasInited; // 0x28
	private Dictionary`2 m_professionViewDict; // 0x30
	private GetProfessionCharCount m_overrideGetProfessionCharCount; // 0x38
	private Action`1 m_callback; // 0x40
	private ClimbTowerMenuViewModel m_cachedModel; // 0x48
	private static DelegateBridge __Hotfix0_get_getProfessionCharCount; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__DefaultGetProfessionCharCount; // 0x10
	private static DelegateBridge __Hotfix0__RenderCount; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge __Hotfix0_UpdateButton; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private GetProfessionCharCount getProfessionCharCount { get; }

	// RVA: 0x2c83a58 VA: 0x759529ba58
	private GetProfessionCharCount get_getProfessionCharCount() { }
	// RVA: 0x2c83be4 VA: 0x759529bbe4
	private Void _InitIfNot() { }
	// RVA: 0x2c83e00 VA: 0x759529be00
	private Int32 _DefaultGetProfessionCharCount(ProfessionCategory profession) { }
	// RVA: 0x2c83ebc VA: 0x759529bebc
	private Void _RenderCount() { }
	// RVA: 0x2c84104 VA: 0x759529c104
	public override Void Render(ClimbTowerMenuViewModel viewModel) { }
	// RVA: 0x2c82204 VA: 0x759529a204
	public Void UpdateButton(GetProfessionCharCount overrideGetProfessionCharCount, Action`1 callback) { }
	// RVA: 0x2c841ac VA: 0x759529c1ac
	public Void .ctor() { }
}
```