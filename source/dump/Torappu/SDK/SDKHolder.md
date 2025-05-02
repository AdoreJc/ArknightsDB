# SDKHolder

**Namespace:** `Torappu.SDK`


## Fields

- `SDKType _curType`

- `GameObject _curSDKObj`


## Properties

- `SDKType type`

- `GameObject SDKObj`


## Methods

- `SDKType get_type()`

- `Void set_type(SDKType)`

- `GameObject get_SDKObj()`

- `Void _SetSDKTypeAndSave(SDKType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.SDK
public class SDKHolder : SingletonScriptableObject`1
{
	private SDKType _curType; // 0x18
	private GameObject _curSDKObj; // 0x20
	private List`1 _SDKs; // 0x28

	public SDKType type { get; set; }
	public GameObject SDKObj { get; }

	// RVA: 0x357c360 VA: 0x7595b94360
	public SDKType get_type() { }
	// RVA: 0x357c368 VA: 0x7595b94368
	public Void set_type(SDKType value) { }
	// RVA: 0x357c370 VA: 0x7595b94370
	public GameObject get_SDKObj() { }
	// RVA: 0x357c378 VA: 0x7595b94378
	public static ISDKBase FindSDKComponent(GameObject obj) { }
	// RVA: 0x357c36c VA: 0x7595b9436c
	private Void _SetSDKTypeAndSave(SDKType targetType) { }
	// RVA: 0x357c618 VA: 0x7595b94618
	public Void .ctor() { }
}
```