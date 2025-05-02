# Act1ArcadeBadgeBookDetailProgressItemView

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `GameObject _itemPanel`

- `GameObject _splitPanel`

- `CanvasGroup _selectedGroup`

- `Boolean m_hasInited`

- `FadeSwitchTween m_selectedTween`


## Methods

- `Void Render(Act1ArcadeBadgeBookItemViewModel, Boolean, Boolean)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Act1ArcadeBadgeBookDetailProgressItemView : MonoBehaviour, IHotfixable
{
	private GameObject _itemPanel; // 0x18
	private GameObject _splitPanel; // 0x20
	private CanvasGroup _selectedGroup; // 0x28
	private Boolean m_hasInited; // 0x30
	private FadeSwitchTween m_selectedTween; // 0x38
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x33f227c VA: 0x7595a0a27c
	public Void Render(Act1ArcadeBadgeBookItemViewModel item, Boolean selected, Boolean initShow) { }
	// RVA: 0x33f236c VA: 0x7595a0a36c
	private Void _InitIfNot() { }
	// RVA: 0x33f243c VA: 0x7595a0a43c
	public Void .ctor() { }
}
```