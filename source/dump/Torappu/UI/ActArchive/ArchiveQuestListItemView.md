# ArchiveQuestListItemView

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `GameObject _firstFarLinePanel`

- `GameObject _rightLinePanel`

- `GameObject _normalPanel`

- `GameObject _lockedPanel`

- `CanvasGroup _selectedGroup`

- `UIAnimationLocation _animTrackPointNew`

- `Graphic _selectGraphic`

- `Boolean m_hasInited`

- `UISwitchTween m_selectTween`

- `Tween m_trackPointTween`

- `Int32 m_cachedIndex`


## Methods

- `Void set_itemSelectEvent(Action`1)`

- `Void OnItemSelectEvent()`

- `Void Render(ViewParam, Boolean)`

- `Void _CheckIfPlayTrackPointLoopAnim(Boolean)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveQuestListItemView : MonoBehaviour, IHotfixable
{
	private GameObject _firstFarLinePanel; // 0x18
	private GameObject _rightLinePanel; // 0x20
	private GameObject _normalPanel; // 0x28
	private GameObject _lockedPanel; // 0x30
	private ArchiveQuestTypePanel[] _typePanels; // 0x38
	private CanvasGroup _selectedGroup; // 0x40
	private UIAnimationLocation _animTrackPointNew; // 0x48
	private Text[] _titleTexts; // 0x58
	private Graphic _selectGraphic; // 0x60
	private Boolean m_hasInited; // 0x68
	private UISwitchTween m_selectTween; // 0x70
	private Tween m_trackPointTween; // 0x78
	private Int32 m_cachedIndex; // 0x80
	private Action`1 <itemSelectEvent>k__BackingField; // 0x88
	private static DelegateBridge __Hotfix0_get_itemSelectEvent; // 0x0
	private static DelegateBridge __Hotfix0_set_itemSelectEvent; // 0x8
	private static DelegateBridge __Hotfix0_OnItemSelectEvent; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge __Hotfix0__CheckIfPlayTrackPointLoopAnim; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private Action`1 itemSelectEvent { get; set; }

	// RVA: 0x3073f14 VA: 0x759568bf14
	private Action`1 get_itemSelectEvent() { }
	// RVA: 0x3073f7c VA: 0x759568bf7c
	public Void set_itemSelectEvent(Action`1 value) { }
	// RVA: 0x3074000 VA: 0x759568c000
	public Void OnItemSelectEvent() { }
	// RVA: 0x30740a8 VA: 0x759568c0a8
	public Void Render(ViewParam param, Boolean initRender) { }
	// RVA: 0x3074440 VA: 0x759568c440
	private Void _CheckIfPlayTrackPointLoopAnim(Boolean isNew) { }
	// RVA: 0x307435c VA: 0x759568c35c
	private Void _InitIfNot() { }
	// RVA: 0x30745d0 VA: 0x759568c5d0
	public Void .ctor() { }
}
```