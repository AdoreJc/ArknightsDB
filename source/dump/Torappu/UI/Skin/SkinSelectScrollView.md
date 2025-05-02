# SkinSelectScrollView

**Namespace:** `Torappu.UI.Skin`


## Fields

- `Transform _viewContainer`

- `Transform _scrollItemContainer`

- `SkinSelectGroupView _groupView`

- `SkinSelectScrollItemView _scrollItemView`

- `SkinSelectDetailView _detailView`

- `Single m_state`

- `Boolean shopTitleBarFlag`

- `Vector2 m_startPoint`

- `Single m_startState`

- `Boolean m_dragFlag`

- `DateTime m_startClickTime`

- `Boolean m_isInited`

- `UIPage m_page`

- `UIStateFinder m_stateFinder`


## Methods

- `Void OnEnable()`

- `Void RefreshDetailView()`

- `Void InitData(List`1, String, UIPage)`

- `Void TweenToState(Single)`

- `Void OnBeginDrag(PointerEventData)`

- `Void OnDrag(PointerEventData)`

- `Void ApplyState(Single, Single)`

- `IEnumerator _ToState(Single, Single, Int32)`

- `IEnumerator _ToStateTrick(Single, Single, Int32, Action)`

- `Void OnEndDrag(PointerEventData)`

- `Void _DoEndDrag()`

- `Void _RefreshLeftView(Int32)`

- `Void SetSkinIllustsVisible(Boolean)`

- `SkinSelectViewModel _TryGetViewModel(Single)`

- `SkinSelectViewModel TryGetCurrentSkinModel()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Skin
public class SkinSelectScrollView : MonoBehaviour, IBeginDragHandler, IEventSystemHandler, IDragHandler, IEndDragHandler, IHotfixable
{
	private const String DEFAULT_SKIN_GROUP_ID; // 0x0
	private List`1 m_itemViewLists; // 0x18
	private Dictionary`2 m_commonViewList; // 0x20
	private Transform _viewContainer; // 0x28
	private Transform _scrollItemContainer; // 0x30
	private SkinSelectGroupView _groupView; // 0x38
	private SkinSelectScrollItemView _scrollItemView; // 0x40
	private SkinSelectDetailView _detailView; // 0x48
	public Single m_state; // 0x50
	public Boolean shopTitleBarFlag; // 0x54
	private Vector2 m_startPoint; // 0x58
	private Single m_startState; // 0x60
	private Boolean m_dragFlag; // 0x64
	private DateTime m_startClickTime; // 0x68
	public const Int32 MAX_ITEM_COUNT; // 0x0
	public const Int32 MID_ITEM_INDEX; // 0x0
	public const Int32 REMOVE_LENGTH; // 0x0
	public const Int32 DELTA_TIME; // 0x0
	public const Int32 DELTA_TIME_CLICK; // 0x0
	private Dictionary`2 m_viewLists; // 0x70
	private List`1 m_viewModelListCache; // 0x78
	private Boolean m_isInited; // 0x80
	private UIPage m_page; // 0x88
	private UIStateFinder m_stateFinder; // 0x90
	private static DelegateBridge __Hotfix0_OnEnable; // 0x0
	private static DelegateBridge __Hotfix0_RefreshDetailView; // 0x8
	private static DelegateBridge __Hotfix0_InitData; // 0x10
	private static DelegateBridge __Hotfix0_TweenToState; // 0x18
	private static DelegateBridge __Hotfix0_OnBeginDrag; // 0x20
	private static DelegateBridge __Hotfix0_OnDrag; // 0x28
	private static DelegateBridge __Hotfix0_ApplyState; // 0x30
	private static DelegateBridge __Hotfix0__ToState; // 0x38
	private static DelegateBridge __Hotfix0__ToStateTrick; // 0x40
	private static DelegateBridge __Hotfix0_OnEndDrag; // 0x48
	private static DelegateBridge __Hotfix0__DoEndDrag; // 0x50
	private static DelegateBridge __Hotfix0__RefreshLeftView; // 0x58
	private static DelegateBridge __Hotfix0_SetSkinIllustsVisible; // 0x60
	private static DelegateBridge __Hotfix0__TryGetViewModel; // 0x68
	private static DelegateBridge __Hotfix0_TryGetCurrentSkinModel; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78


	// RVA: 0x23d6bf8 VA: 0x75949eebf8
	private Void OnEnable() { }
	// RVA: 0x23d7024 VA: 0x75949ef024
	public Void RefreshDetailView() { }
	// RVA: 0x23d71a0 VA: 0x75949ef1a0
	public Void InitData(List`1 viewModelList, String focusSkinId, UIPage page) { }
	// RVA: 0x23d805c VA: 0x75949f005c
	public Void TweenToState(Single state) { }
	// RVA: 0x23d8ab8 VA: 0x75949f0ab8
	public Void OnBeginDrag(PointerEventData eventData) { }
	// RVA: 0x23d8b80 VA: 0x75949f0b80
	public Void OnDrag(PointerEventData eventData) { }
	// RVA: 0x23d7bc8 VA: 0x75949efbc8
	public Void ApplyState(Single state, Single trickState) { }
	// RVA: 0x23d70bc VA: 0x75949ef0bc
	private IEnumerator _ToState(Single startTarget, Single finishTarget, Int32 count) { }
	// RVA: 0x23d89bc VA: 0x75949f09bc
	private IEnumerator _ToStateTrick(Single startTarget, Single finishTarget, Int32 count, Action finishAction) { }
	// RVA: 0x23d8fc8 VA: 0x75949f0fc8
	public Void OnEndDrag(PointerEventData eventData) { }
	// RVA: 0x23d6c7c VA: 0x75949eec7c
	private Void _DoEndDrag() { }
	// RVA: 0x23d7588 VA: 0x75949ef588
	private Void _RefreshLeftView(Int32 state) { }
	// RVA: 0x23d9044 VA: 0x75949f1044
	public Void SetSkinIllustsVisible(Boolean isVisible) { }
	// RVA: 0x23d8c70 VA: 0x75949f0c70
	private SkinSelectViewModel _TryGetViewModel(Single index) { }
	// RVA: 0x23d9148 VA: 0x75949f1148
	public SkinSelectViewModel TryGetCurrentSkinModel() { }
	// RVA: 0x23d91b4 VA: 0x75949f11b4
	public Void .ctor() { }
}
```