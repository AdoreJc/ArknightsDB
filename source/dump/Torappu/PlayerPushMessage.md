# PlayerPushMessage

**Namespace:** `Torappu`


## Fields

- `String path`

- `JObject payload`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class PlayerPushMessage
{
	public const String PUSH_MSG_FIELD; // 0x0
	public String path; // 0x10
	public JObject payload; // 0x18


	// RVA: 0x32c9698 VA: 0x75958e1698
	public static PlayerPushMessage CreateFromJSON(JObjectWrapper jObj) { }
	// RVA: 0x32c98a8 VA: 0x75958e18a8
	public Void .ctor() { }
}
```