# Act1VAutoChessBattleStartServiceConfig

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `String <actId>k__BackingField`


## Properties

- `String actId`


## Methods

- `String get_actId()`

- `Void set_actId(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessBattleStartServiceConfig : StartBattleServiceConfig`2
{
	private String <actId>k__BackingField; // 0x10
	private static DelegateBridge __Hotfix0_get_actId; // 0x0
	private static DelegateBridge __Hotfix0_set_actId; // 0x8
	private static DelegateBridge __Hotfix0_ParseRequest; // 0x10
	private static DelegateBridge __Hotfix0_get_serviceCode; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private String actId { get; set; }
	protected override String serviceCode { get; }

	// RVA: 0x33609a8 VA: 0x75959789a8
	private String get_actId() { }
	// RVA: 0x3360a10 VA: 0x7595978a10
	public Void set_actId(String value) { }
	// RVA: 0x3360a94 VA: 0x7595978a94
	protected override Act1VAutoChessBattleStartRequest ParseRequest() { }
	// RVA: 0x3360b44 VA: 0x7595978b44
	protected override String get_serviceCode() { }
	// RVA: 0x3360bc0 VA: 0x7595978bc0
	public Void .ctor() { }
}
```