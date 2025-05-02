# RL02OuterBuffNodeGroupView

**Namespace:** `Torappu.UI.RoguelikeTopic.RL02`


## Fields

- `RectTransform _container`

- `Adapter m_adapter`

- `UIPage m_page`


## Methods

- `Void set_onNodeClicked(Action`1)`

- `Void OnInit(UIPage)`

- `Void Render(ListDict`2, RenderConfig)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL02
public class RL02OuterBuffNodeGroupView : MonoBehaviour, IHotfixable
{
	private RL02OuterBuffNodeItemView[] _nodePrefab; // 0x18
	private RectTransform _container; // 0x20
	private Adapter m_adapter; // 0x28
	private UIPage m_page; // 0x30
	private Action`1 <onNodeClicked>k__BackingField; // 0x38
	private static DelegateBridge __Hotfix0_get_onNodeClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onNodeClicked; // 0x8
	private static DelegateBridge __Hotfix0_OnInit; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action`1 onNodeClicked { get; set; }

	// RVA: 0x26c238c VA: 0x7594cda38c
	private Action`1 get_onNodeClicked() { }
	// RVA: 0x26c18b8 VA: 0x7594cd98b8
	public Void set_onNodeClicked(Action`1 value) { }
	// RVA: 0x26c193c VA: 0x7594cd993c
	public Void OnInit(UIPage page) { }
	// RVA: 0x26c1af0 VA: 0x7594cd9af0
	public Void Render(ListDict`2 viewModelList, RenderConfig config) { }
	// RVA: 0x26c293c VA: 0x7594cda93c
	public Void .ctor() { }
}
```