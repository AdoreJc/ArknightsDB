# RoguelikeDungeonZoneView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RectTransform _layerPrefab`

- `RectTransform _layerContainer`

- `Image _imageBackground`

- `CanvasGroup _canvasBkgBlur`

- `RectTransform _panelCursor`

- `Single _cursorTweenDuration`

- `Single _cursorTweenDistance`

- `RoguelikeDungeonZoneViewModel m_cacheModel`

- `Tween m_cursorTweener`

- `ShowSwitchTween m_showSwitchTween`

- `CanvasGroup m_canvasGroup`

- `StateTransitionParam m_currTransParam`

- `StateEngine m_bindStateEngine`

- `Boolean m_isShow`

- `Boolean m_hasPendingRenderEvent`


## Methods

- `Void set_onNodeClicked(Action`1)`

- `Void set_onZoneCreated(Action`1)`

- `Void _OnBeforeStateTransition(Object)`

- `Void _EventOnStateResume(Object)`

- `Void _EventOnStatePause(Object)`

- `Void Init(RoguelikeDungeonController)`

- `Void SetShow(Boolean, Boolean)`

- `RoguelikeDungeonNodeView GetViewByNode(RoguelikeDungeonNode)`

- `Void _CreateZone()`

- `RoguelikeDungeonNodeView _LoadDungeonNodePrefabWithTopicId(String)`

- `RectTransform _LoadDungeonLayerPrefabWithTopicId(String)`

- `Void _RenderZone()`

- `Void CleanNodeEffect()`

- `Void _RenderBackground()`

- `Void _PlayCursorAnimation()`

- `Boolean _NeedRender()`

- `Vector3 <_PlayCursorAnimation>b__42_0()`

- `Void <_PlayCursorAnimation>b__42_1(Vector3)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeDungeonZoneView : DataBinder`1
{
	private static readonly Type[] ENABLE_STATES; // 0x0
	private static readonly PlayerRoguelikePlayerEventType[] NO_RENDER_PENDING_EVENTS; // 0x8
	private const Single TWEEN_DURATION; // 0x0
	private RectTransform _layerPrefab; // 0x20
	private RectTransform _layerContainer; // 0x28
	private Image _imageBackground; // 0x30
	private CanvasGroup _canvasBkgBlur; // 0x38
	private RectTransform _panelCursor; // 0x40
	private Single _cursorTweenDuration; // 0x48
	private Single _cursorTweenDistance; // 0x4c
	private RoguelikeDungeonZoneViewModel m_cacheModel; // 0x50
	private Dictionary`2 m_views; // 0x58
	private Tween m_cursorTweener; // 0x60
	private ShowSwitchTween m_showSwitchTween; // 0x68
	private CanvasGroup m_canvasGroup; // 0x70
	private StateTransitionParam m_currTransParam; // 0x78
	private StateEngine m_bindStateEngine; // 0x80
	private Boolean m_isShow; // 0x88
	private Boolean m_hasPendingRenderEvent; // 0x89
	private Action`1 <onNodeClicked>k__BackingField; // 0x90
	private Action`1 <onZoneCreated>k__BackingField; // 0x98
	private static DelegateBridge __Hotfix0_get_onNodeClicked; // 0x10
	private static DelegateBridge __Hotfix0_set_onNodeClicked; // 0x18
	private static DelegateBridge __Hotfix0_get_onZoneCreated; // 0x20
	private static DelegateBridge __Hotfix0_set_onZoneCreated; // 0x28
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x30
	private static DelegateBridge __Hotfix0__OnBeforeStateTransition; // 0x38
	private static DelegateBridge __Hotfix0__EventOnStateResume; // 0x40
	private static DelegateBridge __Hotfix0__EventOnStatePause; // 0x48
	private static DelegateBridge __Hotfix0_Init; // 0x50
	private static DelegateBridge __Hotfix0_SetShow; // 0x58
	private static DelegateBridge __Hotfix0_GetViewByNode; // 0x60
	private static DelegateBridge __Hotfix0__CreateZone; // 0x68
	private static DelegateBridge __Hotfix0__LoadDungeonNodePrefabWithTopicId; // 0x70
	private static DelegateBridge __Hotfix0__LoadDungeonLayerPrefabWithTopicId; // 0x78
	private static DelegateBridge __Hotfix0__RenderZone; // 0x80
	private static DelegateBridge __Hotfix0_CleanNodeEffect; // 0x88
	private static DelegateBridge __Hotfix0__RenderBackground; // 0x90
	private static DelegateBridge __Hotfix0__PlayCursorAnimation; // 0x98
	private static DelegateBridge __Hotfix0__NeedRender; // 0xa0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa8

	public Action`1 onNodeClicked { get; set; }
	public Action`1 onZoneCreated { get; set; }

	// RVA: 0x2a113ac VA: 0x75950293ac
	public Action`1 get_onNodeClicked() { }
	// RVA: 0x2a11424 VA: 0x7595029424
	public Void set_onNodeClicked(Action`1 value) { }
	// RVA: 0x2a114b8 VA: 0x75950294b8
	public Action`1 get_onZoneCreated() { }
	// RVA: 0x2a11530 VA: 0x7595029530
	public Void set_onZoneCreated(Action`1 value) { }
	// RVA: 0x2a115c4 VA: 0x75950295c4
	public override Void OnValueChanged(RoguelikeDungeonZoneViewProperty property) { }
	// RVA: 0x2a12524 VA: 0x759502a524
	private Void _OnBeforeStateTransition(Object arg) { }
	// RVA: 0x2a12640 VA: 0x759502a640
	private Void _EventOnStateResume(Object arg) { }
	// RVA: 0x2a129f8 VA: 0x759502a9f8
	private Void _EventOnStatePause(Object arg) { }
	// RVA: 0x2a12c34 VA: 0x759502ac34
	public Void Init(RoguelikeDungeonController controller) { }
	// RVA: 0x2a12810 VA: 0x759502a810
	public Void SetShow(Boolean isShow, Boolean fastMode) { }
	// RVA: 0x2a12fa0 VA: 0x759502afa0
	public RoguelikeDungeonNodeView GetViewByNode(RoguelikeDungeonNode node) { }
	// RVA: 0x2a116b0 VA: 0x75950296b0
	private Void _CreateZone() { }
	// RVA: 0x2a1307c VA: 0x759502b07c
	private RoguelikeDungeonNodeView _LoadDungeonNodePrefabWithTopicId(String topicId) { }
	// RVA: 0x2a13208 VA: 0x759502b208
	private RectTransform _LoadDungeonLayerPrefabWithTopicId(String topicId) { }
	// RVA: 0x2a11f08 VA: 0x7595029f08
	private Void _RenderZone() { }
	// RVA: 0x2a1382c VA: 0x759502b82c
	public Void CleanNodeEffect() { }
	// RVA: 0x2a11bac VA: 0x7595029bac
	private Void _RenderBackground() { }
	// RVA: 0x2a13394 VA: 0x759502b394
	private Void _PlayCursorAnimation() { }
	// RVA: 0x2a11d98 VA: 0x7595029d98
	private Boolean _NeedRender() { }
	// RVA: 0x2a139c8 VA: 0x759502b9c8
	public Void .ctor() { }
	// RVA: 0x2a13b00 VA: 0x759502bb00
	private static Void .cctor() { }
	// RVA: 0x2a13d20 VA: 0x759502bd20
	private Vector3 <_PlayCursorAnimation>b__42_0() { }
	// RVA: 0x2a13d3c VA: 0x759502bd3c
	private Void <_PlayCursorAnimation>b__42_1(Vector3 val) { }
}
```