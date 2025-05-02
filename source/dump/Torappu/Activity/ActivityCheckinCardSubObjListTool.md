# ActivityCheckinCardSubObjListTool

**Namespace:** `Torappu.Activity`


## Fields

- `Boolean m_hasAdapterInited`

- `SubItemListAdapter m_adapter`

- `SimpleLayoutContent m_subItemListContainer`


## Properties

- `SimpleLayoutContent subItemListContainer`


## Methods

- `Void set_subItemListContainer(SimpleLayoutContent)`

- `Void RenderCardSubObjList(SubItemListRenderConfig)`

- `Void _InitAdapterIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity
public class ActivityCheckinCardSubObjListTool : IHotfixable
{
	public static readonly ItemObjConfig ITEM_OBJ_CONFIG_EMPTY; // 0x0
	private Boolean m_hasAdapterInited; // 0x10
	private SubItemListAdapter m_adapter; // 0x18
	private SimpleLayoutContent m_subItemListContainer; // 0x20
	private static DelegateBridge __Hotfix0_set_subItemListContainer; // 0x10
	private static DelegateBridge __Hotfix0_RenderCardSubObjList; // 0x18
	private static DelegateBridge __Hotfix0__InitAdapterIfNot; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public SimpleLayoutContent subItemListContainer { set; }

	// RVA: 0x30d10fc VA: 0x75956e90fc
	public Void set_subItemListContainer(SimpleLayoutContent value) { }
	// RVA: 0x30d1200 VA: 0x75956e9200
	public Void RenderCardSubObjList(SubItemListRenderConfig renderConfig) { }
	// RVA: 0x30d1b64 VA: 0x75956e9b64
	private Void _InitAdapterIfNot() { }
	// RVA: 0x30d1040 VA: 0x75956e9040
	public Void .ctor() { }
	// RVA: 0x30d1cfc VA: 0x75956e9cfc
	private static Void .cctor() { }
}
```