# SixStarRuneSelectRuneGroupView

**Namespace:** `Torappu.UI.Stage`


## Fields

- `CanvasGroup _canvasTitle`

- `Text _textLevel`

- `SimpleLayoutContent _content`

- `GameObject _panelComplete`

- `GameObject _panelUncomplete`

- `SixStarRuneSelectGroupStatus m_cachedStatus`

- `Adapter m_adapter`

- `Boolean m_hasInited`


## Methods

- `Void Render(SixStarRuneSelectGroupViewModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class SixStarRuneSelectRuneGroupView : MonoBehaviour, IHotfixable
{
	private const Single ALPHA_LOCKED; // 0x0
	private const Single ALPHA_UNLOCK; // 0x0
	private CanvasGroup _canvasTitle; // 0x18
	private GameObject[] _panelUnselected; // 0x20
	private Text _textLevel; // 0x28
	private SimpleLayoutContent _content; // 0x30
	private GameObject _panelComplete; // 0x38
	private GameObject _panelUncomplete; // 0x40
	private List`1 m_cachedRuneModel; // 0x48
	private SixStarRuneSelectGroupStatus m_cachedStatus; // 0x50
	private Adapter m_adapter; // 0x58
	private Boolean m_hasInited; // 0x60
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2f4f5f4 VA: 0x75955675f4
	public Void Render(SixStarRuneSelectGroupViewModel model) { }
	// RVA: 0x2f4f7a4 VA: 0x75955677a4
	private Void _InitIfNot() { }
	// RVA: 0x2f4f908 VA: 0x7595567908
	public Void .ctor() { }
}
```