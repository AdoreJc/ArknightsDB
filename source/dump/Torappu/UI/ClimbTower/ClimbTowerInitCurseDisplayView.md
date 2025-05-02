# ClimbTowerInitCurseDisplayView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `SimpleLayoutContent _stepList`

- `SimpleLayoutContent _curseCardList`

- `Boolean m_hasInited`

- `ClimbTowerInitStepListAdapter m_stepAdapter`

- `CurseCardListAdapter m_cardListAdapter`

- `ClimbTowerInitCurseDisplayModel m_displayModel`


## Methods

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerInitCurseDisplayView : DataBinder`1
{
	private SimpleLayoutContent _stepList; // 0x20
	private SimpleLayoutContent _curseCardList; // 0x28
	private const Int32 TOTAL_STEP_COUNT; // 0x0
	private const Int32 CURRENT_STEP_VAL; // 0x0
	private Boolean m_hasInited; // 0x30
	private ClimbTowerInitStepListAdapter m_stepAdapter; // 0x38
	private CurseCardListAdapter m_cardListAdapter; // 0x40
	private ClimbTowerInitCurseDisplayModel m_displayModel; // 0x48
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2ca8534 VA: 0x75952c0534
	public override Void OnValueChanged(ClimbTowerInitCurseDisplayProp property) { }
	// RVA: 0x2ca85fc VA: 0x75952c05fc
	private Void _InitIfNot() { }
	// RVA: 0x2ca88b8 VA: 0x75952c08b8
	public Void .ctor() { }
}
```