# U8ExtraGameData

**Namespace:** `U8.SDK`


## Fields

- `Int32 <dataType>k__BackingField`

- `String <uid>k__BackingField`

- `String <roleID>k__BackingField`

- `String <roleName>k__BackingField`

- `String <roleLevel>k__BackingField`

- `Int32 <serverID>k__BackingField`

- `String <serverName>k__BackingField`

- `String <channel>k__BackingField`

- `String <subChannel>k__BackingField`


## Properties

- `Int32 dataType`

- `String uid`

- `String roleID`

- `String roleName`

- `String roleLevel`

- `Int32 serverID`

- `String serverName`

- `String channel`

- `String subChannel`


## Methods

- `Int32 get_dataType()`

- `Void set_dataType(Int32)`

- `String get_uid()`

- `Void set_uid(String)`

- `String get_roleID()`

- `Void set_roleID(String)`

- `String get_roleName()`

- `Void set_roleName(String)`

- `String get_roleLevel()`

- `Void set_roleLevel(String)`

- `Int32 get_serverID()`

- `Void set_serverID(Int32)`

- `String get_serverName()`

- `Void set_serverName(String)`

- `String get_channel()`

- `Void set_channel(String)`

- `String get_subChannel()`

- `Void set_subChannel(String)`


## Dump
```C#
// Dll : U8SDK.dll
// Namespace : U8.SDK
public class U8ExtraGameData
{
	public const Int32 TYPE_SELECT_SERVER; // 0x0
	public const Int32 TYPE_CREATE_ROLE; // 0x0
	public const Int32 TYPE_ENTER_GAME; // 0x0
	public const Int32 TYPE_LEVEL_UP; // 0x0
	public const Int32 TYPE_EXIT_GAME; // 0x0
	public const Int32 TYPE_STOP_GAME; // 0x0
	public const Int32 TYPE_APP_START; // 0x0
	public const Int32 TYPE_USER_LOGIN; // 0x0
	public const Int32 TYPE_USER_LOGOUT; // 0x0
	private Int32 <dataType>k__BackingField; // 0x10
	private String <uid>k__BackingField; // 0x18
	private String <roleID>k__BackingField; // 0x20
	private String <roleName>k__BackingField; // 0x28
	private String <roleLevel>k__BackingField; // 0x30
	private Int32 <serverID>k__BackingField; // 0x38
	private String <serverName>k__BackingField; // 0x40
	private String <channel>k__BackingField; // 0x48
	private String <subChannel>k__BackingField; // 0x50

	public Int32 dataType { get; set; }
	public String uid { get; set; }
	public String roleID { get; set; }
	public String roleName { get; set; }
	public String roleLevel { get; set; }
	public Int32 serverID { get; set; }
	public String serverName { get; set; }
	public String channel { get; set; }
	public String subChannel { get; set; }

	// RVA: 0x67e2e30 VA: 0x7598dfae30
	public Int32 get_dataType() { }
	// RVA: 0x67e2e38 VA: 0x7598dfae38
	public Void set_dataType(Int32 value) { }
	// RVA: 0x67e2e40 VA: 0x7598dfae40
	public String get_uid() { }
	// RVA: 0x67e2e48 VA: 0x7598dfae48
	public Void set_uid(String value) { }
	// RVA: 0x67e2e50 VA: 0x7598dfae50
	public String get_roleID() { }
	// RVA: 0x67e2e58 VA: 0x7598dfae58
	public Void set_roleID(String value) { }
	// RVA: 0x67e2e60 VA: 0x7598dfae60
	public String get_roleName() { }
	// RVA: 0x67e2e68 VA: 0x7598dfae68
	public Void set_roleName(String value) { }
	// RVA: 0x67e2e70 VA: 0x7598dfae70
	public String get_roleLevel() { }
	// RVA: 0x67e2e78 VA: 0x7598dfae78
	public Void set_roleLevel(String value) { }
	// RVA: 0x67e2e80 VA: 0x7598dfae80
	public Int32 get_serverID() { }
	// RVA: 0x67e2e88 VA: 0x7598dfae88
	public Void set_serverID(Int32 value) { }
	// RVA: 0x67e2e90 VA: 0x7598dfae90
	public String get_serverName() { }
	// RVA: 0x67e2e98 VA: 0x7598dfae98
	public Void set_serverName(String value) { }
	// RVA: 0x67e2ea0 VA: 0x7598dfaea0
	public String get_channel() { }
	// RVA: 0x67e2ea8 VA: 0x7598dfaea8
	public Void set_channel(String value) { }
	// RVA: 0x67e2eb0 VA: 0x7598dfaeb0
	public String get_subChannel() { }
	// RVA: 0x67e2eb8 VA: 0x7598dfaeb8
	public Void set_subChannel(String value) { }
	// RVA: 0x67e2ec0 VA: 0x7598dfaec0
	public Void .ctor() { }
}
```