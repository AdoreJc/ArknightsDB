# GroceryHomeLaunchGoodGroupView

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `GameObject _panelCurr`

- `GameObject _panelFuture`

- `GameObject _panelPass`

- `GameObject _panelStageLocked`

- `Text _textGoodNameDesc`

- `Text _textStageUnlockDesc`

- `UIStateFinder m_stateFinder`


## Methods

- `Void Render(GroceryHomeLaunchPanelGoodGroupModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GroceryHomeLaunchGoodGroupView : MonoBehaviour, IHotfixable
{
	private const Single ALPHA_NOT_CURRENT; // 0x0
	private const Single ALPHA_CURRENT; // 0x0
	private GameObject _panelCurr; // 0x18
	private GameObject _panelFuture; // 0x20
	private GameObject _panelPass; // 0x28
	private GameObject _panelStageLocked; // 0x30
	private Text[] _textDateDesc; // 0x38
	private Text _textGoodNameDesc; // 0x40
	private CanvasGroup[] _canvasContent; // 0x48
	private Text _textStageUnlockDesc; // 0x50
	private Image[] _goodIcon; // 0x58
	private UIStateFinder m_stateFinder; // 0x60
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x285ff28 VA: 0x7594e77f28
	public Void Render(GroceryHomeLaunchPanelGoodGroupModel groupModel) { }
	// RVA: 0x2860220 VA: 0x7594e78220
	public Void .ctor() { }
}
```