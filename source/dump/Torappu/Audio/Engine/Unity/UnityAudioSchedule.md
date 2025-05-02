# UnityAudioSchedule

**Namespace:** `Torappu.Audio.Engine.Unity`


## Fields

- `IEnumerator m_scheduleRoutine`


## Properties

- `Boolean isScheduling`


## Methods

- `Boolean get_isScheduling()`

- `Void StartAudioSchedule(ChannelAudioSource[], Int32, Single)`

- `Void StopAudioSchedule()`

- `IEnumerator _AudioScheduleCoroutine(ChannelAudioSource[], Int32, Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Audio.Engine.Unity
public class UnityAudioSchedule : IHotfixable
{
	private IEnumerator m_scheduleRoutine; // 0x10
	private static DelegateBridge __Hotfix0_get_isScheduling; // 0x0
	private static DelegateBridge __Hotfix0_StartAudioSchedule; // 0x8
	private static DelegateBridge __Hotfix0_StopAudioSchedule; // 0x10
	private static DelegateBridge __Hotfix0__AudioScheduleCoroutine; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Boolean isScheduling { get; }

	// RVA: 0x3ee7640 VA: 0x75964ff640
	public Boolean get_isScheduling() { }
	// RVA: 0x3ee89e8 VA: 0x75965009e8
	public Void StartAudioSchedule(ChannelAudioSource[] sources, Int32 count, Single delay) { }
	// RVA: 0x3ee7460 VA: 0x75964ff460
	public Void StopAudioSchedule() { }
	// RVA: 0x3ee8bb8 VA: 0x7596500bb8
	private IEnumerator _AudioScheduleCoroutine(ChannelAudioSource[] sources, Int32 count, Single delay) { }
	// RVA: 0x3ee6764 VA: 0x75964fe764
	public Void .ctor() { }
}
```