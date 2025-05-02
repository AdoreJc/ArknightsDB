# PhotoRewardAdapter

**Namespace:** ` `


## Fields

- `Boolean m_hasRecieved`


## Methods

- `Void RefreshStatus(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class PhotoRewardAdapter : SimpleLayoutAdapter
{
	public List`1 dataSource; // 0x20
	private Boolean m_hasRecieved; // 0x28
	private static DelegateBridge __Hotfix0_get_count; // 0x0
	private static DelegateBridge __Hotfix0_RefreshStatus; // 0x8
	private static DelegateBridge __Hotfix0_RenderView; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override Int32 count { get; }

	// RVA: 0x3119db4 VA: 0x7595731db4
	public override Int32 get_count() { }
	// RVA: 0x31191a4 VA: 0x75957311a4
	public Void RefreshStatus(Boolean hasRecieved) { }
	// RVA: 0x3119e34 VA: 0x7595731e34
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
	// RVA: 0x311950c VA: 0x759573150c
	public Void .ctor() { }
}
```