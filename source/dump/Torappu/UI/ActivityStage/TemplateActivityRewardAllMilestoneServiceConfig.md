# TemplateActivityRewardAllMilestoneServiceConfig

**Namespace:** `Torappu.UI.ActivityStage`


## Fields

- `String m_actId`


## Methods

- `Void SendRewardMilestoneRequest()`

- `Void <SendRewardMilestoneRequest>b__3_0(ActivityRewardAllMilestoneResponse)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActivityStage
public class TemplateActivityRewardAllMilestoneServiceConfig : IMilestoneServiceConfig
{
	private String m_actId; // 0x10
	private Action`1 m_onProceed; // 0x18


	// RVA: 0x30abefc VA: 0x75956c3efc
	public Void .ctor(String actId, Action`1 onProceed) { }
	// RVA: 0x30abf40 VA: 0x75956c3f40
	public Void SendRewardMilestoneRequest() { }
	// RVA: 0x30ac0e8 VA: 0x75956c40e8
	private Void <SendRewardMilestoneRequest>b__3_0(ActivityRewardAllMilestoneResponse response) { }
}
```