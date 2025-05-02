# NotificationFloatLayouter

**Namespace:** `Torappu.Notification`


## Fields

- `NotifyViewHost m_host`

- `RectTransform m_layout`


## Methods

- `NotifyWrapper _GenerateWrapper(NotifyView)`

- `Void _StartShowEffect(NotifyWrapper, Single)`

- `Void _StartHideTween(NotifyWrapper)`

- `IEnumerator _HideWrapperCoroutine(NotifyWrapper)`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu.Notification
public class NotificationFloatLayouter : NotifyViewLayouter
{
	private NotifyViewHost m_host; // 0x10
	private RectTransform m_layout; // 0x18
	private ListDict`2 m_notifyList; // 0x20

	public override NotifyViewHost host { get; }

	// RVA: 0x67a9a8c VA: 0x7598dc1a8c
	public Void .ctor(NotifyViewHost host, RectTransform layoutGroup) { }
	// RVA: 0x67a9b44 VA: 0x7598dc1b44
	public override NotifyViewHost get_host() { }
	// RVA: 0x VA: 0x0
	protected override ViewType InstNotifyView(NotifyViewOptions`2 options) { }
	// RVA: 0x VA: 0x0
	public override Void AddNotifyView(NotifyView notifyView, NotifyViewOptions`2 options) { }
	// RVA: 0x67a9b4c VA: 0x7598dc1b4c
	public override Void RemoveNotifyView(Int32 layoutId) { }
	// RVA: 0x67a9c20 VA: 0x7598dc1c20
	private NotifyWrapper _GenerateWrapper(NotifyView notifyView) { }
	// RVA: 0x67a9d28 VA: 0x7598dc1d28
	private Void _StartShowEffect(NotifyWrapper wrapper, Single delay) { }
	// RVA: 0x67a9bf0 VA: 0x7598dc1bf0
	private Void _StartHideTween(NotifyWrapper wrapper) { }
	// RVA: 0x67aa0bc VA: 0x7598dc20bc
	private IEnumerator _HideWrapperCoroutine(NotifyWrapper wrapper) { }
}
```