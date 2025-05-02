# SandboxV2AdminMainBottomTab

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2AdminMainPanelType _panelType`

- `Graphic _graphic`

- `RectTransform m_rt`

- `Tweener m_tween`


## Properties

- `SandboxV2AdminMainPanelType panelType`

- `Boolean active`

- `Vector2 anchoredPosition`


## Methods

- `Void add_eClick(Action`1)`

- `Void remove_eClick(Action`1)`

- `SandboxV2AdminMainPanelType get_panelType()`

- `Void EventOnClick()`

- `Boolean get_active()`

- `Void set_active(Boolean)`

- `Void TweenToSelect(SandboxV2AdminMainPanelType, Single)`

- `Vector2 get_anchoredPosition()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminMainBottomTab : MonoBehaviour, IHotfixable
{
	private SandboxV2AdminMainPanelType _panelType; // 0x18
	private Graphic _graphic; // 0x20
	private RectTransform m_rt; // 0x28
	private Tweener m_tween; // 0x30
	private Action`1 eClick; // 0x38
	private static DelegateBridge __Hotfix0_add_eClick; // 0x0
	private static DelegateBridge __Hotfix0_remove_eClick; // 0x8
	private static DelegateBridge __Hotfix0_get_panelType; // 0x10
	private static DelegateBridge __Hotfix0_EventOnClick; // 0x18
	private static DelegateBridge __Hotfix0_get_active; // 0x20
	private static DelegateBridge __Hotfix0_set_active; // 0x28
	private static DelegateBridge __Hotfix0_TweenToSelect; // 0x30
	private static DelegateBridge __Hotfix0_get_anchoredPosition; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public SandboxV2AdminMainPanelType panelType { get; }
	public Boolean active { get; set; }
	public Vector2 anchoredPosition { get; }

	// RVA: 0x24d8290 VA: 0x7594af0290
	public Void add_eClick(Action`1 value) { }
	// RVA: 0x24d8384 VA: 0x7594af0384
	public Void remove_eClick(Action`1 value) { }
	// RVA: 0x24d8478 VA: 0x7594af0478
	public SandboxV2AdminMainPanelType get_panelType() { }
	// RVA: 0x24d84e0 VA: 0x7594af04e0
	public Void EventOnClick() { }
	// RVA: 0x24d8568 VA: 0x7594af0568
	public Boolean get_active() { }
	// RVA: 0x24d85e4 VA: 0x7594af05e4
	public Void set_active(Boolean value) { }
	// RVA: 0x24d8670 VA: 0x7594af0670
	public Void TweenToSelect(SandboxV2AdminMainPanelType selType, Single dur) { }
	// RVA: 0x24d87f0 VA: 0x7594af07f0
	public Vector2 get_anchoredPosition() { }
	// RVA: 0x24d88f8 VA: 0x7594af08f8
	public Void .ctor() { }
}
```