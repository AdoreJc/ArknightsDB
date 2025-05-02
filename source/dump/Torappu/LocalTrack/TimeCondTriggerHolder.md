# TimeCondTriggerHolder

**Namespace:** `Torappu.LocalTrack`


## Methods

- `Void OnEnterGame()`

- `Void OnCrossDay()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.LocalTrack
public class TimeCondTriggerHolder : TrackTriggerHolder`1, IVersionTrackTriggerHolder
{
	private Dictionary`2 m_typedTriggers; // 0x20
	private static DelegateBridge __Hotfix0_OnTriggerAdded; // 0x0
	private static DelegateBridge __Hotfix0_OnEnterGame; // 0x8
	private static DelegateBridge __Hotfix0_OnCrossDay; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3f19ff8 VA: 0x7596531ff8
	protected override Void OnTriggerAdded(TimeCondTrigger trigger) { }
	// RVA: 0x3f1a1b4 VA: 0x75965321b4
	public Void OnEnterGame() { }
	// RVA: 0x3f1a3b0 VA: 0x75965323b0
	public Void OnCrossDay() { }
	// RVA: 0x3f1a414 VA: 0x7596532414
	public Void .ctor() { }
}
```