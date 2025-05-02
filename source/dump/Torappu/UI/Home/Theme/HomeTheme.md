# HomeTheme

**Namespace:** `Torappu.UI.Home.Theme`


## Fields

- `String <themeId>k__BackingField`

- `JObject <jdata>k__BackingField`


## Properties

- `String themeId`

- `JObject jdata`


## Methods

- `String get_themeId()`

- `Void set_themeId(String)`

- `JObject get_jdata()`

- `Void set_jdata(JObject)`

- `Boolean Load(String)`

- `Void Unload()`

- `T LoadAsset(String)`

- `Int32 _GetAssetGroup()`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home.Theme
public class HomeTheme : UIStyle
{
	private String <themeId>k__BackingField; // 0x18
	private JObject <jdata>k__BackingField; // 0x20
	private static DelegateBridge __Hotfix0_get_themeId; // 0x0
	private static DelegateBridge __Hotfix0_set_themeId; // 0x8
	private static DelegateBridge __Hotfix0_get_jdata; // 0x10
	private static DelegateBridge __Hotfix0_set_jdata; // 0x18
	private static DelegateBridge __Hotfix0_Load; // 0x20
	private static DelegateBridge __Hotfix0_Unload; // 0x28
	private static DelegateBridge __Hotfix0_LoadAsset; // 0x30
	private static DelegateBridge __Hotfix0__GetAssetGroup; // 0x38
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public String themeId { get; set; }
	public JObject jdata { get; set; }

	// RVA: 0x284ab1c VA: 0x7594e62b1c
	public String get_themeId() { }
	// RVA: 0x284dae4 VA: 0x7594e65ae4
	private Void set_themeId(String value) { }
	// RVA: 0x284db68 VA: 0x7594e65b68
	public JObject get_jdata() { }
	// RVA: 0x284dbd0 VA: 0x7594e65bd0
	private Void set_jdata(JObject value) { }
	// RVA: 0x284dc54 VA: 0x7594e65c54
	public Boolean Load(String nThemeId) { }
	// RVA: 0x284def4 VA: 0x7594e65ef4
	public Void Unload() { }
	// RVA: 0x VA: 0x0
	public T LoadAsset(String resPath) { }
	// RVA: 0x284e018 VA: 0x7594e66018
	private Int32 _GetAssetGroup() { }
	// RVA: 0x284e084 VA: 0x7594e66084
	private Void OnDestroy() { }
	// RVA: 0x284e0ec VA: 0x7594e660ec
	public Void .ctor() { }
}
```