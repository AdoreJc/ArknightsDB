# GuidebookTriggerConfig

**Namespace:** `Torappu.UI`


## Fields

- `UIGuideTarget _autoShowTarget`

- `String _subsignal`


## Properties

- `UIGuideTarget autoShowTarget`

- `String subsignal`


## Methods

- `UIGuideTarget get_autoShowTarget()`

- `String get_subsignal()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class GuidebookTriggerConfig : ScriptableObject
{
	private String[] _pageIds; // 0x18
	private UIGuideTarget _autoShowTarget; // 0x20
	private String _subsignal; // 0x28

	public String[] pageIds { get; }
	public UIGuideTarget autoShowTarget { get; }
	public String subsignal { get; }

	// RVA: 0x217c5a0 VA: 0x75947945a0
	public String[] get_pageIds() { }
	// RVA: 0x217c5a8 VA: 0x75947945a8
	public UIGuideTarget get_autoShowTarget() { }
	// RVA: 0x217c5b0 VA: 0x75947945b0
	public String get_subsignal() { }
	// RVA: 0x217c5b8 VA: 0x75947945b8
	public Void .ctor() { }
}
```