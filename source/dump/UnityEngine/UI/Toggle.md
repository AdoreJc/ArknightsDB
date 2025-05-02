# Toggle

**Namespace:** `UnityEngine.UI`


## Fields

- `ToggleTransition toggleTransition`

- `Graphic graphic`

- `ToggleGroup m_Group`

- `ToggleEvent onValueChanged`

- `Boolean m_IsOn`


## Properties

- `ToggleGroup group`

- `Boolean isOn`


## Methods

- `ToggleGroup get_group()`

- `Void set_group(ToggleGroup)`

- `Void SetToggleGroup(ToggleGroup, Boolean)`

- `Boolean get_isOn()`

- `Void set_isOn(Boolean)`

- `Void SetIsOnWithoutNotify(Boolean)`

- `Void Set(Boolean, Boolean)`

- `Void PlayEffect(Boolean)`

- `Void InternalToggle()`


## Dump
```C#
// Dll : UnityEngine.UI.dll
// Namespace : UnityEngine.UI
public class Toggle : Selectable, IPointerClickHandler, IEventSystemHandler, ISubmitHandler, ICanvasElement
{
	public ToggleTransition toggleTransition; // 0xf8
	public Graphic graphic; // 0x100
	private ToggleGroup m_Group; // 0x108
	public ToggleEvent onValueChanged; // 0x110
	private Boolean m_IsOn; // 0x118

	public ToggleGroup group { get; set; }
	public Boolean isOn { get; set; }

	// RVA: 0x6a6b1fc VA: 0x75990831fc
	public ToggleGroup get_group() { }
	// RVA: 0x6a6b204 VA: 0x7599083204
	public Void set_group(ToggleGroup value) { }
	// RVA: 0x6a6b440 VA: 0x7599083440
	protected Void .ctor() { }
	// RVA: 0x6a6b520 VA: 0x7599083520
	public virtual Void Rebuild(CanvasUpdate executing) { }
	// RVA: 0x6a6b524 VA: 0x7599083524
	public virtual Void LayoutComplete() { }
	// RVA: 0x6a6b528 VA: 0x7599083528
	public virtual Void GraphicUpdateComplete() { }
	// RVA: 0x6a6b52c VA: 0x759908352c
	protected override Void OnDestroy() { }
	// RVA: 0x6a6b998 VA: 0x7599083998
	protected override Void OnEnable() { }
	// RVA: 0x6a6b9c4 VA: 0x75990839c4
	protected override Void OnDisable() { }
	// RVA: 0x6a6b9e4 VA: 0x75990839e4
	protected override Void OnDidApplyAnimationProperties() { }
	// RVA: 0x6a6b224 VA: 0x7599083224
	private Void SetToggleGroup(ToggleGroup newGroup, Boolean setMemberValue) { }
	// RVA: 0x6a6bf00 VA: 0x7599083f00
	public Boolean get_isOn() { }
	// RVA: 0x6a6bf08 VA: 0x7599083f08
	public Void set_isOn(Boolean value) { }
	// RVA: 0x6a6bf14 VA: 0x7599083f14
	public Void SetIsOnWithoutNotify(Boolean value) { }
	// RVA: 0x6a6bb08 VA: 0x7599083b08
	private Void Set(Boolean value, Boolean sendCallback) { }
	// RVA: 0x6a6b37c VA: 0x759908337c
	private Void PlayEffect(Boolean instant) { }
	// RVA: 0x6a6c064 VA: 0x7599084064
	protected override Void Start() { }
	// RVA: 0x6a6c06c VA: 0x759908406c
	private Void InternalToggle() { }
	// RVA: 0x6a6c0c0 VA: 0x75990840c0
	public virtual Void OnPointerClick(PointerEventData eventData) { }
	// RVA: 0x6a6c0e4 VA: 0x75990840e4
	public virtual Void OnSubmit(BaseEventData eventData) { }
	// RVA: 0x6a6c0e8 VA: 0x75990840e8
	private Transform UnityEngine.UI.ICanvasElement.get_transform() { }
}
```