# TransitionParam

**Namespace:** ` `


## Fields

- `String topicId`

- `Boolean isAutoTrans`

- `Boolean isManualTrans`

- `RoguelikeGameZoneData zoneData`

- `TransitionChaosData chaos`

- `TransitionVisionData vision`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class TransitionParam : IHotfixable
{
	public String topicId; // 0x10
	public Boolean isAutoTrans; // 0x18
	public Boolean isManualTrans; // 0x19
	public RoguelikeGameZoneData zoneData; // 0x20
	public TransitionChaosData chaos; // 0x28
	public TransitionVisionData vision; // 0x30
	private static DelegateBridge __Hotfix0_Create; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2bb0e28 VA: 0x75951c8e28
	public static TransitionParam Create(RoguelikeDungeonZoneViewModel zoneModel) { }
	// RVA: 0x2bb2260 VA: 0x75951ca260
	public Void .ctor() { }
}
```