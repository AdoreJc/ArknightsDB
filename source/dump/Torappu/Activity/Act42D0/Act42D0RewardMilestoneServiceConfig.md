# Act42D0RewardMilestoneServiceConfig

**Namespace:** `Torappu.Activity.Act42D0`


## Fields

- `String m_actId`


## Methods

- `Void SendRewardMilestoneRequest()`

- `Void <SendRewardMilestoneRequest>b__4_0(Act42D0RecvMilestoneResponse)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42D0RewardMilestoneServiceConfig : IMilestoneServiceConfig
{
	private String m_actId; // 0x10
	private List`1 m_milestones; // 0x18
	private Action`1 m_onProceed; // 0x20


	// RVA: 0x320331c VA: 0x759581b31c
	public Void .ctor(String actId, List`1 milestones, Action`1 onProceed) { }
	// RVA: 0x320337c VA: 0x759581b37c
	public Void SendRewardMilestoneRequest() { }
	// RVA: 0x320352c VA: 0x759581b52c
	private Void <SendRewardMilestoneRequest>b__4_0(Act42D0RecvMilestoneResponse response) { }
}
```