# RL03TopicChallengeGroupInfo

**Namespace:** ` `


## Fields

- `Int32 groupId`

- `Int32 challengeCount`

- `Boolean isGroupAllComplete`

- `Int32 firstUnCompleteIndex`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class RL03TopicChallengeGroupInfo : IHotfixable
{
	public Int32 groupId; // 0x10
	public Int32 challengeCount; // 0x14
	public Boolean isGroupAllComplete; // 0x18
	public Int32 firstUnCompleteIndex; // 0x1c
	public List`1 challengeStatus; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0


	// RVA: 0x2b8eb34 VA: 0x75951a6b34
	public Void .ctor() { }
}
```