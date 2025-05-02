# RoguelikeFocusNodeView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `CanvasGroup _canvasGroup`

- `GameObject m_imageObj`

- `Image m_imageFocus`

- `Tween m_alphaTweener`

- `Tween m_posTweener`

- `RoguelikeDungeonController m_controller`

- `IRoguelikeFocusNodePlugin m_plugin`


## Methods

- `GameObject _LoadFocusImg(RoguelikeDungeonController, String)`

- `Void Init(RoguelikeDungeonController)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeFocusNodeView : DataBinder`1
{
	private const Single TWEEN_DURATION; // 0x0
	private CanvasGroup _canvasGroup; // 0x20
	private GameObject m_imageObj; // 0x28
	private Image m_imageFocus; // 0x30
	private Tween m_alphaTweener; // 0x38
	private Tween m_posTweener; // 0x40
	private RoguelikeDungeonController m_controller; // 0x48
	private IRoguelikeFocusNodePlugin m_plugin; // 0x50
	private static DelegateBridge __Hotfix0__LoadFocusImg; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2a14108 VA: 0x759502c108
	private GameObject _LoadFocusImg(RoguelikeDungeonController controller, String topicId) { }
	// RVA: 0x2a1424c VA: 0x759502c24c
	public override Void OnValueChanged(RoguelikeFocusViewProperty property) { }
	// RVA: 0x2a14578 VA: 0x759502c578
	public Void Init(RoguelikeDungeonController controller) { }
	// RVA: 0x2a1472c VA: 0x759502c72c
	public Void .ctor() { }
}
```