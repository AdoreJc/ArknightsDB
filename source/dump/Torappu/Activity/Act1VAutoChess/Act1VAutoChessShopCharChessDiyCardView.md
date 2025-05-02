# Act1VAutoChessShopCharChessDiyCardView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Text _diyCountInfo`

- `String m_cachedChessSlotId`


## Methods

- `Void set_onItemClick(Action`1)`

- `Void Render(Act1VAutoChessShopCharChessDiyCardViewModel)`

- `Void OnItemCardClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessShopCharChessDiyCardView : MonoBehaviour, IHotfixable
{
	private Text _diyCountInfo; // 0x18
	private String m_cachedChessSlotId; // 0x20
	private Action`1 <onItemClick>k__BackingField; // 0x28
	private static DelegateBridge __Hotfix0_get_onItemClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onItemClick; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_OnItemCardClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Action`1 onItemClick { get; set; }

	// RVA: 0x331d790 VA: 0x7595935790
	public Action`1 get_onItemClick() { }
	// RVA: 0x331cb2c VA: 0x7595934b2c
	public Void set_onItemClick(Action`1 value) { }
	// RVA: 0x331cc18 VA: 0x7595934c18
	public Void Render(Act1VAutoChessShopCharChessDiyCardViewModel diyCardViewModel) { }
	// RVA: 0x331d930 VA: 0x7595935930
	public Void OnItemCardClick() { }
	// RVA: 0x331d9d0 VA: 0x75959359d0
	public Void .ctor() { }
}
```