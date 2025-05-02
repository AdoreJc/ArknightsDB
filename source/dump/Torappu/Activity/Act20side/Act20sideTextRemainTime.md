# Act20sideTextRemainTime

**Namespace:** `Torappu.Activity.Act20side`


## Fields

- `Text _text`

- `Color _remainTimeColor`


## Methods

- `String _FormatRemainTime(TimeSpan)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act20side
public class Act20sideTextRemainTime : AbstractRemainTime
{
	private Text _text; // 0x18
	private Color _remainTimeColor; // 0x20
	private static DelegateBridge __Hotfix0_SetRemainTime; // 0x0
	private static DelegateBridge __Hotfix0__FormatRemainTime; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3302148 VA: 0x759591a148
	public override Void SetRemainTime(TimeSpan time) { }
	// RVA: 0x3302278 VA: 0x759591a278
	private String _FormatRemainTime(TimeSpan timeSpan) { }
	// RVA: 0x33024d0 VA: 0x759591a4d0
	public Void .ctor() { }
}
```