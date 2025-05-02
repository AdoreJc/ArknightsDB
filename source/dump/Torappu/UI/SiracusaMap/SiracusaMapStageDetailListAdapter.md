# SiracusaMapStageDetailListAdapter

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `GameObject _detailItem`


## Methods

- `Void set_onDetailItemClick(Action`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaMapStageDetailListAdapter : RecycleLoopScrollAdapter`2
{
	private GameObject _detailItem; // 0x68
	private Action`1 <onDetailItemClick>k__BackingField; // 0x70
	private static DelegateBridge __Hotfix0_get_onDetailItemClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onDetailItemClick; // 0x8
	private static DelegateBridge __Hotfix0_UpdateView; // 0x10
	private static DelegateBridge __Hotfix0_ViewConstructor; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action`1 onDetailItemClick { get; set; }

	// RVA: 0x23e2a44 VA: 0x75949faa44
	private Action`1 get_onDetailItemClick() { }
	// RVA: 0x23e2aac VA: 0x75949faaac
	public Void set_onDetailItemClick(Action`1 value) { }
	// RVA: 0x23e2b30 VA: 0x75949fab30
	public override Void UpdateView(Int32 position, GameObject view, SiracusaMapStageDetailItemHolder holder, SiracusaMapStageDetailInfoViewModel data) { }
	// RVA: 0x23e2c6c VA: 0x75949fac6c
	protected override GameObject ViewConstructor(GameObjectPool objectPool) { }
	// RVA: 0x23e2d90 VA: 0x75949fad90
	public Void .ctor() { }
}
```