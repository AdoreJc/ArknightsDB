# RL04AlchemyForecastViewModel

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `ForecastStatus <status>k__BackingField`

- `ForecastType <type>k__BackingField`

- `RL04AlchemyForecastDefinitenessItemViewModel <definitenessItemViewModel>k__BackingField`

- `RL04AlchemyForecastRandomViewModel <randomViewModel>k__BackingField`


## Properties

- `ForecastStatus status`

- `ForecastType type`

- `RL04AlchemyForecastDefinitenessItemViewModel definitenessItemViewModel`

- `RL04AlchemyForecastRandomViewModel randomViewModel`


## Methods

- `ForecastStatus get_status()`

- `Void set_status(ForecastStatus)`

- `ForecastType get_type()`

- `Void set_type(ForecastType)`

- `RL04AlchemyForecastDefinitenessItemViewModel get_definitenessItemViewModel()`

- `Void set_definitenessItemViewModel(RL04AlchemyForecastDefinitenessItemViewModel)`

- `RL04AlchemyForecastRandomViewModel get_randomViewModel()`

- `Void set_randomViewModel(RL04AlchemyForecastRandomViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04AlchemyForecastViewModel : IHotfixable
{
	private ForecastStatus <status>k__BackingField; // 0x10
	private ForecastType <type>k__BackingField; // 0x14
	private RL04AlchemyForecastDefinitenessItemViewModel <definitenessItemViewModel>k__BackingField; // 0x18
	private RL04AlchemyForecastRandomViewModel <randomViewModel>k__BackingField; // 0x20
	private static DelegateBridge __Hotfix0_get_status; // 0x0
	private static DelegateBridge __Hotfix0_set_status; // 0x8
	private static DelegateBridge __Hotfix0_get_type; // 0x10
	private static DelegateBridge __Hotfix0_set_type; // 0x18
	private static DelegateBridge __Hotfix0_get_definitenessItemViewModel; // 0x20
	private static DelegateBridge __Hotfix0_set_definitenessItemViewModel; // 0x28
	private static DelegateBridge __Hotfix0_get_randomViewModel; // 0x30
	private static DelegateBridge __Hotfix0_set_randomViewModel; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public ForecastStatus status { get; set; }
	public ForecastType type { get; set; }
	public RL04AlchemyForecastDefinitenessItemViewModel definitenessItemViewModel { get; set; }
	public RL04AlchemyForecastRandomViewModel randomViewModel { get; set; }

	// RVA: 0x2aff5c0 VA: 0x75951175c0
	public ForecastStatus get_status() { }
	// RVA: 0x2aff628 VA: 0x7595117628
	public Void set_status(ForecastStatus value) { }
	// RVA: 0x2aff6a4 VA: 0x75951176a4
	public ForecastType get_type() { }
	// RVA: 0x2aff70c VA: 0x759511770c
	public Void set_type(ForecastType value) { }
	// RVA: 0x2aff788 VA: 0x7595117788
	public RL04AlchemyForecastDefinitenessItemViewModel get_definitenessItemViewModel() { }
	// RVA: 0x2aff7f0 VA: 0x75951177f0
	public Void set_definitenessItemViewModel(RL04AlchemyForecastDefinitenessItemViewModel value) { }
	// RVA: 0x2aff874 VA: 0x7595117874
	public RL04AlchemyForecastRandomViewModel get_randomViewModel() { }
	// RVA: 0x2aff8dc VA: 0x75951178dc
	public Void set_randomViewModel(RL04AlchemyForecastRandomViewModel value) { }
	// RVA: 0x2aff960 VA: 0x7595117960
	public Void .ctor() { }
}
```