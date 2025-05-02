# TemplateActivityRewardMilestoneServiceConfig

**Namespace:** `Torappu.UI.ActivityStage`


## Fields

- `String m_actId`

- `String m_milestoneId`


## Methods

- `Void SendRewardMilestoneRequest()`

- `Void <SendRewardMilestoneRequest>b__4_0(ActivityRewardMilestoneResponse)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActivityStage
public class TemplateActivityRewardMilestoneServiceConfig : IMilestoneServiceConfig
{
	private String m_actId; // 0x10
	private String m_milestoneId; // 0x18
	private Action`1 m_onProceed; // 0x20


	// RVA: 0x30abcb0 VA: 0x75956c3cb0
	public Void .ctor(String actId, String milestoneId, Action`1 onProceed) { }
	// RVA: 0x30abd10 VA: 0x75956c3d10
	public Void SendRewardMilestoneRequest() { }
	// RVA: 0x30abec8 VA: 0x75956c3ec8
	private Void <SendRewardMilestoneRequest>b__4_0(ActivityRewardMilestoneResponse response) { }
}
```