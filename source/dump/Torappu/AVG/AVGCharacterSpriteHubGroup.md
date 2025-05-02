# AVGCharacterSpriteHubGroup

**Namespace:** `Torappu.AVG`


## Methods

- `Void SetImage(AlphaSplitImageHolder, Int32, String, Single, Single)`

- `Void SetImage(AlphaSplitImageHolder, Int32, Int32, Single, Single)`

- `Void _PickSetImageImpl(AlphaSplitImageHolder, SpriteConfig, Int32, Single, Single)`

- `Void _SetImage(AlphaSplitImageHolder, SpriteConfig, SpriteConfig, Int32, Single, Single)`

- `Boolean _HasFace(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AVGCharacterSpriteHubGroup : MonoBehaviour, IHotfixable
{
	public SpriteConfigGroup[] spriteGroups; // 0x18
	private static DelegateBridge __Hotfix0_SetImage; // 0x0
	private static DelegateBridge __Hotfix1_SetImage; // 0x8
	private static DelegateBridge __Hotfix0__PickSetImageImpl; // 0x10
	private static DelegateBridge __Hotfix0__SetImage; // 0x18
	private static DelegateBridge __Hotfix0__HasFace; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x3e9d784 VA: 0x75964b5784
	public Void SetImage(AlphaSplitImageHolder imageHolder, Int32 body, String alias, Single blackStart, Single blackEnd) { }
	// RVA: 0x3e9ddb8 VA: 0x75964b5db8
	public Void SetImage(AlphaSplitImageHolder imageHolder, Int32 body, Int32 index, Single blackStart, Single blackEnd) { }
	// RVA: 0x3ea47a4 VA: 0x75964bc7a4
	private Void _PickSetImageImpl(AlphaSplitImageHolder imageHolder, SpriteConfig targetConfig, Int32 body, Single blackStart, Single blackEnd) { }
	// RVA: 0x3ea4ad8 VA: 0x75964bcad8
	private Void _SetImage(AlphaSplitImageHolder imageHolder, SpriteConfig charConfig, SpriteConfig faceConfig, Int32 body, Single blackStart, Single blackEnd) { }
	// RVA: 0x3ea49a4 VA: 0x75964bc9a4
	private Boolean _HasFace(Int32 body) { }
	// RVA: 0x3ea506c VA: 0x75964bd06c
	public Void .ctor() { }
}
```