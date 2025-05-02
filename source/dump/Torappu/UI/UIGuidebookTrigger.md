# UIGuidebookTrigger

**Namespace:** `Torappu.UI`


## Fields

- `UIGuideTarget _autoShowTarget`

- `String _subsignal`

- `String _dynConfig`

- `Config m_config`

- `RefCountReference m_pageBlockRef`

- `UIBlockHandler m_pageBlocker`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void Start()`

- `Void OnDestroy()`

- `Void OnClicked()`

- `Void ManualTrigger()`

- `Boolean OnAutoShow(UIGuideTarget, String)`

- `Void _OnGuidebookClosed()`

- `Void _OnGuideBookOpen()`

- `Void _DoTriggerImpl()`

- `Void _OpenGuidebook()`

- `Void _ClearPageBlocker()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIGuidebookTrigger : MonoBehaviour, IGuidebookListener
{
	private String[] _pageIds; // 0x18
	private UIGuideTarget _autoShowTarget; // 0x20
	private String _subsignal; // 0x28
	private String _dynConfig; // 0x30
	private Config m_config; // 0x38
	private RefCountReference m_pageBlockRef; // 0x50
	private UIBlockHandler m_pageBlocker; // 0x58
	private Boolean m_isInited; // 0x60


	// RVA: 0x217e748 VA: 0x7594796748
	private Void _InitIfNot() { }
	// RVA: 0x217e944 VA: 0x7594796944
	public Void Start() { }
	// RVA: 0x217e95c VA: 0x759479695c
	public Void OnDestroy() { }
	// RVA: 0x217e960 VA: 0x7594796960
	public Void OnClicked() { }
	// RVA: 0x217e990 VA: 0x7594796990
	public Void ManualTrigger() { }
	// RVA: 0x217e9a8 VA: 0x75947969a8
	public Boolean OnAutoShow(UIGuideTarget target, String subsignal) { }
	// RVA: 0x217ebac VA: 0x7594796bac
	private Void _OnGuidebookClosed() { }
	// RVA: 0x217ec70 VA: 0x7594796c70
	private Void _OnGuideBookOpen() { }
	// RVA: 0x217e978 VA: 0x7594796978
	private Void _DoTriggerImpl() { }
	// RVA: 0x217eb1c VA: 0x7594796b1c
	private Void _OpenGuidebook() { }
	// RVA: 0x217ec30 VA: 0x7594796c30
	private Void _ClearPageBlocker() { }
	// RVA: 0x217ed7c VA: 0x7594796d7c
	public Void .ctor() { }
}
```