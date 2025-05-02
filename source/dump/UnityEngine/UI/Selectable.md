# Selectable

**Namespace:** `UnityEngine.UI`


## Fields

- `Boolean m_EnableCalled`

- `Navigation m_Navigation`

- `Transition m_Transition`

- `ColorBlock m_Colors`

- `SpriteState m_SpriteState`

- `AnimationTriggers m_AnimationTriggers`

- `Boolean m_Interactable`

- `Graphic m_TargetGraphic`

- `Boolean m_GroupsAllowInteraction`

- `Int32 m_CurrentIndex`

- `Boolean <isPointerInside>k__BackingField`

- `Boolean <isPointerDown>k__BackingField`

- `Boolean <hasSelection>k__BackingField`


## Properties

- `Navigation navigation`

- `Transition transition`

- `ColorBlock colors`

- `SpriteState spriteState`

- `AnimationTriggers animationTriggers`

- `Graphic targetGraphic`

- `Boolean interactable`

- `Boolean isPointerInside`

- `Boolean isPointerDown`

- `Boolean hasSelection`

- `Image image`

- `Animator animator`

- `SelectionState currentSelectionState`


## Methods

- `Navigation get_navigation()`

- `Void set_navigation(Navigation)`

- `Transition get_transition()`

- `Void set_transition(Transition)`

- `ColorBlock get_colors()`

- `Void set_colors(ColorBlock)`

- `SpriteState get_spriteState()`

- `Void set_spriteState(SpriteState)`

- `AnimationTriggers get_animationTriggers()`

- `Void set_animationTriggers(AnimationTriggers)`

- `Graphic get_targetGraphic()`

- `Void set_targetGraphic(Graphic)`

- `Boolean get_interactable()`

- `Void set_interactable(Boolean)`

- `Boolean get_isPointerInside()`

- `Void set_isPointerInside(Boolean)`

- `Boolean get_isPointerDown()`

- `Void set_isPointerDown(Boolean)`

- `Boolean get_hasSelection()`

- `Void set_hasSelection(Boolean)`

- `Image get_image()`

- `Void set_image(Image)`

- `Animator get_animator()`

- `Boolean ParentGroupAllowsInteraction()`

- `Void OnSetProperty()`

- `Void OnApplicationFocus(Boolean)`

- `SelectionState get_currentSelectionState()`

- `Selectable FindSelectable(Vector3)`

- `Void Navigate(AxisEventData, Selectable)`

- `Void StartColorTween(Color, Boolean)`

- `Void DoSpriteSwap(Sprite)`

- `Void TriggerAnimation(String)`

- `Boolean IsHighlighted()`

- `Boolean IsPressed()`

- `Void EvaluateAndTransitionToSelectionState()`


## Dump
```C#
// Dll : UnityEngine.UI.dll
// Namespace : UnityEngine.UI
public class Selectable : UIBehaviour, IMoveHandler, IEventSystemHandler, IPointerDownHandler, IPointerUpHandler, IPointerEnterHandler, IPointerExitHandler, ISelectHandler, IDeselectHandler
{
	protected static Selectable[] s_Selectables; // 0x0
	protected static Int32 s_SelectableCount; // 0x8
	private Boolean m_EnableCalled; // 0x18
	private Navigation m_Navigation; // 0x20
	private Transition m_Transition; // 0x48
	private ColorBlock m_Colors; // 0x4c
	private SpriteState m_SpriteState; // 0xa8
	private AnimationTriggers m_AnimationTriggers; // 0xc8
	private Boolean m_Interactable; // 0xd0
	private Graphic m_TargetGraphic; // 0xd8
	private Boolean m_GroupsAllowInteraction; // 0xe0
	protected Int32 m_CurrentIndex; // 0xe4
	private Boolean <isPointerInside>k__BackingField; // 0xe8
	private Boolean <isPointerDown>k__BackingField; // 0xe9
	private Boolean <hasSelection>k__BackingField; // 0xea
	private readonly List`1 m_CanvasGroupCache; // 0xf0

	public static Selectable[] allSelectablesArray { get; }
	public static Int32 allSelectableCount { get; }
	public static List`1 allSelectables { get; }
	public Navigation navigation { get; set; }
	public Transition transition { get; set; }
	public ColorBlock colors { get; set; }
	public SpriteState spriteState { get; set; }
	public AnimationTriggers animationTriggers { get; set; }
	public Graphic targetGraphic { get; set; }
	public Boolean interactable { get; set; }
	protected Boolean isPointerInside { get; set; }
	protected Boolean isPointerDown { get; set; }
	protected Boolean hasSelection { get; set; }
	public Image image { get; set; }
	public Animator animator { get; }
	protected SelectionState currentSelectionState { get; }

	// RVA: 0x6a65048 VA: 0x759907d048
	public static Selectable[] get_allSelectablesArray() { }
	// RVA: 0x6a650e4 VA: 0x759907d0e4
	public static Int32 get_allSelectableCount() { }
	// RVA: 0x6a6513c VA: 0x759907d13c
	public static List`1 get_allSelectables() { }
	// RVA: 0x6a651e0 VA: 0x759907d1e0
	public static Int32 AllSelectablesNoAlloc(Selectable[] selectables) { }
	// RVA: 0x6a6529c VA: 0x759907d29c
	public Navigation get_navigation() { }
	// RVA: 0x6a652b0 VA: 0x759907d2b0
	public Void set_navigation(Navigation value) { }
	// RVA: 0x6a6539c VA: 0x759907d39c
	public Transition get_transition() { }
	// RVA: 0x6a653a4 VA: 0x759907d3a4
	public Void set_transition(Transition value) { }
	// RVA: 0x6a65418 VA: 0x759907d418
	public ColorBlock get_colors() { }
	// RVA: 0x6a65428 VA: 0x759907d428
	public Void set_colors(ColorBlock value) { }
	// RVA: 0x6a654c0 VA: 0x759907d4c0
	public SpriteState get_spriteState() { }
	// RVA: 0x6a654d0 VA: 0x759907d4d0
	public Void set_spriteState(SpriteState value) { }
	// RVA: 0x6a6554c VA: 0x759907d54c
	public AnimationTriggers get_animationTriggers() { }
	// RVA: 0x6a65554 VA: 0x759907d554
	public Void set_animationTriggers(AnimationTriggers value) { }
	// RVA: 0x6a655c8 VA: 0x759907d5c8
	public Graphic get_targetGraphic() { }
	// RVA: 0x6a655d0 VA: 0x759907d5d0
	public Void set_targetGraphic(Graphic value) { }
	// RVA: 0x6a65644 VA: 0x759907d644
	public Boolean get_interactable() { }
	// RVA: 0x6a6564c VA: 0x759907d64c
	public Void set_interactable(Boolean value) { }
	// RVA: 0x6a657bc VA: 0x759907d7bc
	protected Boolean get_isPointerInside() { }
	// RVA: 0x6a657c4 VA: 0x759907d7c4
	protected Void set_isPointerInside(Boolean value) { }
	// RVA: 0x6a657d0 VA: 0x759907d7d0
	protected Boolean get_isPointerDown() { }
	// RVA: 0x6a657d8 VA: 0x759907d7d8
	protected Void set_isPointerDown(Boolean value) { }
	// RVA: 0x6a657e4 VA: 0x759907d7e4
	protected Boolean get_hasSelection() { }
	// RVA: 0x6a657ec VA: 0x759907d7ec
	protected Void set_hasSelection(Boolean value) { }
	// RVA: 0x6a5f7fc VA: 0x75990777fc
	protected Void .ctor() { }
	// RVA: 0x6a657f8 VA: 0x759907d7f8
	public Image get_image() { }
	// RVA: 0x6a65874 VA: 0x759907d874
	public Void set_image(Image value) { }
	// RVA: 0x6a6587c VA: 0x759907d87c
	public Animator get_animator() { }
	// RVA: 0x6a658c4 VA: 0x759907d8c4
	protected override Void Awake() { }
	// RVA: 0x6a65974 VA: 0x759907d974
	protected override Void OnCanvasGroupChanged() { }
	// RVA: 0x6a659a8 VA: 0x759907d9a8
	private Boolean ParentGroupAllowsInteraction() { }
	// RVA: 0x6a65b20 VA: 0x759907db20
	public virtual Boolean IsInteractable() { }
	// RVA: 0x6a65b40 VA: 0x759907db40
	protected override Void OnDidApplyAnimationProperties() { }
	// RVA: 0x6a5fc6c VA: 0x7599077c6c
	protected override Void OnEnable() { }
	// RVA: 0x6a65b94 VA: 0x759907db94
	protected override Void OnTransformParentChanged() { }
	// RVA: 0x6a65338 VA: 0x759907d338
	private Void OnSetProperty() { }
	// RVA: 0x6a5ff5c VA: 0x7599077f5c
	protected override Void OnDisable() { }
	// RVA: 0x6a65bbc VA: 0x759907dbbc
	private Void OnApplicationFocus(Boolean hasFocus) { }
	// RVA: 0x6a65b44 VA: 0x759907db44
	protected SelectionState get_currentSelectionState() { }
	// RVA: 0x6a65c64 VA: 0x759907dc64
	protected virtual Void InstantClearState() { }
	// RVA: 0x6a66014 VA: 0x759907e014
	protected virtual Void DoStateTransition(SelectionState state, Boolean instant) { }
	// RVA: 0x6a66238 VA: 0x759907e238
	public Selectable FindSelectable(Vector3 dir) { }
	// RVA: 0x6a666e4 VA: 0x759907e6e4
	private static Vector3 GetPointOnRectEdge(RectTransform rect, Vector2 dir) { }
	// RVA: 0x6a66888 VA: 0x759907e888
	private Void Navigate(AxisEventData eventData, Selectable sel) { }
	// RVA: 0x6a60d04 VA: 0x7599078d04
	public virtual Selectable FindSelectableOnLeft() { }
	// RVA: 0x6a60e00 VA: 0x7599078e00
	public virtual Selectable FindSelectableOnRight() { }
	// RVA: 0x6a60efc VA: 0x7599078efc
	public virtual Selectable FindSelectableOnUp() { }
	// RVA: 0x6a60ff8 VA: 0x7599078ff8
	public virtual Selectable FindSelectableOnDown() { }
	// RVA: 0x6a60c54 VA: 0x7599078c54
	public virtual Void OnMove(AxisEventData eventData) { }
	// RVA: 0x6a65cd4 VA: 0x759907dcd4
	private Void StartColorTween(Color targetColor, Boolean instant) { }
	// RVA: 0x6a65de4 VA: 0x759907dde4
	private Void DoSpriteSwap(Sprite newSprite) { }
	// RVA: 0x6a65e8c VA: 0x759907de8c
	private Void TriggerAnimation(String triggername) { }
	// RVA: 0x6a66940 VA: 0x759907e940
	protected Boolean IsHighlighted() { }
	// RVA: 0x6a65c18 VA: 0x759907dc18
	protected Boolean IsPressed() { }
	// RVA: 0x6a6699c VA: 0x759907e99c
	private Void EvaluateAndTransitionToSelectionState() { }
	// RVA: 0x6a60714 VA: 0x7599078714
	public virtual Void OnPointerDown(PointerEventData eventData) { }
	// RVA: 0x6a60968 VA: 0x7599078968
	public virtual Void OnPointerUp(PointerEventData eventData) { }
	// RVA: 0x6a66a34 VA: 0x759907ea34
	public virtual Void OnPointerEnter(PointerEventData eventData) { }
	// RVA: 0x6a66a40 VA: 0x759907ea40
	public virtual Void OnPointerExit(PointerEventData eventData) { }
	// RVA: 0x6a66a48 VA: 0x759907ea48
	public virtual Void OnSelect(BaseEventData eventData) { }
	// RVA: 0x6a66a54 VA: 0x759907ea54
	public virtual Void OnDeselect(BaseEventData eventData) { }
	// RVA: 0x6a66a5c VA: 0x759907ea5c
	public virtual Void Select() { }
	// RVA: 0x6a66b60 VA: 0x759907eb60
	private static Void .cctor() { }
}
```