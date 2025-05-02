# Act1LockFinalItemView

**Namespace:** `Torappu.Activity.Act1Lock.UI`


## Fields

- `CanvasGroup _commonPartCanvasGroup`

- `LayoutElement _layoutElement`

- `GameObject _activePart`

- `GameObject _activeExpandPart`

- `GameObject _inactivePart`

- `SimpleLayoutContent _charList1`

- `SimpleLayoutContent _charList2`

- `UIAnimationLocation _animation`

- `Image _imgRegion`

- `Image _imgStatus`

- `Image _imgEnemyIcon`

- `Text _textCaption`

- `InterlockSquadModel m_interlockModel`

- `Int32 m_position`

- `Boolean m_hasInited`

- `InterlockCharItemAdapter m_charListAdapter1`

- `InterlockCharItemAdapter m_charListAdapter2`

- `Tween m_expandTween`


## Properties

- `Single itemWidth`


## Methods

- `Void set_onExpandAction(Action`2)`

- `Void set_onCancelAction(Action`1)`

- `Void set_onJumpAction(Action`1)`

- `Single get_itemWidth()`

- `Void Render(Int32, InterlockSquadModel, String)`

- `Void PlayExpandAnim(Action`2)`

- `Void _CleanAnimTween()`

- `Void _InitIfNot()`

- `Void OnBtnExpand()`

- `Void OnBtnJump()`

- `Void OnBtnCancel()`

- `Void <OnBtnExpand>b__38_0(Int32, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Lock.UI
public class Act1LockFinalItemView : MonoBehaviour, IHotfixable
{
	private CanvasGroup _commonPartCanvasGroup; // 0x18
	private LayoutElement _layoutElement; // 0x20
	private GameObject _activePart; // 0x28
	private GameObject _activeExpandPart; // 0x30
	private GameObject _inactivePart; // 0x38
	private SimpleLayoutContent _charList1; // 0x40
	private SimpleLayoutContent _charList2; // 0x48
	private UIAnimationLocation _animation; // 0x50
	private Image _imgRegion; // 0x60
	private Sprite[] _regionSpriteList; // 0x68
	private Image _imgStatus; // 0x70
	private Image _imgEnemyIcon; // 0x78
	private Sprite[] _statusSpriteList; // 0x80
	private Text _textCaption; // 0x88
	private Action`2 <onExpandAction>k__BackingField; // 0x90
	private Action`1 <onCancelAction>k__BackingField; // 0x98
	private Action`1 <onJumpAction>k__BackingField; // 0xa0
	private InterlockSquadModel m_interlockModel; // 0xa8
	private Int32 m_position; // 0xb0
	private Boolean m_hasInited; // 0xb4
	private InterlockCharItemAdapter m_charListAdapter1; // 0xb8
	private InterlockCharItemAdapter m_charListAdapter2; // 0xc0
	private Tween m_expandTween; // 0xc8
	private static DelegateBridge __Hotfix0_get_onExpandAction; // 0x0
	private static DelegateBridge __Hotfix0_set_onExpandAction; // 0x8
	private static DelegateBridge __Hotfix0_get_onCancelAction; // 0x10
	private static DelegateBridge __Hotfix0_set_onCancelAction; // 0x18
	private static DelegateBridge __Hotfix0_get_onJumpAction; // 0x20
	private static DelegateBridge __Hotfix0_set_onJumpAction; // 0x28
	private static DelegateBridge __Hotfix0_get_itemWidth; // 0x30
	private static DelegateBridge __Hotfix0_Render; // 0x38
	private static DelegateBridge __Hotfix0_PlayExpandAnim; // 0x40
	private static DelegateBridge __Hotfix0__CleanAnimTween; // 0x48
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x50
	private static DelegateBridge __Hotfix0_OnBtnExpand; // 0x58
	private static DelegateBridge __Hotfix0_OnBtnJump; // 0x60
	private static DelegateBridge __Hotfix0_OnBtnCancel; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70

	private Action`2 onExpandAction { get; set; }
	private Action`1 onCancelAction { get; set; }
	private Action`1 onJumpAction { get; set; }
	public Single itemWidth { get; }

	// RVA: 0x33ad650 VA: 0x75959c5650
	private Action`2 get_onExpandAction() { }
	// RVA: 0x33acfcc VA: 0x75959c4fcc
	public Void set_onExpandAction(Action`2 value) { }
	// RVA: 0x33ad6b8 VA: 0x75959c56b8
	private Action`1 get_onCancelAction() { }
	// RVA: 0x33ad050 VA: 0x75959c5050
	public Void set_onCancelAction(Action`1 value) { }
	// RVA: 0x33ad720 VA: 0x75959c5720
	private Action`1 get_onJumpAction() { }
	// RVA: 0x33ad0d4 VA: 0x75959c50d4
	public Void set_onJumpAction(Action`1 value) { }
	// RVA: 0x33acc54 VA: 0x75959c4c54
	public Single get_itemWidth() { }
	// RVA: 0x33ad158 VA: 0x75959c5158
	public Void Render(Int32 position, InterlockSquadModel interlockModel, String finalStageId) { }
	// RVA: 0x33ad94c VA: 0x75959c594c
	public Void PlayExpandAnim(Action`2 callback) { }
	// RVA: 0x33ad8b8 VA: 0x75959c58b8
	private Void _CleanAnimTween() { }
	// RVA: 0x33ad788 VA: 0x75959c5788
	private Void _InitIfNot() { }
	// RVA: 0x33adbb4 VA: 0x75959c5bb4
	public Void OnBtnExpand() { }
	// RVA: 0x33adc80 VA: 0x75959c5c80
	public Void OnBtnJump() { }
	// RVA: 0x33add38 VA: 0x75959c5d38
	public Void OnBtnCancel() { }
	// RVA: 0x33addd8 VA: 0x75959c5dd8
	public Void .ctor() { }
	// RVA: 0x33ade48 VA: 0x75959c5e48
	private Void <OnBtnExpand>b__38_0(Int32 position, Boolean targetStatus) { }
}
```