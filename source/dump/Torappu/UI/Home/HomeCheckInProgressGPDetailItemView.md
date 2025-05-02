# HomeCheckInProgressGPDetailItemView

**Namespace:** `Torappu.UI.Home`


## Fields

- `SimpleLayoutContent _content`

- `Text _textDay`

- `CanvasGroup _canvasGroupComplete`

- `GameObject _panelComplete`

- `GameObject _panelSplitLine`

- `Adapter m_adapter`

- `Boolean m_hasInited`


## Methods

- `Void Render(Int32, ProgressCheckInItem, Int32)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeCheckInProgressGPDetailItemView : MonoBehaviour, IHotfixable
{
	private const Single ALPHA_COMPLETE; // 0x0
	private const Single ALPHA_UNCOMPLETE; // 0x0
	private SimpleLayoutContent _content; // 0x18
	private Text _textDay; // 0x20
	private CanvasGroup _canvasGroupComplete; // 0x28
	private GameObject _panelComplete; // 0x30
	private GameObject _panelSplitLine; // 0x38
	private Adapter m_adapter; // 0x40
	private Boolean m_hasInited; // 0x48
	private List`1 m_rewardList; // 0x50
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x28308b4 VA: 0x7594e488b4
	public Void Render(Int32 index, ProgressCheckInItem model, Int32 currCheckInDay) { }
	// RVA: 0x2830a18 VA: 0x7594e48a18
	private Void _InitIfNot() { }
	// RVA: 0x2830b7c VA: 0x7594e48b7c
	public Void .ctor() { }
}
```