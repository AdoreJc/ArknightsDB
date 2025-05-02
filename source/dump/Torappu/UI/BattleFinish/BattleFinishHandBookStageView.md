# BattleFinishHandBookStageView

**Namespace:** `Torappu.UI.BattleFinish`


## Fields

- `Text _textName`

- `BattleFinishRankGroup _rankGroup`

- `BattleFinishIllustView _illustView`

- `SimpleLayoutContent _dropItemsContent`

- `GameObject _dropListGo`

- `Boolean m_isAnim`

- `Action <onClick>k__BackingField`


## Properties

- `Action onClick`


## Methods

- `Void set_onClick(Action)`

- `Action get_onClick()`

- `IEnumerator RenderViewAysnc(BattleFinishHandBookStageViewModel)`

- `Void EventOnPageClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BattleFinish
public class BattleFinishHandBookStageView : MonoBehaviour, IHotfixable
{
	private const Single ITEM_DISPLAY_DELAY; // 0x0
	private Text _textName; // 0x18
	private BattleFinishRankGroup _rankGroup; // 0x20
	private BattleFinishIllustView _illustView; // 0x28
	private SimpleLayoutContent _dropItemsContent; // 0x30
	private GameObject _dropListGo; // 0x38
	private Boolean m_isAnim; // 0x40
	private Action <onClick>k__BackingField; // 0x48
	private static DelegateBridge __Hotfix0_set_onClick; // 0x0
	private static DelegateBridge __Hotfix0_get_onClick; // 0x8
	private static DelegateBridge __Hotfix0_RenderViewAysnc; // 0x10
	private static DelegateBridge __Hotfix0_EventOnPageClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action onClick { get; set; }

	// RVA: 0x2e8ec80 VA: 0x75954a6c80
	public Void set_onClick(Action value) { }
	// RVA: 0x2e8ed04 VA: 0x75954a6d04
	private Action get_onClick() { }
	// RVA: 0x2e8ed6c VA: 0x75954a6d6c
	public IEnumerator RenderViewAysnc(BattleFinishHandBookStageViewModel battleFinishModel) { }
	// RVA: 0x2e8ee64 VA: 0x75954a6e64
	public Void EventOnPageClicked() { }
	// RVA: 0x2e8ef14 VA: 0x75954a6f14
	public Void .ctor() { }
}
```