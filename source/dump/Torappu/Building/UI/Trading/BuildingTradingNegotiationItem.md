# BuildingTradingNegotiationItem

**Namespace:** `Torappu.Building.UI.Trading`


## Fields

- `TradingOrderViewType _type`

- `Boolean m_isInited`

- `Boolean m_isSelected`


## Methods

- `Void set_onItemClicked(Action`1)`

- `Void Render(TradingOrderViewType)`

- `Void EventOnItemClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Trading
public class BuildingTradingNegotiationItem : MonoBehaviour
{
	private TradingOrderViewType _type; // 0x18
	private GameObject[] _selectedObjs; // 0x20
	private GameObject[] _unselectedObjs; // 0x28
	private Boolean m_isInited; // 0x30
	private Boolean m_isSelected; // 0x31
	private Action`1 <onItemClicked>k__BackingField; // 0x38

	private Action`1 onItemClicked { get; set; }

	// RVA: 0x3d84860 VA: 0x759639c860
	private Action`1 get_onItemClicked() { }
	// RVA: 0x3d84868 VA: 0x759639c868
	public Void set_onItemClicked(Action`1 value) { }
	// RVA: 0x3d8191c VA: 0x759639991c
	public Void Render(TradingOrderViewType type) { }
	// RVA: 0x3d84870 VA: 0x759639c870
	public Void EventOnItemClicked() { }
	// RVA: 0x3d84890 VA: 0x759639c890
	public Void .ctor() { }
}
```