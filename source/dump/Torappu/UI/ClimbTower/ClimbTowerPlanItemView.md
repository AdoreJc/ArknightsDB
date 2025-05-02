# ClimbTowerPlanItemView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `GameObject _selectGo`

- `Text _textName`

- `Text _textDesc`

- `UIAtlasImage _logoPlan`

- `UIAtlasObject _logoAtlas`

- `Boolean _freeState`


## Methods

- `Void set_onPlanClick(Action`1)`

- `Void Render(Boolean)`

- `Void OnPlanClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerPlanItemView : MonoBehaviour, IHotfixable
{
	private GameObject _selectGo; // 0x18
	private Text _textName; // 0x20
	private Text _textDesc; // 0x28
	private UIAtlasImage _logoPlan; // 0x30
	private UIAtlasObject _logoAtlas; // 0x38
	private Boolean _freeState; // 0x40
	private Action`1 <onPlanClick>k__BackingField; // 0x48
	private static DelegateBridge __Hotfix0_get_onPlanClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onPlanClick; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_OnPlanClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action`1 onPlanClick { get; set; }

	// RVA: 0x2c8d038 VA: 0x75952a5038
	private Action`1 get_onPlanClick() { }
	// RVA: 0x2c8d0a0 VA: 0x75952a50a0
	public Void set_onPlanClick(Action`1 value) { }
	// RVA: 0x2c8d124 VA: 0x75952a5124
	public Void Render(Boolean isFree) { }
	// RVA: 0x2c8d2f4 VA: 0x75952a52f4
	public Void OnPlanClick() { }
	// RVA: 0x2c8d394 VA: 0x75952a5394
	public Void .ctor() { }
}
```