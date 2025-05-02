# RoguelikeExpeditionCharGridAdapter

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `GameObject itemPrefab`

- `RoguelikeExpeditionPluginContext pluginContext`

- `Boolean <isInit>k__BackingField`

- `String <selectedChar>k__BackingField`


## Properties

- `Boolean isInit`

- `String selectedChar`


## Methods

- `Boolean get_isInit()`

- `Void set_isInit(Boolean)`

- `String get_selectedChar()`

- `Void set_selectedChar(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeExpeditionCharGridAdapter : RecycleLoopScrollAdapter`2
{
	public Action`1 onItemClickEvent; // 0x68
	public GameObject itemPrefab; // 0x70
	public RoguelikeExpeditionPluginContext pluginContext; // 0x78
	private Boolean <isInit>k__BackingField; // 0x80
	private String <selectedChar>k__BackingField; // 0x88
	private static DelegateBridge __Hotfix0_get_isInit; // 0x0
	private static DelegateBridge __Hotfix0_set_isInit; // 0x8
	private static DelegateBridge __Hotfix0_get_selectedChar; // 0x10
	private static DelegateBridge __Hotfix0_set_selectedChar; // 0x18
	private static DelegateBridge __Hotfix0_UpdateView; // 0x20
	private static DelegateBridge __Hotfix0_ViewConstructor; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Boolean isInit { get; set; }
	public String selectedChar { get; set; }

	// RVA: 0x2a3527c VA: 0x759504d27c
	public Boolean get_isInit() { }
	// RVA: 0x2a352e4 VA: 0x759504d2e4
	public Void set_isInit(Boolean value) { }
	// RVA: 0x2a35364 VA: 0x759504d364
	public String get_selectedChar() { }
	// RVA: 0x2a353cc VA: 0x759504d3cc
	public Void set_selectedChar(String value) { }
	// RVA: 0x2a35450 VA: 0x759504d450
	public override Void UpdateView(Int32 position, GameObject view, RoguelikeExpeditionCharCardHolder holder, RoguelikeExpeditionCharCardViewModel data) { }
	// RVA: 0x2a355c4 VA: 0x759504d5c4
	protected override GameObject ViewConstructor(GameObjectPool objectPool) { }
	// RVA: 0x2a35680 VA: 0x759504d680
	public Void .ctor() { }
}
```