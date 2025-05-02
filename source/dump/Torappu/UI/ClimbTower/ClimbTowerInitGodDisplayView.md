# ClimbTowerInitGodDisplayView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `SimpleLayoutContent _stepList`

- `SimpleLayoutContent _godCardList`

- `Boolean m_hasInited`

- `ClimbTowerInitStepListAdapter m_stepAdapter`

- `ClimbTowerInitGodDisplayModel m_displayModel`

- `Adapter m_godCardListAdapter`


## Methods

- `Void set_onItemClick(Action`1)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerInitGodDisplayView : DataBinder`1
{
	private SimpleLayoutContent _stepList; // 0x20
	private SimpleLayoutContent _godCardList; // 0x28
	private Boolean m_hasInited; // 0x30
	private ClimbTowerInitStepListAdapter m_stepAdapter; // 0x38
	private ClimbTowerInitGodDisplayModel m_displayModel; // 0x40
	private Adapter m_godCardListAdapter; // 0x48
	private Action`1 <onItemClick>k__BackingField; // 0x50
	private static DelegateBridge __Hotfix0_get_onItemClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onItemClick; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action`1 onItemClick { get; set; }

	// RVA: 0x2cab974 VA: 0x75952c3974
	private Action`1 get_onItemClick() { }
	// RVA: 0x2ca9864 VA: 0x75952c1864
	public Void set_onItemClick(Action`1 value) { }
	// RVA: 0x2cab9dc VA: 0x75952c39dc
	public override Void OnValueChanged(ClimbTowerInitGodDisplayProp property) { }
	// RVA: 0x2cabaf4 VA: 0x75952c3af4
	private Void _InitIfNot() { }
	// RVA: 0x2cabca8 VA: 0x75952c3ca8
	public Void .ctor() { }
}
```