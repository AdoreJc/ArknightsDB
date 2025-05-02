# UIPageListener

**Namespace:** `Torappu.UI`


## Fields

- `Action onCreate`

- `Action onReuse`

- `Action onStart`

- `Action onPageReady`

- `Action onPageRouted`

- `Action onStop`

- `Action onRecycle`

- `Action onDestroy`

- `UIPage <page>k__BackingField`


## Properties

- `UIPage page`


## Methods

- `UIPage get_page()`

- `Void set_page(UIPage)`

- `Boolean BindListener(MonoBehaviour)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIPageListener : IHotfixable
{
	public Action onCreate; // 0x10
	public Action onReuse; // 0x18
	public Action onStart; // 0x20
	public Action onPageReady; // 0x28
	public Action onPageRouted; // 0x30
	public Action onStop; // 0x38
	public Action onRecycle; // 0x40
	public Action onDestroy; // 0x48
	public Action`1 beforeHideCoroutine; // 0x50
	private UIPage <page>k__BackingField; // 0x58
	private static DelegateBridge __Hotfix0_get_page; // 0x0
	private static DelegateBridge __Hotfix0_set_page; // 0x8
	private static DelegateBridge __Hotfix0_BindListener; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public UIPage page { get; set; }

	// RVA: 0x21500d8 VA: 0x75947680d8
	public UIPage get_page() { }
	// RVA: 0x21515c4 VA: 0x75947695c4
	private Void set_page(UIPage value) { }
	// RVA: 0x21506cc VA: 0x75947686cc
	public Boolean BindListener(MonoBehaviour owner) { }
	// RVA: 0x2150ccc VA: 0x7594768ccc
	public Void .ctor() { }
}
```