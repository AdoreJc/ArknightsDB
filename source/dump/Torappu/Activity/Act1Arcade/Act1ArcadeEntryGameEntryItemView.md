# Act1ArcadeEntryGameEntryItemView

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `Text _scoreTxt`

- `Text _nameTxt`

- `Text _lockHintText`

- `Text _endHintText`

- `GameObject _normPanel`

- `GameObject _lockPanel`

- `GameObject _actClosePanel`

- `GameObject _newObj`

- `Act1ArcadeEntryGameEntryItemViewModel m_cachedViewModel`

- `UIStateFinder m_stateFinder`


## Methods

- `Void Render(Act1ArcadeEntryGameEntryItemViewModel)`

- `Void EventOnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Act1ArcadeEntryGameEntryItemView : MonoBehaviour, IHotfixable
{
	private const Int32 SCORE_NUM_DIGIT_CNT; // 0x0
	private Text _scoreTxt; // 0x18
	private Text _nameTxt; // 0x20
	private Text _lockHintText; // 0x28
	private Text _endHintText; // 0x30
	private GameObject _normPanel; // 0x38
	private GameObject _lockPanel; // 0x40
	private GameObject _actClosePanel; // 0x48
	private GameObject _newObj; // 0x50
	private Act1ArcadeEntryGameEntryItemViewModel m_cachedViewModel; // 0x58
	private UIStateFinder m_stateFinder; // 0x60
	public Action`1 notifyToastAction; // 0x70
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_EventOnClick; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x33fe710 VA: 0x7595a16710
	public Void Render(Act1ArcadeEntryGameEntryItemViewModel viewModel) { }
	// RVA: 0x33feb88 VA: 0x7595a16b88
	public Void EventOnClick() { }
	// RVA: 0x33fee44 VA: 0x7595a16e44
	public Void .ctor() { }
}
```