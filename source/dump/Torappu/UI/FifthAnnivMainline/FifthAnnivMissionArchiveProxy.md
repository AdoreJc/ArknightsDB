# FifthAnnivMissionArchiveProxy

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivMissionArchiveProxy : MissionArchiveDataServiceProxy
{
	private static DelegateBridge __Hotfix0_LoadPlayerData; // 0x0
	private static DelegateBridge __Hotfix0_ClaimEntryReward; // 0x8
	private static DelegateBridge __Hotfix0_ClaimNodeReward; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x292db34 VA: 0x7594f45b34
	public override PlayerMissionArchive LoadPlayerData(String topicId) { }
	// RVA: 0x292dc10 VA: 0x7594f45c10
	public override Void ClaimEntryReward(String topicId, Action`1 onProceed) { }
	// RVA: 0x292de4c VA: 0x7594f45e4c
	public override Void ClaimNodeReward(String topicId, String nodeId, Action`1 onProceed) { }
	// RVA: 0x292e0a0 VA: 0x7594f460a0
	public Void .ctor() { }
}
```