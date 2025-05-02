# Act1LockSquadAssistStateBean

**Namespace:** `Torappu.Activity.Act1Lock.UI`


## Fields

- `Act1LockAssistViewProperty assistViewProperty`

- `SharedCharData assistData`

- `SquadFriendData friendData`

- `Boolean isSelected`


## Methods

- `Void SetData(Input)`

- `Void SetSkillSelected(Int32)`

- `Void GeneSquadFriendData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Lock.UI
public class Act1LockSquadAssistStateBean : IStateBean, IHotfixable, IDataBindWrapper
{
	public Act1LockAssistViewProperty assistViewProperty; // 0x10
	public SharedCharData assistData; // 0x18
	public SquadFriendData friendData; // 0x20
	public Boolean isSelected; // 0x28
	private static DelegateBridge __Hotfix0_SetData; // 0x0
	private static DelegateBridge __Hotfix0_SetSkillSelected; // 0x8
	private static DelegateBridge __Hotfix0_GeneSquadFriendData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x33d6de4 VA: 0x75959eede4
	public Void SetData(Input input) { }
	// RVA: 0x33d6edc VA: 0x75959eeedc
	public Void SetSkillSelected(Int32 index) { }
	// RVA: 0x33d6fac VA: 0x75959eefac
	public Void GeneSquadFriendData() { }
	// RVA: 0x33d70dc VA: 0x75959ef0dc
	public Void .ctor() { }
}
```