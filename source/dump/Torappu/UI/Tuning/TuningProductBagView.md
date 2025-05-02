# TuningProductBagView

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `TuningProductBagPanelView _viewPrefab`

- `Transform _viewHolder`

- `GameObject _bagDeco`

- `Boolean m_isInited`

- `TuningProductBagPanelView m_view`


## Methods

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningProductBagView : DataBinder`1
{
	private TuningProductBagPanelView _viewPrefab; // 0x20
	private Transform _viewHolder; // 0x28
	private GameObject _bagDeco; // 0x30
	private Boolean m_isInited; // 0x38
	private TuningProductBagPanelView m_view; // 0x40
	public Action`1 onSelectProductType; // 0x48
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2341dbc VA: 0x7594959dbc
	public override Void OnValueChanged(TuningProductBagProperty property) { }
	// RVA: 0x2341e94 VA: 0x7594959e94
	private Void _InitIfNot() { }
	// RVA: 0x2341fc0 VA: 0x7594959fc0
	public Void .ctor() { }
}
```