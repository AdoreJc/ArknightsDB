# Act9D0BannableObject

**Namespace:** `Torappu.Activity.Act9D0`


## Fields

- `String _key`


## Properties

- `String key`


## Methods

- `String get_key()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act9D0
public class Act9D0BannableObject : MonoBehaviour, IHotfixable
{
	private String _key; // 0x18
	private List`1 _sprites; // 0x20
	private static DelegateBridge __Hotfix0_get_key; // 0x0
	private static DelegateBridge __Hotfix0_get_sprites; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public String key { get; }
	public List`1 sprites { get; }

	// RVA: 0x31aeca8 VA: 0x75957c6ca8
	public String get_key() { }
	// RVA: 0x31aed10 VA: 0x75957c6d10
	public List`1 get_sprites() { }
	// RVA: 0x31aed78 VA: 0x75957c6d78
	public Void .ctor() { }
}
```