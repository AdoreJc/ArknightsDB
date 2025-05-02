# CampaignWorldObjectHolder

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `String _id`

- `ViewType _viewPrefab`

- `ConfigType _config`

- `ViewType m_view`


## Properties

- `String id`

- `ViewType viewPrefab`

- `ConfigType config`

- `ViewType view`


## Methods

- `String get_id()`

- `ViewType get_viewPrefab()`

- `ConfigType get_config()`

- `Void set_config(ConfigType)`

- `ViewType get_view()`

- `ViewType TryCreateView()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class CampaignWorldObjectHolder`2 : MonoBehaviour, IHotfixable
{
	private String _id; // 0x0
	private ViewType _viewPrefab; // 0x0
	private ConfigType _config; // 0x0
	private ViewType m_view; // 0x0
	private static DelegateBridge __Hotfix0_get_id; // 0x0
	private static DelegateBridge __Hotfix0_get_viewPrefab; // 0x0
	private static DelegateBridge __Hotfix0_get_config; // 0x0
	private static DelegateBridge __Hotfix0_set_config; // 0x0
	private static DelegateBridge __Hotfix0_get_view; // 0x0
	private static DelegateBridge __Hotfix0_TryCreateView; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0

	public String id { get; }
	public ViewType viewPrefab { get; }
	public ConfigType config { get; set; }
	public ViewType view { get; }

	// RVA: 0x VA: 0x0
	public String get_id() { }
	// RVA: 0x VA: 0x0
	public ViewType get_viewPrefab() { }
	// RVA: 0x VA: 0x0
	public ConfigType get_config() { }
	// RVA: 0x VA: 0x0
	public Void set_config(ConfigType value) { }
	// RVA: 0x VA: 0x0
	public ViewType get_view() { }
	// RVA: 0x VA: 0x0
	public ViewType TryCreateView() { }
	// RVA: 0x VA: 0x0
	public Void .ctor() { }
}
```