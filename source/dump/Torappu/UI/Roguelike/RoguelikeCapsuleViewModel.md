# RoguelikeCapsuleViewModel

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `String topicId`

- `String itemId`

- `String name`

- `String usage`

- `Boolean active`

- `Int64 ts`

- `Color color`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeCapsuleViewModel : IHotfixable
{
	public String topicId; // 0x10
	public String itemId; // 0x18
	public String name; // 0x20
	public String usage; // 0x28
	public Boolean active; // 0x30
	public Int64 ts; // 0x38
	public Color color; // 0x40
	private static DelegateBridge __Hotfix0_Create; // 0x0
	private static DelegateBridge __Hotfix1_Create; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x29f6c9c VA: 0x759500ec9c
	public static RoguelikeCapsuleViewModel Create(String topicId, Capsule capsule) { }
	// RVA: 0x29f6ed8 VA: 0x759500eed8
	public static RoguelikeCapsuleViewModel Create(String topicId, String capsuleId, Boolean isActive, Int64 ts) { }
	// RVA: 0x29f6e68 VA: 0x759500ee68
	public Void .ctor() { }
}
```