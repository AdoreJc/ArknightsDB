# UINotificationSlideLayouter

**Namespace:** `Torappu.UI.Notification`


## Fields

- `NotifyViewHost m_host`

- `VerticalLayoutGroup m_layout`


## Methods

- `NotifyWrapper _GenerateWrapper(NotifyView)`

- `Void _StartShowEffect(NotifyWrapper, Boolean, Single, String)`

- `Void _StartHideTween(NotifyWrapper)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Notification
public class UINotificationSlideLayouter : NotifyViewLayouter
{
	private const String NOTIFY_CONTAINER_NAME; // 0x0
	private const Single TWEEN_DURATION; // 0x0
	private NotifyViewHost m_host; // 0x10
	private VerticalLayoutGroup m_layout; // 0x18
	private ListDict`2 m_notifyList; // 0x20

	public override NotifyViewHost host { get; }
	public override Single toastPreDelay { get; }

	// RVA: 0x27268d4 VA: 0x7594d3e8d4
	public override NotifyViewHost get_host() { }
	// RVA: 0x27268dc VA: 0x7594d3e8dc
	public Void .ctor(NotifyViewHost controller, VerticalLayoutGroup layoutGroup) { }
	// RVA: 0x2726994 VA: 0x7594d3e994
	public override Single get_toastPreDelay() { }
	// RVA: 0x VA: 0x0
	protected override ViewType InstNotifyView(NotifyViewOptions`2 options) { }
	// RVA: 0x VA: 0x0
	public override Void AddNotifyView(NotifyView notifyView, NotifyViewOptions`2 options) { }
	// RVA: 0x27269a0 VA: 0x7594d3e9a0
	public override Void RemoveNotifyView(Int32 layoutId) { }
	// RVA: 0x2726d1c VA: 0x7594d3ed1c
	private NotifyWrapper _GenerateWrapper(NotifyView notifyView) { }
	// RVA: 0x2726f8c VA: 0x7594d3ef8c
	private Void _StartShowEffect(NotifyWrapper wrapper, Boolean toTheFront, Single delay, String audioSignal) { }
	// RVA: 0x2726a44 VA: 0x7594d3ea44
	private Void _StartHideTween(NotifyWrapper wrapper) { }
}
```