# DescListAdapter

**Namespace:** ` `


## Fields

- `RL04DifficultyItem m_item`


## Methods

- `Void Swtich(RoguelikeTopicDifficultyItemStatus, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class DescListAdapter : SimpleLayoutAdapter
{
	private RL04DifficultyItem m_item; // 0x20
	public List`1 descriptions; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_count; // 0x8
	private static DelegateBridge __Hotfix0_RenderView; // 0x10
	private static DelegateBridge __Hotfix0_Swtich; // 0x18

	public override Int32 count { get; }

	// RVA: 0x26e8f44 VA: 0x7594d00f44
	public Void .ctor(RL04DifficultyItem item) { }
	// RVA: 0x26e9dc4 VA: 0x7594d01dc4
	public override Int32 get_count() { }
	// RVA: 0x26e9e44 VA: 0x7594d01e44
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
	// RVA: 0x26e96f4 VA: 0x7594d016f4
	public Void Swtich(RoguelikeTopicDifficultyItemStatus stateName, Boolean immediately) { }
}
```