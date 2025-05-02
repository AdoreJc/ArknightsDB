# BuildingTradingGainingOrderView

**Namespace:** `Torappu.Building.UI.Trading`


## Fields

- `GameObject _panelWork`

- `GameObject _panelPause`

- `Text _textRemainTime`

- `FillProgressBar _progress`

- `Color _colorLocked`

- `UIColorGraphic _graphicLaborAccelBtn`

- `GameObject _panelLaborAccelLocked`

- `Action onLaborAccelClicked`

- `TradingGainOrderSnapshot m_snapshot`

- `CountDownTask m_countDown`


## Methods

- `Void Render(TradingGainOrderSnapshot)`

- `Void _UpdateCountDown()`

- `Void _RenderOnCountDownTick()`

- `Void Update()`

- `Void EventOnLaborAccelClicked()`

- `Void <_UpdateCountDown>b__11_0(TickValue)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Trading
public class BuildingTradingGainingOrderView : MonoBehaviour
{
	private GameObject _panelWork; // 0x18
	private GameObject _panelPause; // 0x20
	private Text _textRemainTime; // 0x28
	private FillProgressBar _progress; // 0x30
	private Color _colorLocked; // 0x38
	private UIColorGraphic _graphicLaborAccelBtn; // 0x48
	private GameObject _panelLaborAccelLocked; // 0x50
	public Action onLaborAccelClicked; // 0x58
	private TradingGainOrderSnapshot m_snapshot; // 0x60
	private CountDownTask m_countDown; // 0x88


	// RVA: 0x3d84288 VA: 0x759639c288
	public Void Render(TradingGainOrderSnapshot snapshot) { }
	// RVA: 0x3d84478 VA: 0x759639c478
	private Void _UpdateCountDown() { }
	// RVA: 0x3d845c4 VA: 0x759639c5c4
	private Void _RenderOnCountDownTick() { }
	// RVA: 0x3d846a4 VA: 0x759639c6a4
	private Void Update() { }
	// RVA: 0x3d846b8 VA: 0x759639c6b8
	public Void EventOnLaborAccelClicked() { }
	// RVA: 0x3d847e4 VA: 0x759639c7e4
	public Void .ctor() { }
	// RVA: 0x3d8485c VA: 0x759639c85c
	private Void <_UpdateCountDown>b__11_0(TickValue _) { }
}
```