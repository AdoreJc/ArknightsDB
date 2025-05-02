# Act1ArcadeTopMenu

**Namespace:** `Torappu.Activity.Act1Arcade`


## Fields

- `RectTransform _backRect`

- `Action onClickBack`


## Properties

- `RectTransform backRect`


## Methods

- `RectTransform get_backRect()`

- `Void EventOnClickBack()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Arcade
public class Act1ArcadeTopMenu : MonoBehaviour, IHotfixable
{
	public RectTransform _backRect; // 0x18
	public Action onClickBack; // 0x20
	private static DelegateBridge __Hotfix0_get_backRect; // 0x0
	private static DelegateBridge __Hotfix0_EventOnClickBack; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public RectTransform backRect { get; }

	// RVA: 0x3417abc VA: 0x7595a2fabc
	public RectTransform get_backRect() { }
	// RVA: 0x3417b24 VA: 0x7595a2fb24
	public Void EventOnClickBack() { }
	// RVA: 0x3417ba8 VA: 0x7595a2fba8
	public Void .ctor() { }
}
```