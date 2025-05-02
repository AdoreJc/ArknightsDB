# MissionRewardListAdapter

**Namespace:** ` `


## Fields

- `String m_actId`

- `Single m_itemScale`

- `Boolean m_isGot`

- `Color m_color`


## Methods

- `Void SetData(String, List`1, Single, Boolean, Color)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class MissionRewardListAdapter : SimpleLayoutAdapter
{
	private String m_actId; // 0x20
	private List`1 m_rewards; // 0x28
	private Single m_itemScale; // 0x30
	private Boolean m_isGot; // 0x34
	private Color m_color; // 0x38
	private static DelegateBridge __Hotfix0_get_count; // 0x0
	private static DelegateBridge __Hotfix0_RenderView; // 0x8
	private static DelegateBridge __Hotfix0_SetData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override Int32 count { get; }

	// RVA: 0x29ddfbc VA: 0x7594ff5fbc
	public override Int32 get_count() { }
	// RVA: 0x29de03c VA: 0x7594ff603c
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
	// RVA: 0x29de260 VA: 0x7594ff6260
	public Void SetData(String actId, List`1 rewards, Single itemScale, Boolean isTreasureGot, Color _completeItemColor) { }
	// RVA: 0x29de374 VA: 0x7594ff6374
	public Void .ctor() { }
}
```