# AssistReportManuPerItem

**Namespace:** `Torappu.Building.UI.Assist`


## Fields

- `Image _itemIcon`

- `Text _itemName`

- `Text _itemCount`

- `Text _hourCount`

- `Single _countLabelPosAdjustWeight`

- `Single _countLabelPosAdjustBias`

- `Single m_countLabelXPos`

- `RectTransform m_countLabelRect`


## Methods

- `Void Render(UIItemViewModel, BuildingManuFactureItemReport)`

- `Void Awake()`

- `Void Update()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Assist
public class AssistReportManuPerItem : MonoBehaviour
{
	private Image _itemIcon; // 0x18
	private Text _itemName; // 0x20
	private Text _itemCount; // 0x28
	private Text _hourCount; // 0x30
	private Single _countLabelPosAdjustWeight; // 0x38
	private Single _countLabelPosAdjustBias; // 0x3c
	private Single m_countLabelXPos; // 0x40
	private RectTransform m_countLabelRect; // 0x48


	// RVA: 0x3e34a5c VA: 0x759644ca5c
	public Void Render(UIItemViewModel itemViewModel, BuildingManuFactureItemReport report) { }
	// RVA: 0x3e34c2c VA: 0x759644cc2c
	private Void Awake() { }
	// RVA: 0x3e34d10 VA: 0x759644cd10
	private Void Update() { }
	// RVA: 0x3e34e10 VA: 0x759644ce10
	public Void .ctor() { }
}
```