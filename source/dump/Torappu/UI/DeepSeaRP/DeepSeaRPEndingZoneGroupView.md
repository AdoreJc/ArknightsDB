# DeepSeaRPEndingZoneGroupView

**Namespace:** `Torappu.UI.DeepSeaRP`


## Fields

- `RectTransform _transContainer`

- `AnimationWrapper _wrapper`


## Methods

- `Void set_onZoneClicked(Action`1)`

- `Void Render(List`1, String)`

- `Void _EventOnZoneClick(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.DeepSeaRP
public class DeepSeaRPEndingZoneGroupView : MonoBehaviour, IHotfixable
{
	private RectTransform _transContainer; // 0x18
	private List`1 _zoneViewList; // 0x20
	private AnimationWrapper _wrapper; // 0x28
	private const Single CONTAINER_POS_ONE_BIG_ZONE; // 0x0
	private const Single CONTAINER_POS_TWO_BIG_ZONE; // 0x0
	private const Single CONTAINER_POS_THREE_BIG_ZONE; // 0x0
	private const String FADE_IN_PARAM; // 0x0
	private Action`1 <onZoneClicked>k__BackingField; // 0x30
	private static DelegateBridge __Hotfix0_get_onZoneClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onZoneClicked; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__EventOnZoneClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action`1 onZoneClicked { get; set; }

	// RVA: 0x29d9144 VA: 0x7594ff1144
	private Action`1 get_onZoneClicked() { }
	// RVA: 0x29d89d8 VA: 0x7594ff09d8
	public Void set_onZoneClicked(Action`1 value) { }
	// RVA: 0x29d86f0 VA: 0x7594ff06f0
	public Void Render(List`1 zoneMapModelList, String selectedZoneId) { }
	// RVA: 0x29d9458 VA: 0x7594ff1458
	private Void _EventOnZoneClick(String zoneId) { }
	// RVA: 0x29d9510 VA: 0x7594ff1510
	public Void .ctor() { }
}
```