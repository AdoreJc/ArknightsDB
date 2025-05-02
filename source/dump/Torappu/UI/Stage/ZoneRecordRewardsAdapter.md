# ZoneRecordRewardsAdapter

**Namespace:** `Torappu.UI.Stage`


## Fields

- `Single scaleFactor`

- `Color mainColor`

- `Boolean showLeftTime`

- `Boolean showLimitPart`

- `GameObject m_itemPrefab`


## Methods

- `Void _OnItemCardClicked(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class ZoneRecordRewardsAdapter : SimpleLayoutAdapter
{
	public List`1 rewardList; // 0x20
	public List`1 itemCards; // 0x28
	public Single scaleFactor; // 0x30
	public Color mainColor; // 0x34
	public Boolean showLeftTime; // 0x44
	public Boolean showLimitPart; // 0x45
	private GameObject m_itemPrefab; // 0x48
	private static DelegateBridge __Hotfix0_get_count; // 0x0
	private static DelegateBridge __Hotfix0_RenderView; // 0x8
	private static DelegateBridge __Hotfix0__OnItemCardClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override Int32 count { get; }

	// RVA: 0x2fc2c10 VA: 0x75955dac10
	public override Int32 get_count() { }
	// RVA: 0x2fc2c90 VA: 0x75955dac90
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
	// RVA: 0x2fc320c VA: 0x75955db20c
	private Void _OnItemCardClicked(Int32 position) { }
	// RVA: 0x2fc2620 VA: 0x75955da620
	public Void .ctor() { }
}
```