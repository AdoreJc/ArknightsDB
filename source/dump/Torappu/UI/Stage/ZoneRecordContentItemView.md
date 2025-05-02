# ZoneRecordContentItemView

**Namespace:** `Torappu.UI.Stage`


## Fields

- `TwoStateToggle _toggle`

- `Text _stageId`

- `UIColorGraphic _colorGraphic`

- `Color _grayColor`

- `String m_cachedRecordId`

- `Boolean m_isInited`

- `Color NORMAL_COLOR`


## Methods

- `Void Render(ZoneRecordViewModel, Boolean)`

- `Void _InitIfNot(ZoneRecordViewModel)`

- `Void _OnToggle(State)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class ZoneRecordContentItemView : MonoBehaviour, IHotfixable
{
	private TwoStateToggle _toggle; // 0x18
	private Text _stageId; // 0x20
	private UIColorGraphic _colorGraphic; // 0x28
	private Color _grayColor; // 0x30
	public Action`1 onEvent; // 0x40
	private String m_cachedRecordId; // 0x48
	private Boolean m_isInited; // 0x50
	private Color NORMAL_COLOR; // 0x54
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__OnToggle; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2fc02e0 VA: 0x75955d82e0
	public Void Render(ZoneRecordViewModel viewModel, Boolean selected) { }
	// RVA: 0x2fc0464 VA: 0x75955d8464
	private Void _InitIfNot(ZoneRecordViewModel viewModel) { }
	// RVA: 0x2fc0520 VA: 0x75955d8520
	private Void _OnToggle(State state) { }
	// RVA: 0x2fc05c0 VA: 0x75955d85c0
	public Void .ctor() { }
}
```