# ActMultiV3MilestoneMainRewardItemView

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `ItemType _itemType`

- `Text _itemName`

- `Text _itemTypeName`

- `Text _itemDesc`

- `String m_cachedItemId`

- `UIStateFinder m_stateFinder`


## Methods

- `Void Render(String, String)`

- `Void _RenderSkin(String)`

- `Void _RenderNormalItem(String)`

- `Void OnCheckSkin()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3MilestoneMainRewardItemView : MonoBehaviour, IHotfixable
{
	private ItemType _itemType; // 0x18
	private Text _itemName; // 0x20
	private Text _itemTypeName; // 0x28
	private Text _itemDesc; // 0x30
	private String m_cachedItemId; // 0x38
	private UIStateFinder m_stateFinder; // 0x40
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__RenderSkin; // 0x8
	private static DelegateBridge __Hotfix0__RenderNormalItem; // 0x10
	private static DelegateBridge __Hotfix0_OnCheckSkin; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x30f34d8 VA: 0x759570b4d8
	public Void Render(String itemId, String itemDesc) { }
	// RVA: 0x30f35d0 VA: 0x759570b5d0
	private Void _RenderSkin(String itemId) { }
	// RVA: 0x30f3790 VA: 0x759570b790
	private Void _RenderNormalItem(String itemId) { }
	// RVA: 0x30f3860 VA: 0x759570b860
	public Void OnCheckSkin() { }
	// RVA: 0x30f3950 VA: 0x759570b950
	public Void .ctor() { }
}
```