# ActMultiV3BattleFinishReportItemView

**Namespace:** `Torappu.Activity.ActMultiV3.BattleFinish`


## Fields

- `GameObject _iconSelectGO`

- `GameObject _iconUnselectGO`

- `GameObject _iconSelectFullGO`

- `Text _textName`

- `Text _textDesc`

- `ActMultiV3BattleFinishReportItemModel m_reportItemModel`


## Methods

- `Void set_onItemClick(Action`1)`

- `Void Render(ActMultiV3BattleFinishReportItemModel, Boolean, Boolean)`

- `Void EventOnItemClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3.BattleFinish
public class ActMultiV3BattleFinishReportItemView : MonoBehaviour, IHotfixable
{
	private GameObject _iconSelectGO; // 0x18
	private GameObject _iconUnselectGO; // 0x20
	private GameObject _iconSelectFullGO; // 0x28
	private Text _textName; // 0x30
	private Text _textDesc; // 0x38
	private ActMultiV3BattleFinishReportItemModel m_reportItemModel; // 0x40
	private Action`1 <onItemClick>k__BackingField; // 0x48
	private static DelegateBridge __Hotfix0_get_onItemClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onItemClick; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_EventOnItemClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action`1 onItemClick { get; set; }

	// RVA: 0x3181994 VA: 0x7595799994
	private Action`1 get_onItemClick() { }
	// RVA: 0x31819fc VA: 0x75957999fc
	public Void set_onItemClick(Action`1 value) { }
	// RVA: 0x3181a80 VA: 0x7595799a80
	public Void Render(ActMultiV3BattleFinishReportItemModel reportItemModel, Boolean isSelectMax, Boolean isSelect) { }
	// RVA: 0x3181c98 VA: 0x7595799c98
	public Void EventOnItemClick() { }
	// RVA: 0x3181db8 VA: 0x7595799db8
	public Void .ctor() { }
}
```