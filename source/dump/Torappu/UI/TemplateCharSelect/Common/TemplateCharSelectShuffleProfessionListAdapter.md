# TemplateCharSelectShuffleProfessionListAdapter

**Namespace:** `Torappu.UI.TemplateCharSelect.Common`


## Fields

- `ProfessionCategory currentProf`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateCharSelect.Common
public class TemplateCharSelectShuffleProfessionListAdapter : SimpleLayoutAdapter
{
	public static readonly List`1 PROFESSION_ORDER_LIST; // 0x0
	public Action`1 onProfClick; // 0x20
	public ProfessionCategory currentProf; // 0x28
	private static DelegateBridge __Hotfix0_get_count; // 0x8
	private static DelegateBridge __Hotfix0_RenderView; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override Int32 count { get; }

	// RVA: 0x2c5bda0 VA: 0x7595273da0
	public override Int32 get_count() { }
	// RVA: 0x2c5be48 VA: 0x7595273e48
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
	// RVA: 0x2c5b358 VA: 0x7595273358
	public Void .ctor() { }
	// RVA: 0x2c5c03c VA: 0x759527403c
	private static Void .cctor() { }
}
```