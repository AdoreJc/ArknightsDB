# GroceryHomeLaunchView

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `CanvasGroup _canvasGroup`

- `SimpleLayoutContent _contentGoodGroup`

- `RectTransform _rectBack`

- `Boolean m_hasInited`

- `FadeSwitchTween m_fadeSwitchTween`

- `Adapter m_adapter`

- `UIStateFinder m_stateFinder`


## Methods

- `Void EventOnBackClick()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GroceryHomeLaunchView : DataBinder`1, IHotfixable
{
	private CanvasGroup _canvasGroup; // 0x20
	private SimpleLayoutContent _contentGoodGroup; // 0x28
	private RectTransform _rectBack; // 0x30
	private Boolean m_hasInited; // 0x38
	private FadeSwitchTween m_fadeSwitchTween; // 0x40
	private List`1 m_cachedGroupList; // 0x48
	private Adapter m_adapter; // 0x50
	private UIStateFinder m_stateFinder; // 0x58
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_EventOnBackClick; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2860290 VA: 0x7594e78290
	public override Void OnValueChanged(GroceryHomeProperty property) { }
	// RVA: 0x286055c VA: 0x7594e7855c
	public Void EventOnBackClick() { }
	// RVA: 0x2860390 VA: 0x7594e78390
	private Void _InitIfNot() { }
	// RVA: 0x28606dc VA: 0x7594e786dc
	public Void .ctor() { }
}
```